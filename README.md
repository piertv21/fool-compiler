## A simple compiler for the F.O.O.L. language, based on the ANTLR parser generator.

The compiler, overall, consists of:
- Lexer
- Parser
- Syntax Tree Generator (check lexical and syntax errors)
- Abstract Syntax Tree Generator
- Enriched AST Generator (check symbol table errors)
- Type checker (type checking errors)
- Front-end errors checking
- Code Generator
- Assembler
- Stack Virtual Machine (for code execution and result printing)

Supports the declaration of int and bool variables and functions, and some basic operands, such as:
- +, -, *, /
- !, ||, &&
- <=, >=
