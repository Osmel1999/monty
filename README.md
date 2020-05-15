0x18. C - Stacks, Queues - LIFO, FIFO
Description
This Holberton School project is a interpreter for a Bytecode, coded in C. Compilation: gcc -Wall -Werror -Wextra -pedantic *.c -o monty Usage: ./monty byte_file.m

The program reads the contents of file "byte_file.m" that contains one instruction per line. It then calls the right function to modify a stack according to the instruction. It prints custom error messages if the code is wrong.

Contents:
File	Description
main.c	entry point of the program
monty.h	main header file
lists.h	header file for the lists functions
funtion_selector.c	function that takes the right function for the given code.
funcs_interp.c	driver functions for the instructions
str_reader.c	string rider and checker
free.c	memory handling functions.
char.c	handler functions for ascii instructions.
