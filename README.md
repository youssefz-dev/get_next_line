# get_next_line

A C function that reads a file line by line using a file descriptor.

## Features

- Read files line by line
- Supports multiple file descriptors
- Handles different buffer sizes
- Uses a static buffer to preserve data between calls

## Usage

Clone the repository and compile:

```bash
git clone <repository-url>
cd get_next_line
cc main.c get_next_line.c get_next_line_utils.c
