# Fixed-Size Stack Implementation in Python

A lightweight, memory-efficient implementation of a **Fixed-Size Stack** data structure in Python using a classic pointer-based array approach. 

This structure follows the **LIFO (Last-In, First-Out)** principle, where the last element added is the first one to be removed.

## 🚀 Features

* **Fixed Memory Allocation**: Pre-allocates memory to guarantee strict boundaries.
* **Overflow Protection**: Safeguards against adding elements to a full stack.
* **Underflow Protection**: Safeguards against removing elements from an empty stack.
* **Constant Time Performance**: All core operations run instantly without loops.

## ⏱️ Performance (Big O)

* **Push**: O(1) (Constant time)
* **Pop**: O(1) (Constant time)
* **Space**: O(N) (Where N is the designated max size)

## 📦 Installation & Usage

### 1. The Stack Class
To use this data structure, save the Stack class into a dedicated Python file. The class initializes with a fixed maximum size, creates an internal array using placeholders, and tracks the top index using a structural integer pointer.

### 2. Quick Start Example
To interact with the stack, instantiate the class by passing your desired maximum capacity as an argument. You can then use the push method to add data items sequentially, or the pop method to retrieve and clear the most recently added item from the top of the stack.
