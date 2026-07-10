# Operating Systems Homework

A collection of homework assignments for an Operating Systems course. Covers shell programming, process management, memory management, caching, and file systems.

## Assignments

1. **Introduction to OS**: Binary/hex conversion, OS concepts
2. **Shell Programming (Part 1)**: Mini-shell implementation, bash scripting, process management
3. **Shell Programming (Part 2)**: Advanced shell features, directory operations
4. **Mini-Shell v3**: Enhanced shell with additional features
5. **Mini-Shell v4 & AWK**: AWK programming, text processing
6. **Text Transformation & Process Management**: xform-c program, problem solving
7. **Caching & Memory**: LRU cache implementation, caching algorithms
8. **Virtual Memory**: Swapping, caching simulation
9. **Threading & Synchronization**: Multi-threaded dictionary search, substring processing
10. **Synchronization**: Process synchronization problems
11. **Synchronization (Part 2)**: Additional sync problems, parentheses matching
12. **Syntax & Parsing**: BNF grammar, syntax checking
13. **File Systems**: Program file implementation, file operations
14. **Virtual File System**: VSFS implementation

## Technologies

- C
- Bash/AWK scripting
- POSIX threads (pthreads)
- Make

## Building

Each assignment contains its own Makefile. Navigate to the assignment directory and run:

```bash
make
```

## Project Structure

```
.
├── 1/              # Assignment 1: OS Introduction
├── 2/              # Assignment 2: Shell Programming
│   ├── bash1/      # Bash exercises
│   └── MSH/        # Mini-shell implementation
├── 3/              # Assignment 3: Advanced Shell
├── 4/              # Assignment 4: Mini-Shell v3
├── 5/              # Assignment 5: AWK & Mini-Shell v4
├── 6/              # Assignment 6: Text Transformation
├── 7/              # Assignment 7: Caching
├── 8/              # Assignment 8: Virtual Memory
│   └── caching_lru/ # LRU cache implementation
├── 9/              # Assignment 9: Threading
│   ├── dict-threads/ # Multi-threaded dictionary
│   └── substr/     # Substring processing
├── 10/             # Assignment 10: Synchronization
├── 11/             # Assignment 11: Sync Problems
├── 12/             # Assignment 12: Syntax & Parsing
├── 13/             # Assignment 13: File Systems
└── 14/             # Assignment 14: Virtual FS
```
