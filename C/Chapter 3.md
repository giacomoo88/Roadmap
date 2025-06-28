# Chapter 3

<br>

Chapter 3 focuses on formatted input and output in C, primarily using the `printf` and `scanf` functions.
It explains how `printf` can format output using **conversion specifiers**.
Conversion specifier is described as **%±m.pX**
1. *±* = if you put the minus the blank spaces applied will be put at the end
2. *m* = minimum characters to print
3. *p* = precision
4. *X* = what conversion should be applied

The most used ones are:
1. `%d` (integers)
2. `%i` (various number formats depending on the prefix --> 0x hexadecimal, 0 octal)
4. `%f` (floating-point numbers)
5. `%e` (scientific notation)
6. `%g` (or `%f` or `%e`, depending on the numer of digits)

The chapter introduces *formatting tools* like `\n` (newline), `\t` (tab), `\a` (alert bell), `\b` (backspace), `\\` (backslash) and `%%` (percent sign), which help organize output visually. It also explains how to control output alignment and spacing with *field width and precision modifiers*, e.g. `%5d` (minimum width), `%-5d` (left-aligned), and `%.2f` (two decimal places). For input, `scanf` is introduced with similar format specifiers, and the chapter discusses how whitespace and buffer behavior affect input reliability. Practical examples illustrate how to gather and display user data clearly. Lastly, the chapter gives an overview of tokens in C (keywords, constants, identifiers, etc.), laying the groundwork for understanding how formatted I/O fits into full C programs.

<br>

1. Chapter 3 introduces formatted I/O and basic unformatted I/O functions.
2. C provides **formatted I/O** through `printf()` and `scanf()`, via `<stdio.h>`.&#x20;
3. **Unformatted I/O** includes `getchar()` and `putchar()` for single characters.

   ```c
   int ch = getchar();
   putchar(ch);
   ```
4. Basic formatted input:

   ```c
   int age;
   scanf("%d", &age);
   ```
5. Basic formatted output:

   ```c
   printf("Age: %d\n", age);
   ```
6. Format specifiers control type: `%d` for int, `%f` for float, `%c` for char, `%s` for string.
7. Width and precision modifiers format numeric output, e.g., `%6.2f`.
8. `printf("%%")` lets you print a literal `%`.
9. `scanf()` stops reading on whitespace or invalid input and leaves extra characters in the input stream.
10. Input failure occurs if format and user input mismatch—program must handle this.
11. Unformatted `getchar()` reads the next character (including whitespace), return type `int`.
12. Unformatted `putchar()` writes a single character to output.
13. Using `<ctype.h>` functions like `isdigit()`, `isspace()` lets you test character types.
14. I/O operations work through **streams** (`stdin`, `stdout`, `stderr`), abstracting files and devices.
15. `<stdio.h>` functions form the foundation of C’s I/O, and are required in every I/O program.
16. Mixing formatted and unformatted I/O requires care—watch for leftover newline or buffer.
17. Good practice: always check return values of `scanf()` and `getchar()` to detect EOF or errors.
18. Prompting users clearly before `scanf()` improves usability—King recommends avoiding newline in prompts.
19. Exercises reinforce writing and debugging small programs using I/O: character reading, formatted prompts, error checking.
20. Chapter 3 establishes essential tools for user interaction and sets the stage for expressions and control flow in later chapters.
