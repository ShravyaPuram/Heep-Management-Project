# Heep Management Project
This project implements a custom memory allocator using a heap and a free list to simulate dynamic memory allocation and deallocation. 
It allocates memory blocks by finding a suitable free block in the free list, potentially splitting larger blocks to minimize internal fragmentation. 
The deallocation function merges adjacent free blocks to reduce fragmentation and reinserts the freed block into the list in the correct position. 
The Display_free_list() function visualizes the current state of the free list, showing the size and address of each block.
This project demonstrates key memory management concepts such as block splitting-Accessed the memory using Buddy System Technique, merging, and free list management, providing a foundation for understanding memory allocation in system programming.
