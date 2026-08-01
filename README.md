# 🧠 Smart Recipe Organizer | Java + Core Data Structures

A technically robust recipe management system developed in Java, integrating **fundamental data structures** to solve real-world problems like meal planning, ingredient tracking, and cooking task prioritization.

This project demonstrates strong skills in **Data Structure implementation**, **algorithmic thinking**, and **desktop GUI development** — key competencies for a Software Developer role.

---

## 🚀 Project Overview

The Smart Recipe Organizer enables users to manage, search, and organize recipes efficiently using a combination of:
- Binary Search Tree (BST)
- Stack & Queue (Linear & Circular)
- Linked List
- Array & ArrayList
- Recursive Algorithms
- Custom Sorting Implementations

All features are accessible through a **Java Swing GUI** (`JTable`), making it interactive and user-friendly while maintaining underlying algorithmic rigor.

---

## 💼 Why This Matters for Software Development

This project simulates a **real-world application** that demands:
- Efficient data storage and retrieval (BST, Arrays)
- User preference tracking (Stacks, Lists)
- Queue management and scheduling (Meal planning logic)
- Recursive programming and sorting logic (Algorithm design)
- Modular, testable Java code with GUI separation

It showcases my ability to **design systems** that are scalable, performant, and user-centric.

---

## 🧩 Key Functionalities + Data Structures

| Feature | Description | Data Structure | Time Complexities |
|--------|-------------|----------------|-------------------|
| **Recipe CRUD** | Add, view, update, delete recipes | Binary Search Tree (BST) | `O(log n)` avg, `O(n)` worst |
| **Ingredient-Based Search** | Search recipes using ingredients | Array (Linear/Binary Search) | `O(n)` or `O(log n)` |
| **Meal Planning** | Schedule meals efficiently | Circular Queue (Array/Linked List) | `O(1)` enqueue/dequeue |
| **Favorites** | Mark and store favorites dynamically | ArrayList | `O(1)` insert, `O(n)` remove/search |
| **Recently Viewed** | Track last seen recipes | Stack (Linked List) | `O(1)` push/pop |
| **Cooking Queue** | Manage recipe prep queue | Queue (Linked List) | `O(1)` enqueue/dequeue |
| **Custom Sorting** | Sort by time/popularity | Array + Sorting (Bubble, Insertion, Quick Sort) | `O(n log n)` best |
| **Recursive Traversal** | Recursive recipe search & sort | BST traversal, recursive sort | `O(n)` or `O(n log n)` |

---

## 🛠️ Technologies Used

- **Language**: Java (JDK 17+)
- **UI**: Java Swing (`JFrame`, `JButton`, `JTable`, `JScrollPane`)
- **Paradigm**: Object-Oriented Programming
- **Algorithms**: Recursive DFS, Bubble Sort, Insertion Sort, Quick Sort
- **Data Structures**: BST, Stack, Queue, Circular Queue, Linked List, Array, ArrayList

---

## 🖥️ Screenshots

![image](https://github.com/user-attachments/assets/e02b3f67-904e-4477-b5b4-a863cd5ad0b1)
![image](https://github.com/user-attachments/assets/e02b3f67-904e-4477-b5b4-a863cd5ad0b1)


---

## 🧠 Design Highlights

- **Modularized Logic**: Even in a single file, code is separated into logical classes (`Recipe`, `BST`, `GUI`) for readability and maintainability.
- **Real-World Mapping**: Every data structure has been used purposefully based on user-centric scenarios — not arbitrarily.
- **Algorithmic Thinking**: Sorting and searching are implemented manually (not built-in), demonstrating control over time complexity and space efficiency.
- **Ready for Scaling**: This logic can be ported into microservices or REST APIs with minimal restructuring.

---

## 🏁 How to Run

```bash
javac recipe_manager.java
java recipe_manager
