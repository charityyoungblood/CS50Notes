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
  - While in your terminal, to compile the source code file, enter clang filename.c to compile your program
    Ex: workspace $ clang hello.c
  - Once Clang compiles the source code > the a.out file is created which holds the machine code 
  - To output a custom file name from the clang compiler, enter clang -o newFileName oldFileName.c
  
9. Steps to run your program (in your terminal)
  - enter clang filename.c
  - ./filename-created.out (Ex: ./a.out)
  
10. C syntax 

   #include <stdio.h>
   
    int main(void) {
      string s = get_string("Name: ");
      printf("hello, %s\n", s);
    }
              
  - The above lines are read as: create a variable called "s" with type "string", set that variable to the function "get_string", with an argument of "Name: ". Print to the console the string "hello, with the placeholder for a string (%s) and in that placeholder place the value of variable s" 
  - In C, you have to specify the data type in the function or variable declaration 
  - 
  
11. CS50 IDE - use terminal command <make filename> will compile for you (filename WITHOUT the .c extension)
  *** REMEMBER to #include <cs50.h> *** this will include the cs50 library 
  
























