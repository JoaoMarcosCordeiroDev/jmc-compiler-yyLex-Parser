## Compiler Lexer - Parser - Abstract Syntax Tree
Development of a compiler for a custom language with its own alphabet, capable of processing source code, detecting syntax/semantic errors, and generating an Abstract Syntax Tree (AST). The repository includes a test suite with valid code files as well as intentional error test cases to verify fault detection and handling mechanisms.

Tech Stack 
Core Language: C / C++

Lexical Analyzer (Lexer): Flex / Lex (lex.l)

Parser Generator: Yacc / Bison (sintaxe.y)

Build Tool: GNU Make (Makefile)

How to Run

Supported Environment: Linux, macOS, or Windows (via WSL/MinGW)
installed in your environment:
1 - gcc or g++

2 - flex

3 - bison (or yacc)

4 - make

Build and Execution
Clone the repository:

Bash
git clone [https://github.com/JoaoMarcosCordeiroDev/jmc-compiler-lex-parser.git](https://github.com/JoaoMarcosCordeiroDev/jmc-compiler-lex-parser.git)
cd jmc-compiler-lex-parser
Compile the project using the Makefile:

Bash
make
Run the test cases:

Valid code execution:

Bash
./compiladorjm teste1correto
Syntax error test case:

Bash
./compiladorjm errosintatico1
Semantic error test case:

Bash
./compiladorjm erroSemantico1
