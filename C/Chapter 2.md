# Chapter 2

<br>

Chapter 2 covers the fundamentals of writing simple C programs: it begins with a program that prints a message and explains the compilation and linking steps. Next, it introduces the general form of a C program—preprocessor directives, functions (especially `main`), and statements—and shows how to print strings. It then discusses comments for documenting code. The chapter explores variables and assignment, including declaring `int` and `float` types, initialization, and using variables in expressions. Input is introduced via `scanf`, with an example revisited to read and process user input. The use of named constants via `#define` is shown through a temperature conversion program. Finally, it explains identifiers (names and keywords) and program layout, covering formatting and whitespace rules.

<br>

1. A basic C program starts with a header and a `main` function:

   ```c
   #include <stdio.h>
   int main(void) { ... }
   ```

2. Comments explain your code—use `/* ... */` or `// ...`.
3. Variables must be **declared** before use:

   ```c
   int age;
   ```

4. You can assign values with the assignment operator `=`:

   ```c
   age = 25;
   ```

5. **Initialization** can happen during declaration:

   ```c
   int score = 100;
   ```

6. C has basic types: `int`, `float`, `double`, `char`.
7. Input/output is handled with standard functions like `printf` and `scanf`:

   ```c
   scanf("%d", &age);
   printf("Age: %d\n", age);
   ```

8. Constants are created using `#define`:

   ```c
   #define PI 3.14
   ```

9. Variable names (identifiers) must start with a letter or underscore.
10. Avoid using reserved keywords as variable names (e.g., `int`, `return`).
11. Use meaningful names for readability:
```c
   float averageScore;
   ```

12. Whitespace (indentation, new lines) improves code readability.
13. The `main` function must return an `int`:

   ```c
   return 0;
   ```

14. Use semicolons to terminate each statement.
15. You can group code using blocks `{ ... }`.
16. Always initialize variables to avoid undefined behavior.
17. Avoid common errors like missing semicolons or typos in function names.
18. Compilation turns your code into an executable:
   * `gcc program.c -o program`
19. File structure matters: use `.c` for code and `.h` for declarations.
20. Exercises at the end of the chapter help practice writing complete, basic programs.
