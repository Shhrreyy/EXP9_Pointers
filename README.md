# 🔗 EXP-9: Pointers in C++

## 🎯 Aim

To understand and implement pointer concepts in C++ through basic programs such as arithmetic operations, address referencing, call by value/reference, and memory manipulation.

---

## 📚 Theory

Pointers are variables that store the memory address of another variable.  
They are widely used in dynamic memory management, efficient array handling, and function calling techniques.

- **Declaration**: `int *ptr;`
- **Initialization**: `ptr = &var;`
- **Dereferencing**: Accessing the value stored at the address (`*ptr`).

Key concepts covered:
- Pointer arithmetic
- Address referencing
- Call by value vs call by reference
- Changing values via pointers
- Increment operations on pointers

---

## 🧮 Algorithms / Steps

### 1. **Arithmetic using Pointers (`Arithmetic.cpp`)**
- Declare two integer variables.
- Create pointers pointing to them.
- Perform addition, subtraction, multiplication, division using dereferencing (`*ptr`).

### 2. **Address of Variable (`address_var.cpp`)**
- Declare variables.
- Print their memory addresses using `&var`.
- Store addresses in pointers and display values.

### 3. **Call by Value (`call_by_value.cpp`)**
- Define a function that takes parameters normally (by value).
- Modify values inside the function.
- Show that changes do not affect actual arguments.

### 4. **Call by Reference (`call_by_reference.cpp`)**
- Define a function that accepts parameters as references or pointers.
- Modify values inside the function.
- Show that changes reflect in actual arguments.

### 5. **Changing Memory Location (`changing_memlocation.cpp`)**
- Use a pointer variable.
- Assign it to different variables’ addresses.
- Print and demonstrate how the pointer can point to different memory locations.

### 6. **Increment using Pointers (`increment.cpp`)**
- Declare a variable and a pointer pointing to it.
- Increment the value of the variable using pointer dereferencing (`(*ptr)++`).
- Show updated value.

---

## ✅ Conclusion

This experiment highlights the importance of pointers in C++.  
By practicing these programs, one gains understanding of memory addresses, parameter passing techniques, pointer arithmetic, and how pointers provide flexibility and efficiency in programming.

---

## 🧵 Topics Covered

- Basics of Pointers  
- Pointer Arithmetic  
- Address referencing (`&`) and dereferencing (`*`)  
- Call by Value vs Call by Reference  
- Memory location manipulation  
- Increment operations with pointers  
