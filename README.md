# Assignment-6-Medians-and-Order-Statistics-Elementary-Data-Structures
Project Overview

This project implements and analyzes important concepts in algorithms and data structures using Python. The assignment is divided into two parts:

Part 1: Selection Algorithms

Deterministic Selection Algorithm (Median of Medians)
Randomized Selection Algorithm (Randomized Quickselect)
Performance comparison and runtime analysis

Part 2: Elementary Data Structures

Custom Array implementation
Stack implementation
Queue implementation
Singly Linked List implementation

The objective of this project is to understand how different algorithms and data structures work, analyze their efficiency, and evaluate their practical applications.
Technologies Used
Python 3
Google Colab
Part 1: Selection Algorithms
1. Median of Medians Algorithm

The Median of Medians algorithm is a deterministic selection method used to find the kth smallest element in an array. The algorithm divides the array into smaller groups, calculates medians, and uses the median value as a pivot for partitioning.

Characteristics:
Worst-case time complexity: O(n)
Provides guaranteed linear performance
Suitable for applications requiring predictable execution time
2. Randomized Quickselect Algorithm

Randomized Quickselect finds the kth smallest element by selecting a random pivot and partitioning the array based on the pivot value.

Characteristics:
Expected time complexity: O(n)
Faster in most practical cases
Worst-case complexity: O(n²)
Performance Testing

Both algorithms were tested using different input sizes.

Input Size	Median of Medians	Randomized Quickselect
100	0.000093 seconds	0.000037 seconds
500	0.000351 seconds	0.000268 seconds
1000	0.000710 seconds	0.000194 seconds
5000	0.003457 seconds	0.000912 seconds
Part 2: Data Structures Implementation
Array

A custom array implementation was created with operations including:

Insert
Delete
Access
Display

Arrays provide fast element access with O(1) complexity but require shifting elements during insertion or deletion.

Stack

A stack was implemented using an array structure.

Operations:

Push
Pop
Peek

Stacks follow the Last-In-First-Out (LIFO) principle.

Example output:

Stack: [100, 200, 300]

Removed: 300

Applications:

Function calls
Undo operations
Expression evaluation
Queue

A queue implementation was created with enqueue and dequeue operations.

Queues follow the First-In-First-Out (FIFO) principle.

Example output:

Queue:
['Task A', 'Task B']

Removed:
Task A

Applications:

Scheduling systems
Printer queues
Network processing
Linked List

A singly linked list was implemented with:

Node creation
Insertion
Deletion
Traversal

Example output:

Before deletion:

['Data Structures', 'Algorithms', 'Python']

After deletion:

['Data Structures', 'Python']

Applications:

Dynamic memory management
Data organization systems
Applications requiring frequent modifications
Summary of Findings

The implementation successfully demonstrated both selection algorithms and elementary data structures.

The Median of Medians algorithm correctly identified the kth smallest element while providing guaranteed O(n) worst-case performance. The Randomized Quickselect algorithm produced the same correct results and achieved faster execution times during experimental testing. The performance comparison showed that Quickselect was more efficient for the tested input sizes because of reduced overhead and effective random pivot selection.

However, Median of Medians provides better reliability for applications where predictable runtime is important. The experimental results showed that both algorithms have different advantages depending on the application requirements.

The data structure implementations demonstrated the behavior and performance of arrays, stacks, queues, and linked lists. Arrays provided efficient element access, stacks supported LIFO operations, queues demonstrated FIFO processing, and linked lists provided flexible insertion and deletion capabilities.

Overall, the project improved understanding of algorithm design, time complexity analysis, and selecting appropriate data structures based on performance requirements and practical use cases.

Complexity Summary
Data Structure / Algorithm	Operation	Complexity
Median of Medians	Selection	O(n)
Randomized Quickselect	Expected Selection	O(n)
Array Access	Retrieve Element	O(1)
Array Insert/Delete	Modify Elements	O(n)
Stack Push/Pop	Insert/Delete	O(1)
Queue Enqueue	Insert	O(1)
Queue Dequeue	Remove	O(n)
Linked List Insert	Add Node	O(1)
Linked List Search/Delete	Find Node	O(n)
