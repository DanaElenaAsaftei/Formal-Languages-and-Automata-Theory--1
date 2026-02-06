# Integer Expression Parser and Evaluator (ANTLR)

This project implements a simple **expression language** for integer arithmetic using **ANTLR**.  
It includes the definition of a grammar, the generated lexer and parser, and a visitor-based evaluator to compute the result of expressions.

The goal of the project is to understand how **formal languages, grammars, parsing, and syntax trees** work in practice, and how to evaluate expressions by traversing the parse tree.

## Description

The project defines a small language of integer expressions (e.g. sums, subtractions, multiplications, parentheses, etc.).  
ANTLR is used to automatically generate:

- A **lexer** (`IntExprLexer`)
- A **parser** (`IntExprParser`)
- Base visitor and interfaces (`IntExprBaseVisitor`, `IntExprVisitor`)

An evaluation visitor (`EvalVisitor`) is implemented to walk the parse tree and compute the final integer result of each expression.

The `Calc.java` class acts as the main entry point to read expressions and evaluate them.

## Concepts Covered

- Formal grammars and language definition  
- Lexical analysis and parsing  
- Parse trees  
- Visitor pattern  
- Expression evaluation  
- Basic compiler/interpreter structure  

## Technologies

- **Language:** Java  
- **Parser Generator:** ANTLR  
- **Paradigm:** Object-Oriented Programming  
- **Topic:** Formal Languages, Parsing, Interpreters  

## How to Run

1. Make sure you have Java installed.
2. Compile the project (example):
   ```bash
   javac *.java
