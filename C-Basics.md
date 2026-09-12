# C Basics

## 1. Data Types

| Type | Description |
|---|---|
| int | Stores whole numbers. |
| float | Stores decimal numbers. |
| double | Stores decimal numbers with more precision than float. |
| char | Stores one character. |
| bool | Stores true or false. |
| void | Means no value. |

## 2. Format Specifiers

| Specifier | Description |
|---|---|
| %d | Signed integer |
| %u | Unsigned integer |
| %o | Octal integer |
| %x | Hexadecimal (lowercase) |
| %X | Hexadecimal (uppercase) |
| %f | Floating-point number |
| %e | Scientific notation |
| %c | Character |
| %s | String |
| %ld | Long integer |

## 3. Input/Output Functions

- `scanf()` - Reads formatted input.
- `printf()` - Prints formatted output.
- `getchar()` - Reads one character.
- `putchar()` - Prints one character.
- `fgets()` - Reads a line of text.
- `puts()` - Prints a string and adds a new line.

## 4. Escape Sequences

Some common escape sequences are:

- `
` - New line
- `	` - Tab
- `\` - Backslash
- `"` - Double quote
- `'` - Single quote

Example:

```c
printf("Hello\nWorld");
```

## 5. Precision

Precision is used to control the number of digits after the decimal point.

For example:

```c
printf("%.2f", 3.14159);
```

Output:

```text
3.14
```

Here, `.2` means two digits after the decimal point.
