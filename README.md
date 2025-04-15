# Libft

## 📚 About the Project

**Libft** is a foundational C library developed as part of the 42 coding school curriculum. The purpose of the project is to reimplement a selection of standard C library functions, as well as create custom utility functions and data structures. It is one of the first major projects in the program and serves as a base for future development.

All functions are written from scratch in C, with a strong focus on memory management, pointer arithmetic, and code organization.

---

## 🔧 Features

This library includes:

### Part 1 – Standard Libc Functions  
Reimplementations of standard C functions such as:  
- `ft_strlen`, `ft_strlcpy`, `ft_strncmp`  
- `ft_memset`, `ft_memcpy`, `ft_memmove`, `ft_memcmp`  
- `ft_atoi`, `ft_isalpha`, `ft_isdigit`, `ft_toupper`, `ft_tolower`  
- `ft_strdup`, `ft_calloc`, etc.

### Part 2 – Additional Functions  
Utility functions to enhance string and memory manipulation:  
- `ft_substr`, `ft_strjoin`, `ft_strtrim`  
- `ft_split`, `ft_itoa`  
- `ft_strmapi`, `ft_striteri`, etc.

### Bonus Part – Linked List Utilities  
Implementation of a simple singly linked list and associated functions:  
- `ft_lstnew`, `ft_lstadd_front`, `ft_lstadd_back`  
- `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

---

## 🛠️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/libft.git
   cd libft
   ```

2. Compile the library:
   ```bash
   make
   ```

3. Include it in your C projects:
   ```c
   #include "libft.h"
   ```

4. Link with the compiled library:
   ```bash
   gcc yourfile.c -L. -lft
   ```

---

## 🧠 Skills Demonstrated

- Low-level memory handling in C  
- Implementation of custom versions of standard functions  
- Clean and modular C code organization  
- Understanding of Makefiles and compilation  
- Usage of header files and static libraries  
- Data structures (linked lists)

---

## 📝 Notes

- No external libraries or functions beyond those allowed by the project guidelines were used.  
- All code is compliant with the 42 coding standards.

---

## 📁 Project Status

✅ Completed – fully functional, tested, and used as a foundation for other 42 projects.

---

## 📫 Contact

Feel free to reach out via [GitHub](https://github.com/yourusername) if you have any questions or want to connect.
