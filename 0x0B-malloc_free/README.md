malloc, free
Learning Objectives
What is the difference between automatic and dynamic allocation
What is malloc and free and how to use them
Why and when use malloc
How to use valgrind to check for memory leak
Tasks
Float like a butterfly, sting like a bee
Write a function that creates an array of chars, and initializes it with a specific char.

Prototype: char *create_array(unsigned int size, char c);
Returns NULL if size = 0
Returns a pointer to the array, or NULL if it fails
Solution: 0-create_array.c

$ amonkeyprogrammer@ubuntu:~/0x0a. malloc, free$ cat 0-main.c 
#include "holberton.h"
#include <stdio.h>
#include <stdlib.h>

/**
 * simple_print_buffer - prints buffer in hexa
 * @buffer: the address of memory to print
 * @size: the size of the memory to print
 *
 * Return: Nothing.
 */
void simple_print_buffer(char *buffer, unsigned int size)

