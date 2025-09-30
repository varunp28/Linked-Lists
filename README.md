# Linked-Lists  

**Aim:** To study the concept of **Linked List** in C++ and implement creation of a single node and linking multiple nodes.  

**Tools:** GNU g++ compiler for local compilation or any online C++ compiler.  

# Theory  
A **Linked List** is a linear data structure where elements are stored in nodes. Each node contains two parts:  
1. **Data** – stores the actual value.  
2. **Pointer (next)** – stores the address of the next node.  

Unlike arrays, linked lists are dynamic in nature and do not require contiguous memory allocation. They allow efficient insertion and deletion operations but require sequential access for traversal.  

### Types of Linked Lists  
- **Singly Linked List** – each node points to the next node.  
- **Doubly Linked List** – each node has two pointers: one to the next node and one to the previous node.  
- **Circular Linked List** – the last node connects back to the first node.  

# Syntax
```cpp
class Node {
    data_type data;   // stores value
    Node* next;       // pointer to next node
};
```

# **Program 1: Creation of a Single Node**  

### Logic:  
A `Node` class is created with data and pointer.  A single node is created dynamically.  The program demonstrates how values and pointers are stored.  

### Algorithm:  
1. Start  
2. Define a class `Node` with `val` and `next`.  
3. Create a new node with data.  
4. Display the node’s value and pointer.  
5. End  


# **Program 2: Linking Multiple Nodes**  

### Logic:  
Multiple nodes are created dynamically.They are linked together using `next` pointers.  A temporary pointer is used to traverse and print values.  

### Algorithm:  
1. Start  
2. Define a class `Node` with data and pointer.  
3. Create multiple nodes.  
4. Link them using next pointers.  
5. Traverse using a temporary pointer until NULL.  
6. Print node values.  
7. End  


# **Program 3: Head in Linked List**  

### Logic:  
A `Link` class is created with `data` and `next` pointer.  A function is used to add a new node at the beginning of the linked list.  A function is used to traverse and display the list after each insertion.  

### Algorithm:  
1. Start  
2. Define a class `Link` with `data` and `next` pointer.  
3. Create a function to insert a node at head.  
4. Create a function to traverse and print nodes.  
5. Initialize `head` as NULL.  
6. Insert nodes at head one by one.  
7. Display the list after each insertion.  
8. End  

# **Conclusion**  
Linked lists are dynamic data structures that allow flexible memory usage and efficient insertion/deletion. By creating nodes, linking them, and performing head insertions, we can represent sequences without requiring continuous memory like arrays.
