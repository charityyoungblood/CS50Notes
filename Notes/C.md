<!-- C Language Syntax --> 

#include <stdio.h>

int main(void)
  {
    printf("hello, world\n");
  }

1. <stdio.h>
  - Refers to "standard input and output" - meaning this file is somehow related to printing (output) and somehow related to keyboards (input)
  
2. #include - Is like saying "Hey computer. Please include standard input and output functionality" 

3. printf - function to print to the console 

4. main - function, the "main" part of your program

5. Loops
  - While: while (true)
  - For: for (int i = 0; i < 50; i++) > for Integer variable i > set to/initialize at 0 > as long as i is less than 50    > increment by 1 > UNTIL i is NOT less than 50

6. Conditions/Conditional Statements
  - if 
  - else if
  - else

7. Creating your programs 
  - By convention, any program you write in C, will end in file type ".c"
  - When running your program, you can do more in your terminal 
  - In order to run your program, you have to run your source code through the compiler, in order to get machine code (binary) 
  - Think of a "compiler" as a translator - it converts instructions (source code) written in a programming language to machine code 
  
8. Clang 
  - compiler for the C language, as well as C++, Objective-C, Objective-C++
  - While in your terminal, to compile the source code file, enter clang + file name to compile your program
    Ex: workspace $ clang hello.c
  