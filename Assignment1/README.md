-  Assignment 1 - Circular Buffer (CE-ESY)   - Mohammad Al-Adwani

- Overview:
This project implements a Circular Buffer in C without using any built-in data structure libraries.
The program demonstrates how data can be stored and retrieved using a fixed-size buffer in a circular manner.

- Objective:
) Understand the concept of Circular Buffer
) Practice manual implementation in C
) Handle edge cases such as overflow and underflow

- How It Works:
1. The user enters a name using standard input.
2. The string "CE-ESY" is appended to the entered name.
3. Each character of the final string is written into the circular buffer.
4. The program reads the data back from the buffer and prints it.
5. At the end, the buffer becomes empty again.

- Buffer Details:
Fixed size buffer using an array
  - Uses three variables:
  `head` → position for reading
    `tail` → position for writing
    `count` → number of elements in the buffer

- Operations Implemented:
Initialization
Write (insert data)
Read (remove data)
Check if buffer is full (Overflow)
Check if buffer is empty (Underflow)

- Notes:
The buffer size is intentionally small to test overflow behavior.
If the buffer is full, the program prints: `Buffer Overflow`
If the buffer is empty, the program prints: `Buffer Underflow`


- How to Run:
You can compile and run the program using any C compiler:

```bash
gcc prog.c -o prog
./prog
```
