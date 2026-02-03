---

# Red-Black Tree Implementation in C++

## 📌 Overview

This project provides a simple and clear implementation of a **Red-Black Tree** in C++.
A Red-Black Tree is a self-balancing Binary Search Tree that ensures operations like insertion, deletion, and search run in **O(log n)** time.

This implementation focuses on **insertion** and automatically fixes violations using rotations and recoloring.

---

## ✨ Features

* Red-Black Tree node structure with color property (RED / BLACK)
* Automatic balancing after insertion
* Left and right rotations
* Inorder traversal displaying node values with colors
* Clean and beginner-friendly C++ code

---

## 🧠 Concepts Used

* Binary Search Trees (BST)
* Tree rotations
* Self-balancing trees
* Object-Oriented Programming (OOP) in C++
* Enums and pointers

---

## 🛠️ How to Compile and Run

### Using g++

```bash
g++ red_black_tree.cpp -o red_black_tree
./red_black_tree
```

> Make sure you have a C++ compiler (like GCC) installed.

---

## ▶️ Program Behavior

The program inserts the following values into the Red-Black Tree:

```
1, 2, 3, 4, 5, 6, 7, 8, 9
```

After insertion, it prints an **inorder traversal**, showing each node’s value along with its color:

```
Inorder traversal (with colors):
1(B) 2(R) 3(B) 4(B) 5(B) 6(R) 7(B) 8(R) 9(B)
```

*(Exact colors may vary depending on balancing operations)*

---

## 📂 File Structure

```
red_black_tree.cpp   // Main source file with implementation
README.md            // Project documentation
```

---

## 🚀 Future Improvements

* Add deletion operation
* Add level-order (visual) tree display
* Handle duplicate values
* Improve memory management (destructor)

---

## 👨‍💻 Author

Implemented as an educational demonstration of Red-Black Trees in C++.

---
