# Cpp-Queue

This repository provides C++ implementations and explanations of a basic Queue data structure. The code includes both array-based and linked-list-based Queue implementations.

## Table of Contents
- [Introduction](#introduction)
- [Array-based Queue](#array-based-queue)
- [Linked List-based Queue](#linked-list-based-queue)
- [Usage](#usage)
- [Contributions](#contributions)

## Introduction

A queue is a linear data structure that follows the First-In-First-Out (FIFO) principle. In a Queue, elements are added at one end (rear) and removed from the other end (front). The primary operations in a Queue are `enqueue` (to add an element) and `dequeue` (to remove an element).

## Array-based Queue

### Algorithm

1. Initialize a fixed-size array to store the elements.
2. Maintain two pointers, `front` (to track the front of the Queue) and `rear` (to track the rear of the Queue).
3. The `enqueue` operation:
   - Increment the `rear` pointer.
   - Add the element at the `rear` position.
4. The `dequeue` operation:
   - Increment the `front` pointer.
   - Remove the element at the `front` position.
5. Additional checks for Queue fullness and emptiness.

### Code
You can find the Array-based Queue code in the `queue.cpp` file.

## Linked List-based Queue

### Algorithm

1. Create a linked list to store the elements of the Queue.
2. Maintain two pointers, `front` (to track the front of the Queue) and `rear` (to track the rear of the Queue).
3. The `enqueue` operation:
   - Create a new node.
   - Update the `rear` pointer to the new node.
4. The `dequeue` operation:
   - Move the `front` pointer to the next node.
   - Remove the node at the previous `front` position.
5. Additional checks for Queue emptiness.

### Code
You can find the Linked List-based Queue code in the `linked list_queue.cpp` file.

## Queue:
![Screenshot 2023-10-25 193711](https://github.com/Arjun378/Cpp-Queue/assets/74441883/3a815ec6-11eb-4e33-8c76-a442346e8d7e)

![Screenshot 2023-10-25 193746](https://github.com/Arjun378/Cpp-Queue/assets/74441883/9ed35448-4a31-43c9-83ba-4549bd750b08)

![Screenshot 2023-10-25 193821](https://github.com/Arjun378/Cpp-Queue/assets/74441883/90e9fc1b-5532-4cb4-b04d-a612538d85cc)

## Linked List Based Queue: 
![Screenshot 2023-10-25 202749](https://github.com/Arjun378/Cpp-Queue/assets/74441883/3a2fee58-1542-4eae-a43b-2de1cb6c67af)

![Screenshot 2023-10-25 202812](https://github.com/Arjun378/Cpp-Queue/assets/74441883/dfa402af-4a75-4a3c-aaf8-04e0c8a54318)

![Screenshot 2023-10-25 202841](https://github.com/Arjun378/Cpp-Queue/assets/74441883/cbff0da1-6ffc-4486-a661-f2cb74d83505)
