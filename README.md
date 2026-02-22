# Customised Virtual File System (CVFS)

![Language](https://img.shields.io/badge/Language-C%2B%2B-blue)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20macOS-lightgrey)
![License](https://img.shields.io/badge/License-MIT-yellow)

A single-file C++ project that simulates a Linux-like virtual file system with its own interactive shell.

---

## ✨ Highlights

- Simulated Linux-like file system operations with a custom shell interface.
- Implemented key system calls: `creat`, `read`, `write`, `lseek`, `stat`, `unlink`.
- Demonstrates low-level OS concepts such as superblock, inode table (DILB), and user file descriptor table (UFDT).
- Dynamic memory-based file storage (non-persistent).
- Hands-on implementation of file descriptor and offset management.

---

## 🚀 Build & Run

```bash
# Compile
g++ cvfs.cpp -o cvfs

# Run
./cvfs

# Example
CVFS > creat Demo.txt 3
CVFS > write 0
<enter some data>
CVFS > read 0 10
CVFS > ls
CVFS > stat Demo.txt
CVFS > exit

👤 Author

Aditya Mahadev Dete
