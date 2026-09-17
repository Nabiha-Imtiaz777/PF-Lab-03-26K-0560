# C Programming Basics

## 1. Data Types
| Data Type | Description | Size (bytes) |
| :--- | :--- | :--- |
| `int` | Integers are whole numbers with no decimal values. | at least 2, usually 4 |
| `float` | Holds real numbers with a precision of 6 digits. | 4 |
| `double` | Holds real numbers with a precision of 14 digits. | 8 |
| `char` | Allows a variable to store only one character. | 1 |
| `bool` | Holds one of two values: true (1) or false (0). | 1 |
| `void` | Signifies the absence of a value. | 0 |

## 2. Format Specifiers
| Format Specifier | Description |
| :--- | :--- |
| `%d` | Prints signed integer values. |
| `%u` | Prints unsigned integer values. |
| `%o` | Prints octal unsigned integers (starts with 0). |
| `%x` | Prints hexadecimal unsigned integers (lowercase). |
| `%X` | Prints hexadecimal unsigned integers (uppercase). |
| `%f` | Prints decimal floating-point values. |
| `%e` | Prints floating-point numbers in scientific notation. |
| `%c` | Prints unsigned characters. |
| `%s` | Prints strings. |
| `%ld` | Prints long-signed integer values. |

## 3. Input/Output Functions
* **`scanf()`:** Formatted input function that reads input from `stdin` using format specifiers and variable addresses (`&variable`).
* **`printf()`:** Formatted output function that writes output to `stdout` using format specifiers and arguments.
* **`getchar()`:** Unformatted character input function that reads a single character from keyboard input.
* **`putchar()`:** Unformatted character output function that displays a single character on the console.
* **`fgets()`:** Safe string input function that reads a line of text (including spaces) into a character array.
* **`puts()`:** Unformatted string output function that prints a string to `stdout` and automatically appends a newline (`\n`).

## 4. Escape Sequences
* `\n`: Inserts a newline in the text.
* `\t`: Inserts a horizontal tab in the text.
* `\b`: Inserts a backspace in the text.
* `\"`: Inserts a double quote character.
* `\\`: Inserts a backslash character.

## 5. Precision
Precision for floating-point values (`float` and `double`) is specified in the format specifier by adding a period (`.`) followed by a positive integer representing the number of desired decimal places (e.g., `%.2f` for 2 decimal places or `%.14lf` for 14 decimal places). By default, C prints 6 digits after the decimal point if no precision is specified.
