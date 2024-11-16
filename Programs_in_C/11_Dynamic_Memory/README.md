# Dynamic Memory Allocation in C

Dynamic memory allocation allows programs to manage memory during runtime, providing flexibility to create and manipulate data structures dynamically. This folder explores the key concepts and usage of dynamic memory functions like `malloc`, `calloc`, `realloc`, and `free`.

---

## 🚀 **Topics Covered**
1. **`malloc` and `free`**: Allocating and deallocating memory.
2. **`calloc` and `realloc`**: Initializing allocated memory and resizing memory blocks.
3. **Dynamic Arrays**: Creating arrays whose size is determined at runtime.
4. **Structures with Dynamic Memory**: Allocating memory dynamically for structures.

---

## 📂 **Programs Included**
 _____________________________________________________________________________________________
| Program Name                   | Description                                              |
|--------------------------------|----------------------------------------------------------|
| `malloc_free.c`                | Demonstrates the use of `malloc` and `free`.             |
| `calloc_realloc.c`             | Explains `calloc` and resizing with `realloc`.           |
| `dynamic_arrays.c`             | Creating arrays dynamically at runtime.                 |
| `struct_with_dynamic_memory.c` | Using dynamic memory allocation with structures.         |
-----------------------------------------------------------------------------------------------

---

## 🌟 **Quick Tips**
- Always check if memory allocation functions like `malloc` or `calloc` return `NULL` to handle memory allocation failures.
- Free allocated memory using `free` to avoid memory leaks.
- Use `realloc` cautiously to prevent data corruption.

---

## 🛠 **How to Run These Programs**
1. Open a terminal or IDE (like Code::Blocks, Visual Studio Code, or GCC).
2. Compile the program using:
   ```bash
   gcc program_name.c -o program_name
  ```