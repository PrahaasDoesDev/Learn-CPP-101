# Learn C++ 101

An evolving, beginner-friendly set of notes and examples for learning C++. The course works from the basics toward modern C++ topics, with explanations of how programs compile and how data is represented in memory.

> **Work in progress:** The full course roadmap is outlined, but only the notes linked under [Available notes](#available-notes) are currently in this repository. New chapters will be added as the course is written.

## Who this course is for

This course is intended for people who are new to C++ or want a guided refresher. You do not need prior programming experience. You will need a computer, a C++ compiler, and a text editor; Visual Studio Code is used in the included workspace configuration.

## Learning goals

By working through the course and practicing the examples, you will learn to:

- Write, compile, run, and troubleshoot simple C++ programs.
- Use variables, built-in types, expressions, and console input/output.
- Understand the relationship between source code, compilation, execution, and memory.
- Build up to functions, arrays, pointers, strings, templates, and object-oriented programming.

## Available notes

Start with these notes and work through them in order:

0. [Chapter 0: Installing and Setting Up Your C++ Environment](<./Chapter 0/Install.md>) - Install a compiler, editor, debugger, and configure VS Code for your operating system.
1. [Introduction to C++](<./Chapter 1/Introduction to C++.md>) - A first program, comments, compiler errors and warnings, console I/O, and an introduction to the execution and memory models.
2. [Variables and Data Types](<./Chapter 2/Variables and Data Types.md>) - How types relate to memory, number systems, initialization, and identifier naming.

The companion [reference index](./References.md) follows the source video's numbering: the introduction and variables notes cover its Chapters 2 and 3.

## Course roadmap

The intended path is grouped into learning stages. Topics without linked notes below are planned course content, not completed lessons.

| Stage | Source chapters | Topics |
|---|---:|---|
| Setup and introduction | 1-2 | Development tools, first program, comments, errors, input/output, compilation, and the execution model |
| Fundamentals | 3-7 | Variables and types, operations, conditional logic, loops, and arrays |
| Memory and text | 8-10 | Pointers, dynamic memory, references, character manipulation, and strings |
| Functions and generic programming | 11-16 | Functions, return values, overloading, lambdas, templates, and concepts |
| Object-oriented programming | 17-19 | Classes, inheritance, and polymorphism |

For the detailed source-video chapter and topic timestamps, see [References.md](./References.md). The reference index links to the [C++ full course video](https://www.youtube.com/watch?v=8jLOx1hD3_o).

## Getting started

> **Before starting the lessons, follow [Chapter 0: Installing and Setting Up Your C++ Environment](<./Chapter 0/Install.md>) to set up a complete C++ environment—including a compiler, editor, debugger, and VS Code configuration—for your operating system.**

### Compile and run the sample

From the repository root, compile `main.cpp` with GCC or Clang:

```sh
g++ -std=c++20 -Wall -Wextra -pedantic main.cpp -o main
./main
```

On Windows, the executable can be named `main.exe`:

```powershell
g++ -std=c++20 -Wall -Wextra -pedantic main.cpp -o main.exe
.\main.exe
```

With MSVC, run this from a Developer Command Prompt or Developer PowerShell:

```powershell
cl /std:c++20 /EHsc /W4 main.cpp
.\main.exe
```

The source currently in `main.cpp` demonstrates binary, decimal, and hexadecimal output, as well as viewing an integer's bytes in memory. The byte order shown by that example depends on the machine's endianness.

## Repository layout

```text
.
|-- Chapter 0/
|   `-- Install.md
|-- Chapter 1/
|   `-- Introduction to C++.md
|-- Chapter 2/
|   `-- Variables and Data Types.md
|-- Images/
|   |-- Chapter 1/
|   `-- Chapter 2/
|-- References.md
|-- main.cpp
`-- .vscode/
```

- `Chapter 0/` contains the environment setup guide; later `Chapter */` folders contain lesson notes.
- `Images/` contains diagrams used by the lessons.
- `References.md` is the timestamped source-video index and full topic outline.
- `main.cpp` is a small example program; it is not a complete course project.
- `.vscode/` contains editor configuration examples.

## How to study

1. Read a lesson and run its examples yourself.
2. Change the code and predict what will happen before compiling it.
3. Use compiler warnings and error messages as learning tools; fix warnings rather than ignoring them.
4. Try small exercises of your own, then revisit the notes when something is unclear.
5. Continue to the next topic only after you can explain the main ideas in your own words.

Code and output can vary between compilers and platforms, especially for type sizes and memory layout. Where a detail is platform-dependent, use the lesson's guidance and verify it on your own system.

## Images

The introduction includes diagrams for the compilation pipeline and stack frames:

- [Compilation: source to instructions](<./Images/Chapter 1/cpp_compile_source_to_instructions.png>)
- [C++ memory model and stack frames](<./Images/Chapter 1/cpp_memory_model_stack_frames.png>)

## Contributing and feedback

This is a course in progress. Corrections, clearer explanations, and suggestions for beginner exercises are welcome. When suggesting an edit, include the chapter and section and, where possible, a small reproducible example.

## License

No license is currently specified. Unless a license is added, all rights remain with the respective content owners; please ask before reusing or redistributing material from this repository.
