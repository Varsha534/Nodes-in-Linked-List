# Nodes-in-Linked-List

# Linked List 
A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers as shown in the below image:

![image](https://user-images.githubusercontent.com/125336949/234397314-54540a6a-1e37-448f-b59b-666673f7a759.png)

A Linked List is a linear data structure which looks like a chain of nodes, where each node is a different element. Unlike Arrays, Linked List elements are not stored at a contiguous location. It is basically chains of nodes, each node contains information such as data and a pointer to the next node in the chain. In the linked list there is a head pointer, which points to the first element of the linked list, and if the list is empty then it simply points to null or nothing.

# Types of Linked Lists:
- Simple Linked List – In this type of linked list, one can move or traverse the linked list in only one direction. where the next pointer of each node points to other nodes but the next pointer of the last node points to NULL. It is also called “Singly Linked List”.
- Doubly Linked List – In this type of linked list, one can move or traverse the linked list in both directions (Forward and Backward)
- Circular Linked List – In this type of linked list, the last node of the linked list contains the link of the first/head node of the linked list in its next pointer.
- Doubly Circular Linked List – A Doubly Circular linked list or a circular two-way linked list is a more complex type of linked list that contains a pointer to the next as well as the previous node in the sequence. The difference between the doubly linked and circular doubly list is the same as that between a singly linked list and a circular linked list. The circular doubly linked list does not contain null in the previous field of the first node.
- Header Linked List – A header linked list is a special type of linked list that contains a header node at the beginning of the list. 

# Basic operations on Linked Lists:
- Deletion
- Insertion
- Search
- Display

# Representation of Singly Linked Lists: 
A linked list is represented by a pointer to the first node of the linked list. The first node is called the head of the linked list. If the linked list is empty,  then the value of the head points to NULL. 

Each node in a list consists of at least two parts: 

- A Data Item (we can store integers, strings, or any type of data).
- Pointer (Or Reference) to the next node (connects one node to another) or An address of another node

In C, we can represent a node using structures. Below is an example of a linked list node with integer data. 
In Java or C#, LinkedList can be represented as a class and a Node as a separate class. The LinkedList class contains a reference of Node class type. 
