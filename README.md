# ft_printf Project - README 📚

## Project Overview 🌟

Welcome to the ft_printf Project! This project is a custom implementation of the C library function `printf`, designed to provide formatted output. By creating your own version of `printf`, you'll gain a deeper understanding of variadic functions, string manipulation, and formatted output in C programming.

## Table of Contents 📑

- [Introduction](#introduction)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Supported Format Specifiers](#supported-format-specifiers)
- [Contributing](#contributing)
- [License](#license)

## Introduction 📖

The ft_printf Project involves creating a custom version of `printf` from scratch. This project is ideal for improving your understanding of string manipulation, memory management, and variadic functions in C programming.

## Setup and Installation ⚙️

1. Clone the repository:
   ```sh
   https://github.com/Jakowicki/printf-42.git
Navigate to the project directory:
-
- cd ft_printf

Compile the project:
-
- make

## Usage 🚀
To use the ft_printf function in your own projects, include the header file ft_printf.h and link the compiled library:

Include the header in your source files:
-
- _#include "ft_printf.h"_

Compile your project with ft_printf:
-
- _gcc -o your_program your_program.c -L. -lftprintf_

## Supported Format Specifiers 📝

- %c: Character

- %s: String

- %d, %i: Signed decimal integer

- %u: Unsigned decimal integer

- %x, %X: Hexadecimal integer (lowercase or uppercase)

- %p: Pointer address

- %f: Floating point number


## Contributing 🤝
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request. Make sure to follow the coding standards and include appropriate tests.

## License 📜

This project is licensed under the MIT License. See the LICENSE file for details.
