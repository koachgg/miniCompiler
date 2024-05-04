# Mini C Compiler

This project is a mini C compiler built using Lex and YACC. The compiler supports various C-like operations, including arithmetic operators, logical operators, control structures, and I/O operations. It performs lexical, semantic, and syntax analysis along with immediate code generation (AST and quadruple).

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Input Operations**: Read (e.g., `scanf`)
- **Output Operations**: Printf (e.g., `printf`)
- **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`
- **Control Structures**: `while`, `if-else`
- **Logical Operators**: `&&`, `||`, `!`
- **Boolean Operators**: `<`, `>`, `==`, `!=`
- **Immediate Code Generation**: Abstract Syntax Tree (AST) and quadruples for intermediate code

## Project Structure
- **lex.l**: Lexical analyzer for tokenizing C code
- **yacc.y**: YACC grammar rules for syntax analysis and semantic actions
- **ast.h / ast.c**: Abstract Syntax Tree implementation
- **quadruple.h / quadruple.c**: Quadruple code generation
- **main.c**: Main entry point for the compiler
- **Makefile**: Build instructions for compiling the project

## Installation
To install and build the compiler, you need `lex`, `yacc` (or `flex`, `bison`), and `gcc` installed on your system. Follow these steps:

1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <your-repo-folder>
