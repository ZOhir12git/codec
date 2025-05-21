# 🧠 Mini Compiler with Flex & Bison

This is a small educational compiler written in **C** using **Flex** and **Bison**.  
It compiles a minimal programming language with variable declarations, arithmetic expressions, and print statements.

---

## ✨ Features

- Lexical analysis using **Flex**
- Syntax analysis using **Bison**
- Construction of an **Abstract Syntax Tree (AST)**
- Basic **code generation** (prints expressions as C-like output)
- Supports:
  - Integer declarations
  - Variable assignments
  - Arithmetic expressions (`+`)
  - Print statements

---

## 📜 Example Input Code

```c
int x = 5 + 3;
print(x);
----------------------------------------------------------------------------------------------------------------------------------------------------

mini-compiler/
├── lexer.l         # Lexical analyzer (Flex)
├── parser.y        # Syntax parser (Bison)
├── ast.h/.c        # Abstract Syntax Tree structures
├── codegen.c       # Code generation logic
├── main.c          # Entry point
├── Makefile        # Build instructions
└── README.md       # This file
