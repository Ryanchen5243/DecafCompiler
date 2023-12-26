# CSE304 (Fall 2023) - Decaf Compiler
## Ryan Chen

This repository houses a collection of essential components designed for the Decaf language, a Java-like language, developed as part of the Compiler Design course (`CSE304`) at Stony Brook University.

### Included Components:
- `decaf_ast.py`: Defines the Abstract Syntax Tree (AST) structures for Decaf.
- `decaf_checker.py`: Implements the Decaf language checker for semantic analysis.
- `decaf_lexer.py`: Lexer responsible for tokenizing input Decaf code.
- `decaf_parser.py`: Parser to generate the AST from the tokenized output.
- `decaf_typecheck.py`: Handles type checking for Decaf language constructs.

### Additional Files:
- `hello_world.decaf`: Sample Decaf code (hello world) for testing purposes.

### Instructions to Run:
To execute the Decaf compiler components, follow these steps:
1. Ensure Python 3 is installed on your system.
2. Clone this repository to your local machine.
3. Open a terminal and navigate to the repository directory.
4. Run the components using Python 3 by executing the respective files:
   - For example, to use the Decaf language checker on a Decaf file named `hello_world.decaf`, run:
     ```
     python3 decaf_checker.py hello_world.decaf
     ```
   - Replace `hello_world.decaf` with the name of your Decaf code file.

This project is a comprehensive effort to build and understand the foundational components of a Decaf compiler, facilitating syntax parsing, semantic analysis, and type checking. Each component plays a crucial role in the compilation process, aiming to ensure the correctness and efficiency of Decaf code translation.

This project was developed as part of the academic curriculum to explore the concepts of compiler design and implementation.
