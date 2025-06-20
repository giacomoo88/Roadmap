# Chapter 1

<br>

Chapter 1 introduces the C language, created in the 1970s at Bell Labs, highlighting its evolution through standards like C89 and C99. It emphasizes C’s strengths: efficiency, portability, and suitability for system-level programming. The chapter presents the structure of a basic C program, including the use of preprocessor directives like `#include`. It explains that every program must have a `main` function and may also use standard library functions. The compilation process—from editing to execution—is outlined step by step. Basic elements such as comments, variables, assignment, and simple I/O using `printf` and `scanf` are introduced. The chapter aims to gently ease the reader into C programming before diving into more formal and detailed aspects in later chapters.

<br>

1. C was created in the early 1970s by Dennis Ritchie at Bell Labs.
2. It’s a general-purpose, procedural, compiled language used in systems programming and beyond. ([reddit.com][1], [raviroza.com][2])
3. Modern C standards (C99, C11) add features over traditional C (C89/C90) like new types, better memory support, and cleaner syntax. ([raviroza.com][2])
4. A program is written as plain-text source files: `.c` for code and `.h` for headers. ([oreilly.com][3])
5. Programs consist of tokens: keywords (e.g., `int`, `if`), constants (`42`, `'A'`), strings (`"Hello"`), identifiers (variable names). ([raviroza.com][2])
6. C operators include arithmetic (`+ - * / %`), relational (`<`, `==`), logical (`&&`, `||`, `!`), bitwise (`&`, `|`, `^`, `>>`), assignment, increment/decrement, conditional, comma operator. ([raviroza.com][2])
7. Operator precedence dictates evaluation order in expressions. ([raviroza.com][2])
8. Variables must be declared with a type before use.
9. Fundamental data types include `int`, `char`, `float`, `double`; there are also derived types like arrays, structs, unions, pointers, and enums. ([raviroza.com][2])
10. C is strongly typed, though some type conversions can happen implicitly.
11. Type casting (`(int) x`) converts between types when needed. ([raviroza.com][2])
12. Preprocessor directives (`#include`, `#define`) are handled before compilation. ([raviroza.com][2])
13. `#include <stdio.h>` brings in declarations for standard I/O functions like `printf`.
14. Header files separate declarations (in `.h`) from definitions (in `.c`), enabling modular design. ([apeth.com][4])
15. Functions (like `main`) are foundational; `main` is mandatory as the program entry point.&#x20;
16. Every function returns a type (e.g., `int main(void)`) and may take parameters.&#x20;
17. A C program is compiled in phases: preprocessing, compiling, assembling, and linking.
18. Code clarity is critical—King advocates writing code that compiles without warnings.
19. Programs should be broken into logical modules across files, promoting maintainability. ([apeth.com][4], [reddit.com][5])
20. Chapter 1 concludes with Q\&A exercises to reinforce basics and ensure understanding.
