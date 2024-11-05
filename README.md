# Get Next Line

## Description
**Get Next Line** is a program that reads from a file and returns its contents line by line. This function is commonly used to handle files in a structured way, allowing for processing of one line at a time without loading the entire file into memory.

The program includes both standard and bonus versions, with the bonus version handling multiple file descriptors simultaneously.

## Features
- Reads a line from a file each time it's called.
- Returns `NULL` when it reaches the end of the file or encounters an error.
- Bonus version supports reading from multiple files at the same time.

## Files
### Source Files
- **get_next_line.c** - Contains the core function `get_next_line`, which handles reading and returning a single line from a file.
- **get_next_line_bonus.c** - The bonus version of `get_next_line`, designed to handle multiple file descriptors.
- **get_next_line_utils.c** - Utility functions supporting the main `get_next_line` function.
- **get_next_line_utils_bonus.c** - Utility functions specifically for the bonus version.

### Header Files
- **get_next_line.h** - Header file containing declarations for `get_next_line` and related utilities.
- **get_next_line_bonus.h** - Header file for the bonus version of `get_next_line`, with declarations specific to the multi-file descriptor feature.

## Usage

1. **Compile the Program**

   Use the following command to compile the program:
   ```sh
   gcc -Wall -Wextra -Werror get_next_line.c get_next_line_utils.c -o get_next_line
