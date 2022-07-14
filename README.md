# C - Stacks, Queues - LIFO, FIFO

# The Monty language in C
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project was to create an interpreter for Monty ByteCodes files in C language.

# Synopsis

**Monty byte code files**

Files containing Monty byte codes usually have the  `.m`  extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument and the file can contain blank lines (empty or made of spaces only, and any additional text after the opcode or its required argument is not taken into account:

- Language: **C**, **Monty**

## Project Aim
To create an interpreter for Monty ByteCode files

## Learning Objectives
* Understand what **LIFO** and **FIFO** mean
* Understand what a **stack** is and when to use it
* Understand what a **queue** is and when to use it
* Know the common implementations of stacks and queues
* Know the proper way to use global variables


|Bytecode| Function |
|--|--|
| push | Pushes an element to the stack (Requires an integer argument)|
| pall | Prints all the values on the stack, starting from the top of the stack |
| pint | Prints the value at the top of the stack, followed by a new line |
| pop | Removes the top element of the stack |
| swap | Swaps the top two elements of the stack |
| add | Adds the top two elements of the stack |
| nop | Doesn’t do anything |
| sub | Subtracts the top element of the stack from the second top element of the stack |
| div | Divides the second top element of the stack by the top element of the stack. |
| mul | Multiplies the second top element of the stack with the top element of the stack |
| mod | Computes the rest of the division of the second top element of the stack by the top element of the stack |
| pchar | Prints the char at the top of the stack, followed by a new line |
| pstr | Prints the string starting at the top of the stack, followed by a new line |
| rotl | Rotates the stack to the top |
| rotr | Rotates the stack to the bottom |
| stack | Sets the format of the data to a stack (LIFO). This is the default behavior of the program |
| queue | sets the format of the data to a queue (FIFO) |

## Authors
	* Bello Abayomi A.
	* Adetola Rosemary
