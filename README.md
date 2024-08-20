# rizzler

## Introduction

Lagoon's RIzzler Compiler (LRIC) is a specialized compiler for the Rizzler language, designed to translate your Rizzler code into a lower-level language and compile it into an executable binary. This compiler allows users to write code using unique keywords and syntax specific to the Rizzler language.

## Installation

To install the Lagoon's Rizzler Compiler, simply place the `lric` script in a directory included in your system's PATH, or execute it directly from its location.

## Usage

The Lagoon's Rizzler Compiler can be invoked from the command line using the following syntax:
```bash
./lric <input_file> [-o output_file] [-k] [-v]
```

### Arguments

- `<input_file>`: Specifies the input file containing Rizzler code to be compiled.
- `-o <output_file>`: (Optional) Defines the name of the output binary file. Defaults to `a.out` if not specified.
- `-k`: (Optional) Keeps the intermediary files generated during the compilation process.
- `-v`: (Optional) Prints the version number of the compiler and exits.

### Example

To compile a file named `example.rz` and output it as `program`, run:

```bash
./lric example.rz -o program
```

To keep the intermediary files generated during compilation, use:
```bash
./lric example.rz -o program -k
```

To display the compiler version:
```bash
./lric example.rz -v
```

## Rizzler Language Reference

The Rizzler language uses a unique set of keywords and operators, which are translated during compilation. Below is a table of these keywords and their corresponding translations:

| Rizzler Keyword      | Meaning          | Rizzler Operator | Meaning   |
|----------------------|------------------|------------------|-----------|
| `skibidi`            | Type declaration | `mid`            | Equals |
| `based`              | Entrypoint       | `bet`            | Assignment |
| `gyatt`              | Void type        | `omegamid`       | Not equal |
| `rizz`               | Return statement | `sigma`          | Logical AND |
| `only_in_ohio`       | While loop       | `alpha`          | Logical OR |
| `mewing`             | For loop         | `dank`           | Increment |
| `did_you_pray_today` | Print function   | `lame`           | Decrement |
| `amogus`             | If statement     | `aura`           | Multiplication |
| `rizzing_up`         | Else statement   | `cap`            | Negation |
| `baby_gronk`         | Boolean true     | `periodt`        | Statement terminator |
| `sus`                | Boolean false    | `goated`         | Greater than |
| `valid`              | Break statement  | `bussin`         | Less than |
| `blud`               | Integer 1        | `shook`          | Less than or equal to |
| `dawg`               | Integer 0        | `ohio`           | Greater than or equal to |
| `fr`                 | Block start      | `womp`           | Modulus |
| `nah`                | Block end        | `W`              | Left parenthesis |
|                      |                  | `L`              | Right parenthesis |
|                      |                  | `WL`             | Empty parentheses |

### Code Structure

Rizzler programs follow a familiar structure where the main function is defined using the `based` keyword, and various control structures are supported using the specific Rizzler syntax. 

### Hello, World!

Every good piece of documentantion needs to have a hello world, right? So here it is, Hello World in Rizzler!
```C
skibidi based W WL fr
  did_you_pray_today W "Hello, World!" L periodt
  rizz dawg periodt
nah
```

to be contnued, cant be bothered to write more
