# C++ Full Course: Reference Notes

> **Video:** [C++ full course on YouTube](https://www.youtube.com/watch?v=8jLOx1hD3_o)  
> **Format:** 19 chapters, 143 sections, 30+ hours  
> Every timestamp below is a clickable deep link that opens the video at that exact moment.

## Table of contents

| # | Chapter | Starts | Sections |
|---|---------|--------|----------|
| 1 | [Setting up the tools](#chapter-1-setting-up-the-tools) | [00:04:32](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=272s) | 11 |
| 2 | [Diving In](#chapter-2-diving-in) | [01:43:01](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=6181s) | 7 |
| 3 | [Variables And Data Types](#chapter-3-variables-and-data-types) | [03:00:47](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=10847s) | 10 |
| 4 | [Operations on Data](#chapter-4-operations-on-data) | [04:46:45](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=17205s) | 12 |
| 5 | [Flow Control](#chapter-5-flow-control) | [07:01:58](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=25318s) | 6 |
| 6 | [Loops](#chapter-6-loops) | [07:53:49](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=28429s) | 4 |
| 7 | [Arrays](#chapter-7-arrays) | [08:47:08](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=31628s) | 5 |
| 8 | [Pointers](#chapter-8-pointers) | [09:53:23](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=35603s) | 10 |
| 9 | [References](#chapter-9-references) | [12:11:04](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=43864s) | 4 |
| 10 | [Character Manipulation And Strings](#chapter-10-character-manipulation-and-strings) | [12:44:29](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=45869s) | 6 |
| 11 | [Functions](#chapter-11-functions) | [14:12:47](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=51167s) | 7 |
| 12 | [Getting Things Out Of Functions](#chapter-12-getting-things-out-of-functions) | [16:03:20](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=57800s) | 3 |
| 13 | [Function Overloading](#chapter-13-function-overloading) | [16:32:35](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=59555s) | 2 |
| 14 | [Lambda Functions](#chapter-14-lambda-functions) | [16:49:00](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=60540s) | 4 |
| 15 | [Function Templates](#chapter-15-function-templates) | [17:40:08](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=63608s) | 5 |
| 16 | [Concepts](#chapter-16-concepts) | [19:04:31](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=68671s) | 6 |
| 17 | [Classes](#chapter-17-classes) | [20:15:40](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=72940s) | 12 |
| 18 | [Inheritance](#chapter-18-inheritance) | [22:52:43](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=82363s) | 13 |
| 19 | [Polymorphism](#chapter-19-polymorphism) | [26:21:03](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=94863s) | 16 |

## Learning path

| Stage | Chapters | What you get |
|-------|----------|--------------|
| **Setup** | 1–2 | Toolchains, VS Code, first program, I/O, execution and memory model |
| **Fundamentals** | 3–7 | Types, operators, control flow, loops, arrays |
| **Memory** | 8–10 | Pointers, dynamic allocation, references, strings |
| **Functions** | 11–16 | Overloading, lambdas, templates, concepts |
| **OOP** | 17–19 | Classes, inheritance, polymorphism |

---

## Chapter 1: Setting up the tools

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`00:04:32`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=272s) | C++ Dev Tools | 6m |
| [`00:11:06`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=666s) | Installing C++ Compilers On Windows | 13m |
| [`00:24:27`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=1467s) | Installing VS Code On Windows | 3m 33s |
| [`00:28:00`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=1680s) | Configuring Visual Studio Code For C++ On Windows | 29m |
| [`00:57:27`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=3447s) | Installing C++ Compilers On Linux | 6m |
| [`01:04:02`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=3842s) | Installing Visual Studio Code On Linux | 3m 38s |
| [`01:07:40`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=4060s) | Configuring Visual Studio Code For C++ On Linux | 15m |
| [`01:22:45`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=4965s) | Installing C++ Compilers On MacOS | 5m |
| [`01:28:07`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=5287s) | Installing Visual Studio Code On MacOS | 2m 09s |
| [`01:30:16`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=5416s) | Configuring Visual Studio Code For C++ On MacOS | 5m |
| [`01:35:37`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=5737s) | Online Compilers | 7m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 2: Diving In

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`01:43:01`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=6181s) | Your First C++ Program | 12m |
| [`01:55:56`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=6956s) | Comments | 6m |
| [`02:01:56`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=7316s) | Errors And Warnings | 11m |
| [`02:13:12`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=7992s) | Statements And Functions | 18m |
| [`02:31:34`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=9094s) | Input Output | 18m |
| [`02:49:57`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=10197s) | C++ Program Execution Model & Memory Model | 6m |
| [`02:56:42`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=10602s) | C++ Core Language VS Standard Library VS STL | 4m 05s |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 3: Variables And Data Types

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`03:00:47`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=10847s) | Variables And Data Types Introduction | 4m 18s |
| [`03:05:05`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=11105s) | Number Systems | 16m |
| [`03:21:52`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=12112s) | Integers | 18m |
| [`03:40:44`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=13244s) | Integer Modifiers | 13m |
| [`03:54:00`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=14040s) | Fractional Numbers | 22m |
| [`04:16:39`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=15399s) | Booleans | 8m |
| [`04:24:49`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=15889s) | Characters And Text | 7m |
| [`04:32:05`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=16325s) | Auto | 6m |
| [`04:38:06`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=16686s) | Assignments | 7m |
| [`04:45:42`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=17142s) | Variables And Data Types Summary | 1m 03s |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 4: Operations on Data

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`04:46:45`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=17205s) | Operations On Data Introduction | 46s |
| [`04:47:31`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=17251s) | Basic Operations | 10m |
| [`04:58:01`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=17881s) | Precedence and Associativity | 14m |
| [`05:12:06`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=18726s) | Prefix And Postfix + & - | 11m |
| [`05:23:22`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=19402s) | Compound Operators | 8m |
| [`05:31:43`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=19903s) | Relational Operators: Comparing Stuff | 9m |
| [`05:40:51`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=20451s) | Logical Operators | 15m |
| [`05:56:09`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=21369s) | Output formatting | 37m |
| [`06:33:26`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=23606s) | Numeric Limits | 7m |
| [`06:41:10`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=24070s) | Math Functions | 13m |
| [`06:54:23`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=24863s) | Weird Integral Types | 5m |
| [`06:59:41`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=25181s) | Operations On Data Summary | 2m 17s |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 5: Flow Control

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`07:01:58`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=25318s) | Flow Control: Conditional Programming Introduction | 1m 32s |
| [`07:03:30`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=25410s) | If Statement | 17m |
| [`07:20:49`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=26449s) | Else If | 7m |
| [`07:28:46`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=26926s) | Switch | 13m |
| [`07:42:44`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=27764s) | Ternary Operator | 9m |
| [`07:52:20`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=28340s) | Flow Control: Conditional Programming Summary | 1m 29s |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 6: Loops

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`07:53:49`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=28429s) | Loops Introduction | 1m 31s |
| [`07:55:20`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=28520s) | For Loop | 30m |
| [`08:25:20`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=30320s) | While Loop | 11m |
| [`08:36:54`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=31014s) | Do While Loop | 10m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 7: Arrays

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`08:47:08`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=31628s) | Arrays Introduction | 1m 37s |
| [`08:48:45`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=31725s) | Declaring And Using Arrays | 27m |
| [`09:15:53`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=33353s) | Size Of An Array | 10m |
| [`09:26:44`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=34004s) | Arrays Of Characters | 20m |
| [`09:46:46`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=35206s) | Bounds Of An Array | 6m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 8: Pointers

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`09:53:23`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=35603s) | Pointers Introduction | 2m 40s |
| [`09:56:03`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=35763s) | Declaring And Using Pointers | 18m |
| [`10:14:48`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=36888s) | Pointer To Char | 12m |
| [`10:27:26`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=37646s) | Program Memory Map | 9m |
| [`10:36:30`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=38190s) | Dynamic Memory Allocation | 29m |
| [`11:05:45`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=39945s) | Dangling Pointers | 18m |
| [`11:24:15`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=41055s) | When New Fails | 13m |
| [`11:38:00`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=41880s) | Null Pointer Safety | 7m |
| [`11:45:18`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=42318s) | Memory Leaks | 10m |
| [`11:55:44`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=42944s) | Dynamic Arrays | 15m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 9: References

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`12:11:04`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=43864s) | References Introduction | 54s |
| [`12:11:58`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=43918s) | Declaring And Using References | 10m |
| [`12:22:28`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=44548s) | Comparing References To Pointers | 14m |
| [`12:37:25`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=45445s) | References And Const | 7m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 10: Character Manipulation And Strings

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`12:44:29`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=45869s) | Character Manipulation And Strings Introduction | 1m 55s |
| [`12:46:24`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=45984s) | Character Manipulation | 23m |
| [`13:09:28`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=47368s) | C-String Manipulation | 32m |
| [`13:41:42`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=49302s) | C-String Concatenation And Copying | 19m |
| [`14:01:19`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=50479s) | Introducing `std::string` | 2m 19s |
| [`14:03:38`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=50618s) | Declaring And Using `std::string` | 9m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 11: Functions

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`14:12:47`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=51167s) | One Definition Rule | 15m |
| [`14:28:25`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=52105s) | First Hand On Functions | 32m |
| [`15:00:50`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=54050s) | Function Declaration & Definition | 14m |
| [`15:15:30`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=54930s) | Functions Across Multiple Files - Compilation Model Revisited | 27m |
| [`15:42:30`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=56550s) | Pass By Value | 8m |
| [`15:50:30`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=57030s) | Pass By Pointer | 7m |
| [`15:57:46`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=57466s) | Pass By Reference | 5m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 12: Getting Things Out Of Functions

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`16:03:20`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=57800s) | Getting Things Out Of Functions Introduction | 38s |
| [`16:03:58`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=57838s) | Input And Output Parameters | 13m |
| [`16:17:54`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=58674s) | Returning From Functions | 14m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 13: Function Overloading

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`16:32:35`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=59555s) | Function Overloading Introduction | 1m 42s |
| [`16:34:17`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=59657s) | Overloading With Different Parameters | 14m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 14: Lambda Functions

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`16:49:00`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=60540s) | Lambda Functions Introduction | 38s |
| [`16:49:38`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=60578s) | Declaring And Using Lambda Functions | 30m |
| [`17:20:25`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=62425s) | Capture Lists | 13m |
| [`17:34:24`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=63264s) | Capture All In Context | 5m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 15: Function Templates

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`17:40:08`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=63608s) | Function Templates Introduction | 1m 37s |
| [`17:41:45`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=63705s) | Trying Out Function Templates | 38m |
| [`18:19:52`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=65992s) | Template Type Deduction And Explicit Arguments | 15m |
| [`18:35:47`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=66947s) | Template Type Parameters By Reference | 13m |
| [`18:48:55`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=67735s) | Template Specialization | 15m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 16: Concepts

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`19:04:31`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=68671s) | Concepts Introduction | 2m 16s |
| [`19:06:47`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=68807s) | Concepts | 18m |
| [`19:25:32`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=69932s) | Concepts: Building Your Own | 17m |
| [`19:42:45`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=70965s) | Requires Clause: Zooming In | 17m |
| [`19:59:53`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=71993s) | Logical Combinations Of Concepts | 9m |
| [`20:09:39`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=72579s) | Concepts And Auto | 6m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 17: Classes

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`20:15:40`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=72940s) | Classes Introduction | 53s |
| [`20:16:33`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=72993s) | Your First C++ Class | 21m |
| [`20:38:03`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=74283s) | Constructors | 15m |
| [`20:53:35`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=75215s) | Defaulted Constructors | 6m |
| [`20:59:42`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=75582s) | Setters And Getters | 10m |
| [`21:10:06`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=76206s) | Class Across Multiple Files | 20m |
| [`21:30:49`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=77449s) | Managing Class Objects Through Pointers | 11m |
| [`21:42:48`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=78168s) | Destructors | 22m |
| [`22:05:44`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=79544s) | Constructor & Destructor Call Order | 5m |
| [`22:11:03`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=79863s) | The This Pointer | 22m |
| [`22:33:33`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=81213s) | Struct | 9m |
| [`22:42:37`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=81757s) | Size Of Class Objects | 10m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 18: Inheritance

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`22:52:43`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=82363s) | Inheritance Introduction | 3m 16s |
| [`22:55:59`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=82559s) | Your First Try On Inheritance | 25m |
| [`23:21:10`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=84070s) | Protected Members | 10m |
| [`23:32:06`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=84726s) | Base Class Access Specifiers: Zooming In | 4m 43s |
| [`23:36:49`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=85009s) | Base Class Access Specifiers: A Demo | 30m |
| [`24:07:42`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=86862s) | Closing In On Private Inheritance | 18m |
| [`24:26:36`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=87996s) | Resurrecting Members Back In Scope | 20m |
| [`24:46:59`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=89219s) | Default Arg Constructors With Inheritance | 10m |
| [`24:57:37`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=89857s) | Custom Constructors With Inheritance | 29m |
| [`25:26:56`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=91616s) | Copy Constructors With Inheritance | 24m |
| [`25:51:53`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=93113s) | Inheriting Base Constructors | 14m |
| [`26:06:00`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=93960s) | Inheritance With Destructors | 6m |
| [`26:12:20`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=94340s) | Reused Symbols In Inheritance | 8m |

[↑ Back to top](#c-full-course-reference-notes)

## Chapter 19: Polymorphism

| Timestamp | Topic | Length |
|-----------|-------|--------|
| [`26:21:03`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=94863s) | Polymorphism Introduction | 5m |
| [`26:26:54`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=95214s) | Static Binding With Inheritance | 28m |
| [`26:55:24`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=96924s) | Polymorphism (Dynamic Binding) With Virtual Functions | 19m |
| [`27:14:31`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=98071s) | Size Of Polymorphic Objects And Slicing | 12m |
| [`27:26:37`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=98797s) | Polymorphic Objects Stored In Collections | 19m |
| [`27:45:42`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=99942s) | Override | 7m |
| [`27:52:45`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=100365s) | Overloading, Overriding And Hiding | 14m |
| [`28:07:35`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=101255s) | Inheritance And Polymorphism At Different Levels | 25m |
| [`28:33:03`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=102783s) | Inheritance And Polymorphism With Static Members | 16m |
| [`28:49:13`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=103753s) | Final | 18m |
| [`29:07:42`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=104862s) | Virtual Functions With Default Arguments | 15m |
| [`29:23:18`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=105798s) | Virtual Destructors | 12m |
| [`29:35:38`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=106538s) | `dynamic_cast<>()` | 32m |
| [`30:08:17`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=108497s) | Don't Call Virtual (Polymorphic) Functions From Constructors & Destructors | 16m |
| [`30:24:45`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=109485s) | Pure Virtual Functions And Abstract Classes | 18m |
| [`30:43:37`](https://www.youtube.com/watch?v=8jLOx1hD3_o&t=110617s) | Abstract Classes As Interfaces | — |

[↑ Back to top](#c-full-course-reference-notes)

---

*Lengths are computed from the gap to the next timestamp, so the final section has none listed.*