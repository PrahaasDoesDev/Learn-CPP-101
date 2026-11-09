# Chapter 0: Installing and Setting Up Your C++ Environment

Before writing C++, you need three things:

1. **A compiler** to translate C++ source code into a program.
2. **A code editor** to write and edit source files.
3. **A terminal and debugger** to run programs and investigate problems.

This guide sets up Visual Studio Code and a C++ toolchain. Follow the section for your operating system. You can use another editor if you prefer, but you still need a compiler.

## Windows: Visual Studio Code and GCC

These steps use GCC through MSYS2's UCRT64 environment.

### 1. Install Visual Studio Code

Download and install [Visual Studio Code](https://code.visualstudio.com/). During setup, enabling the options to add `code` to PATH and to add **Open with Code** to the context menu is helpful.

### 2. Install MSYS2 and GCC

1. Download and install [MSYS2](https://www.msys2.org/). The default install location, `C:\msys64`, is used in the examples below.
2. Open **MSYS2 UCRT64** from the Start menu. Use the UCRT64 terminal for the following commands.
3. Update the package database and installed packages:

   ```sh
   pacman -Syu
   ```

   If MSYS2 asks you to close the terminal, close it, reopen **MSYS2 UCRT64**, and run the update command again if instructed.
4. Install the compiler, debugger, and build tools:

   ```sh
   pacman -S --needed mingw-w64-ucrt-x86_64-gcc mingw-w64-ucrt-x86_64-gdb mingw-w64-ucrt-x86_64-make
   ```

### 3. Add GCC to PATH

Add the UCRT64 binary folder to your Windows user `Path`:

```text
C:\msys64\ucrt64\bin
```

To edit it, search Windows for **Edit environment variables for your account**, select `Path`, choose **Edit**, and add the folder as a new entry. If you installed MSYS2 somewhere other than `C:\msys64`, use your actual install path.

Close and reopen terminals and VS Code so they pick up the updated PATH. Do not add the MSYS2 `usr\bin` folder for this setup; use the UCRT64 `bin` folder.

### 4. Install the C++ extension

In VS Code, open **Extensions** (`Ctrl+Shift+X`), search for **C/C++** by Microsoft, and install it. This extension provides editing support, IntelliSense, and debugger integration; it does **not** install a compiler.

### 5. Verify the toolchain

Open a new PowerShell or VS Code terminal and run:

```powershell
g++ --version
gdb --version
```

Both commands should print version information. If Windows says a command is not recognized, check that the UCRT64 `bin` directory is in your user `Path`, then restart the terminal.

## Linux

Install a compiler, debugger, and build tools using your distribution's package manager. For Ubuntu or Debian:

```sh
sudo apt update
sudo apt install build-essential gdb
```

For Fedora:

```sh
sudo dnf install gcc-c++ gdb make
```

Install [Visual Studio Code](https://code.visualstudio.com/) using the instructions for your distribution, then install the **C/C++** extension by Microsoft. Verify the installation:

```sh
g++ --version
gdb --version
```

Package names can differ on other distributions; use the distribution's documentation if these commands do not apply.

## macOS

Install Apple's command-line developer tools:

```sh
xcode-select --install
```

Install [Visual Studio Code](https://code.visualstudio.com/) and its Microsoft **C/C++** extension. Verify that the compiler is available:

```sh
clang++ --version
```

The command-line tools provide Apple's Clang compiler and debugger. If macOS prompts you to accept a license or install additional components, follow the prompt and retry the version check.

## Compile and run a test program

After installing a compiler, open the course folder in a terminal and build the sample program. Use the command for your platform.

On Windows with GCC:

```powershell
g++ -std=c++20 -Wall -Wextra -pedantic main.cpp -o main.exe
.\main.exe
```

On Linux with GCC:

```sh
g++ -std=c++20 -Wall -Wextra -pedantic main.cpp -o main
./main
```

On macOS with Clang:

```sh
clang++ -std=c++20 -Wall -Wextra -pedantic main.cpp -o main
./main
```

With MSVC from a Developer Command Prompt or Developer PowerShell, use:

```powershell
cl /std:c++20 /EHsc /W4 main.cpp
.\main.exe
```

You should see binary, decimal, and hexadecimal representations of a number, followed by its bytes. Byte order depends on the computer's architecture.

## Open and build in VS Code

1. Open VS Code and choose **File > Open Folder...**, then select the course repository.
2. Open `main.cpp`.
3. Open the integrated terminal with **Terminal > New Terminal** and run the compile command above.
4. To use the VS Code build tasks, open **Terminal > Run Build Task...** and choose a task for your installed compiler.

The repository's `.vscode` settings are examples and may need editing on your computer. In particular:

- `tasks.json` contains compiler paths that are specific to the original machine.
- The GCC and Clang tasks use the C++26 language mode, while the MSVC task uses C++20.
- `c_cpp_properties.json` points IntelliSense at MSVC by default and also selects C++26.

Update the compiler path, IntelliSense compiler, and language standard to match the toolchain you installed. The command-line build instructions in this chapter work independently of those VS Code settings.

## Common setup problems

| Problem | What to check |
|---|---|
| `g++`, `clang++`, or `cl` is not recognized | Confirm that the compiler is installed. On Windows GCC, check `C:\msys64\ucrt64\bin` in PATH and reopen the terminal. For MSVC, use a Developer Command Prompt or Developer PowerShell. |
| VS Code cannot find a compiler | The C/C++ extension is not a compiler. Install a toolchain and set the compiler path in the workspace configuration. |
| A build task uses a missing path | Edit `.vscode/tasks.json` to point to your compiler, or compile from the integrated terminal. |
| IntelliSense shows errors but compilation works | Check `.vscode/c_cpp_properties.json` for the correct compiler path and language standard. |
| A command works in one terminal but not another | Restart VS Code and terminals after changing PATH, and make sure you are using the right shell or developer prompt. |

Once the compiler and editor are working, continue to [Chapter 1: Introduction to C++](<./Chapter 1/Introduction to C++.md>).
