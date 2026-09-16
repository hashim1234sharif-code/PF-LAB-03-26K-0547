# C Programming Basics

## 1. Data Types

| Data Type | Description |
|---|---|
| `int` | Used to store whole numbers, such as 10, 25, or -5. |
| `float` | Used to store decimal numbers with single precision. |
| `double` | Used to store decimal numbers with double precision and greater accuracy than `float`. |
| `char` | Used to store a single character, such as 'A' or 'b'. |
| `bool` | Used to store a Boolean value, either true or false. In C, it is commonly used with `stdbool.h`. |
| `void` | Represents the absence of a value. It is commonly used for functions that do not return a value. |

## 2. Format Specifiers

| Format Specifier | Description |
|---|---|
| `%d` | Used to display or read a signed integer. |
| `%u` | Used to display or read an unsigned integer. |
| `%o` | Used to display an integer in octal format. |
| `%x` | Used to display an integer in hexadecimal format using lowercase letters. |
| `%X` | Used to display an integer in hexadecimal format using uppercase letters. |
| `%f` | Used to display a floating-point value in decimal notation. |
| `%e` | Used to display a floating-point value in scientific notation. |
| `%c` | Used to display or read a single character. |
| `%s` | Used to display or read a string. |
| `%ld` | Used to display or read a long integer. |

## 3. Input/Output Functions

### scanf()

`scanf()` is used to take formatted input from the user.

Example:

`scanf("%d", &age);`

### printf()

`printf()` is used to display formatted output on the screen.

Example:

`printf("Age = %d", age);`

### getchar()

`getchar()` reads a single character from the keyboard.

Example:

`char ch = getchar();`

### putchar()

`putchar()` displays a single character on the screen.

Example:

`putchar(ch);`

### fgets()

`fgets()` is used to read a string or line of text, including spaces.

Example:

`fgets(name, sizeof(name), stdin);`

### puts()

`puts()` displays a string followed by a new line.

Example:

`puts(name);`

## 4. Escape Sequences

Escape sequences are special characters used inside strings and character constants.

| Escape Sequence | Description | Example |
|---|---|---|
| `\n` | New line | `printf("Hello\nWorld");` |
| `\t` | Horizontal tab | `printf("Hello\tWorld");` |
| `\\` | Backslash | `printf("C:\\Program Files");` |
| `\"` | Double quotation mark | `printf("\"Hello\"");` |
| `\'` | Single quotation mark | `printf("\'A\'");` |
| `\b` | Backspace | `printf("Hello\b");` |
| `\r` | Carriage return | `printf("Hello\r");` |

## 5. Precision

Precision specifies the number of digits displayed after the decimal point when printing floating-point values.

For example, `%.2f` displays a floating-point value with two digits after the decimal point.

Example:

`printf("%.2f", 12.3456);`

Output:

`12.35`

Other examples include:

`%.1f` - displays 1 digit after the decimal point.

`%.2f` - displays 2 digits after the decimal point.

`%.3f` - displays 3 digits after the decimal point.

The precision is specified by placing a period followed by the desired number of digits between `%` and `f`.
