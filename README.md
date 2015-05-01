# Lexical-Analyzer-and-parser
This holds 3 file which one is written in Lex and The other two are in C. The code is a simple lexical Analyzer and a parser which is used for check a given codes validity

To execute the code:- Compile the Lex file:- using the command:- lex myscanner.l

then compile the myscanner.c using the command:- gcc myscanner.c lex.yy.c -o myscanner

run the object file created by compiling the C file; by, ./myscanner <config.in
