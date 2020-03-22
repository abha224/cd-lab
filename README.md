# cd-lab
Implementation of the front end phases of a C compiler 

# Phase 1: Scanner for C- language

Used LEX/Flex to implement a lexical analyzer for C language. The lexical
analyzer supports nested comments, and return appropriate error
messages that are as meaningfull as possible, such as comments and strings that
don't end until the end of the file, etc. 

# Phase 2: Parser for C- language

Used YACC/Bison to implement a parser for C language. 

# Phase 3: Semantic checker for C- language

The objective of this assignment is to perform semantic analysis such as type and
scope analysis and declaration processing, and integrate such analyses with the
parser. Add semantic actions to the parser to produce abstract syntax for the C
language.

# Phase 4: Intermediate Code Generation for C- language

In this project we will generate a three address code for C language .We will
test the results by compiling the resulting program, running it, and checking that
it produces the expected output.

