# CVFS — Custom Virtual File System

## Overview

CVFS (Custom Virtual File System) is a C++ project that simulates core file-system concepts using in-memory data structures.

The project provides a command-line shell for creating, opening, reading, writing, deleting, truncating, and inspecting files.

## Features

- Create regular files with permissions
- Open and close files
- Read and write file data
- List files using `ls`
- Display file information using `stat` and `fstat`
- Delete files using `rm`
- Truncate file contents
- Change read/write offsets using `lseek`
- Display command help and manual information
- In-memory inode and file-table management

## Technologies

- C++
- Structures
- Pointers
- Dynamic memory allocation
- Linked lists
- File descriptors
- In-memory file management
- Command-line processing

## Project Structure

```text
CVFS/
├── README.md
├── .gitignore
└── CVFS/
    └── CVFS.cpp
```

## Supported Commands

| Command | Purpose |
|---|---|
| `ls` | List files |
| `create` | Create a new file |
| `open` | Open an existing file |
| `close` | Close a file |
| `closeall` | Close opened files |
| `read` | Read file contents |
| `write` | Write data to a file |
| `stat` | Display file information |
| `fstat` | Display file information using a file descriptor |
| `truncate` | Remove file data |
| `rm` | Delete a file |
| `lseek` | Change the file offset |
| `man` | Display command information |
| `help` | Display available commands |
| `clear` | Clear the console |
| `exit` | Terminate the virtual file system |

## Compile and Run

Using g++:

```bash
g++ CVFS.cpp -o CVFS
./CVFS
```

On Windows, the executable can be run as:

```text
CVFS.exe
```

Compiled executables are intentionally excluded from Git using `.gitignore`.

## Learning Outcomes

This project helps demonstrate:

- How a virtual file system can be represented using structures
- Inode and file-table concepts
- File descriptors and offsets
- Read/write permissions
- Linked-list based file management
- Dynamic memory allocation
- Command parsing and shell-style interaction

## Author

**Omkar Amrute**

GitHub: [OmkarAmrute1745](https://github.com/OmkarAmrute1745)
