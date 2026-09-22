# 🔄 Circular Queue Implementation in C

A menu-driven **C program** implementing a **Circular Queue** data structure using fixed-size arrays with dynamic capacity limits. Features efficient queue wraparound using modulo arithmetic for enqueue, dequeue, and display operations.

---

## ✨ Features

- 📥 **Enqueue Operation**: Adds elements to the queue with dynamic overflow checking.
- 📤 **Dequeue Operation**: Removes the front element while properly handling single-element and empty queue cases[cite: 2].
- 📊 **Display Queue**: Traverses and displays all active elements in circular order[cite: 2].
- 🔄 **Circular Logic**: Uses `(index + 1) % size` logic to reuse freed array slots efficiently[cite: 2].

---

## 💻 Sample Terminal Output

```text
enter size of queue: 3

 1:enqueue
 2:dequeue
 3:display
 4:Exit
enter your choice :1
enter element :10

 1:enqueue
 2:dequeue
 3:display
 4:Exit
enter your choice :3
10
