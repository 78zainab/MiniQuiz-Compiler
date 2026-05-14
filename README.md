
# Mini Compiler – Quiz Score Calculator

A Mini Compiler for Quiz Score Calculation built in C using Flex and Bison.

It implements major compiler phases:
- Lexical Analysis
- Syntax Analysis
- Symbol Table Management
- Three-Address Code (TAC) Generation

## Files
- quiz.c → main compiler source code
- quiz → compiled binary
- quiz.txt → input / test cases

## Build (example)
flex lexer.l
bison -d parser.y
gcc lex.yy.c parser.tab.c quiz.c -o quiz -lfl

>>>>>>> 3005d1f (Initial commit: mini compiler with quiz score calculator, included: quiz.txt, quiz.c, quiz, README.md)
