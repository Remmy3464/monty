#####Monty

## Description of Files
<h6>monty.h</h6>
header file for the project, contains the structs used throughout.  

<h6>main.c</h6>
Entry point of the interpreter. Feeds a line at a time to `execute`

<h6>execute.c</h6>
Dispatch the line received from main to the function behind the opcode.

<h6>push_and_pop.c</h6>
Contains `push` and `pop` opcodes

<h6>calculations.c</h6>
contains `add`, `sub`, `mul`, `div` and `mod` opcodes.  

<h6>print_functions.c</h6>
Contains `pint`, `pall`, `pchar` and `pstr` opcodes.

<h6>nopandqueue.c</h6>
Contains `nop`, `stack` and `queue` opcodes.

<h6>move_elements_functions.c</h6>
Contains `swap`, `rotr` and `rotr` opcodes.

<h6>basic_linked_list_functions.c</h6>
The stack is implemented as a doubly linked list. This file contains the functions needed to add elements, remove elements and free a doubly linked list.  

<h6>helpers.c</h6>
This file contains helper functions to deal with a string.

<h6>getline.c</h6>
Our implementation of getline to read a line from a file.

<h5>brainfuck/</h5>
The brainfuck folder contains:
<h6>1000-holberton.bf</h6>
Print `Holberton` in bf.  

<h6>1000-add.bf</h6>
Add 2 single digit numbers whose result is less than 10 in bf.  

<h6>1000-mul.bf</h6>
Multiply 2 single digits numbers whose result is less than 10 in bf.

## Links
[Brainfuck](https://en.wikipedia.org/wiki/Brainfuck)
