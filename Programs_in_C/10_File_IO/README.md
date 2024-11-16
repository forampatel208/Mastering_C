# File Handling in C

File handling allows programs to create, read, write, and manage data stored in files. This folder covers basic file operations like opening, closing, reading, writing, and appending data to files.

---

## 🚀 **Topics Covered**
1. **Opening and Closing Files**: Using `fopen` and `fclose` to manage file streams.
2. **Reading and Writing**: Performing basic read and write operations using `fprintf`, `fscanf`, etc.
3. **Copying Files**: Copying content from one file to another.
4. **Appending to Files**: Adding data to an existing file without overwriting.

---

## 📂 **Programs Included**
 _____________________________________________________________________________________________
| Program Name           | Description                                                        |
|------------------------|--------------------------------------------------------------------|
| `file_open_close.c`    | Demonstrates how to open and close files.                          |
| `file_read_write.c`    | Illustrates reading and writing data to files.                     |   
| `file_copy.c`          | Copies content from one file to another.                           |
| `appending_files.c`    | Appends data to an existing file.                                  |
-----------------------------------------------------------------------------------------------

---

## 🌟 **Quick Tips**
- Always check if a file was successfully opened using the return value of `fopen`.
- Use file modes (`r`, `w`, `a`, etc.) carefully to avoid accidental overwrites or data loss.
- Always close a file after operations using `fclose`.

---

## 🛠 **How to Run These Programs**
1. Open a terminal or IDE (like Code::Blocks, Visual Studio Code, or GCC).
2. Compile the program using:
   ```bash
   gcc program_name.c -o program_name
  ```