PROBLEM STATEMENT

Use gdb to read assembly code for C program to find factorial of a number with recursion and demonstrate how parameters are passed using pass by value.

This Assignment is Combined with Assignment 4


Assignment 4 : 

PROBLEM STATEMENT

Explain how pass by reference works, using assembly code generated using g++ -S on a C++ program.

PPL ASSIGNMENT 4
Disassembling Programs with gdb
Create programs in c language for the following:
1. int main with return statement
2. int main return  with integers
3. main with float
4. main with char
5. main with variables, expressions
6. main with array, structures
7. main with pointers
8. main with function- call by value , call by reference

Steps-
1. Write c program
2. Compile using gcc -g filename.c -o filename
3. Run gdb filename
4. In gdb - run the commands
run // run the program
disassemble main // disassemble program
info registers // get values of different registers
5. Draw memory layout diagram for each program
