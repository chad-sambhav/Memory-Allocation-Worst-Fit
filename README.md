# memory-allocation-worst-fit
Memory allocation using Worst Fit algorithm.

# Worst Fit Memory Allocation in C

This repository contains a C implementation of the Worst Fit memory allocation algorithm. The program manages memory allocation, deallocation, and compaction using a linked list structure.

## Description

The program simulates a memory allocation system where memory is allocated to different programs based on their requirements using the Worst Fit strategy. The Worst Fit algorithm allocates the largest available memory block that can accommodate the requested size, aiming to leave large enough free blocks for future allocations.

## Features

- **Memory Allocation**: Allocate memory to programs based on their size requirements.
- **Memory Deallocation**: Free up memory that is no longer in use.
- **Memory Compaction**: Reorganize memory to eliminate fragmentation and consolidate free space.
- **Dynamic Memory Management**: Uses a linked list to manage memory blocks dynamically.

- ## Files Included

- `worst_fit.c`: Implementation of the Worst Fit memory allocation algorithm.

