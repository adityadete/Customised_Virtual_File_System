# Customised_Virtual_File_System
🗂️ Custom Virtual File System (CVFS)
A single-file C++ project that simulates a Linux-like Virtual File System with a custom interactive shell.

✨ Highlights

Simulates Linux-style file operations

Implements creat, read, write, lseek, stat, unlink

Demonstrates SuperBlock, Inode Table (DILB), and UFDT

Dynamic memory-based file storage

Shows practical OS-level file system concepts

🛠️ Tech Stack

Language: C++

Concepts: Operating Systems, File Systems

Compiler: g++

🚀 Build & Run
# Compile
g++ cvfs.cpp -o cvfs

# Run
./cvfs
💡 Quick Example
CVFS > creat Demo.txt 3
CVFS > write 0
<enter some data>
CVFS > read 0 10
CVFS > ls
CVFS > stat Demo.txt
CVFS > exit
📁 Repository Layout
cvfs.cpp      # Core implementation
README.md     # Documentation
.gitignore    # Ignored files
👤 Author

Aditya Mahadev Dete
