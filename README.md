
# printf

Creating a custom printf function.

## Authors
![Github All Contributors](https://img.shields.io/badge/all%20contributors-2-brightgreen)
<br/>
    - [Kevin](https://github.com/userRinks) <br/>


## Description

This project contains a structure of custom `_printf()` functions. It handles a number of specifiers and manipulates strings to print output in a desired format.

### What is `_printf()`?

`printf` takes an argument or series of arguments and displays the output in the respective order.

`printf` takes a number of arguments.
For instance, to identify the start of the string, we use the double quotation mark (") at the front. To identify the end of the string we put another double-quote at the end. `printf` also takes the following arguments:

Symbol                |Meaning   |
|----------------|-------------------------------|
| `\` | escape the next character |
| `\\` | print backslash |
| `"` | start or end of string |
| `\"` | print a double quote |
| `'` | start or end a character constant |
| `\'`| print a single quote |
| `%` | start a format specification |
| `\%` | print a percent sign |

Furthermore, it takes specifiers such as:

Specifier                |Output                        |Examples |
|----------------|-------------------------------|-----------------------------|
| `c` | Character | y |
| `d` or `i` | Signed integer | 1024, -1024 |
| `s` | String of characters | Hello ALx |
| `b` | Binary representation of unsigned integer | 01010110 |
| `u` | Unsigned integer | 1024 |
| `o` | Unsigned octal | 432 |
| `x` | Unsigned hexadecimal integer | 3ca |
| `X` | Unsigned hexadecimal integer (uppercase) | 3CA |
| `S` | String with hex-ascii value replacing special characters | \x0A\x0A |
| `p` | Pointer address | 0x403212 |
| `r` | Reversed string of characters | xLA olleH |
| `R` | ROT13 Translation of string | Uryyb |
