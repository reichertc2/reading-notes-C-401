# Code 401 - Advanced Software Development - Python

## Class 15 - Implementation: Trees

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### Tree Implementation Instruction

In the K-ary tree dataset is a tree with more than two node, hence the 'K'. With this dataset, there is a traverse method called Breadth First Traversal. This is to enqueue all the children of a given node in the data set. As an example if Node 1 has children 2 through 5. In this sequence the traverse of breadth will go from left to right or 2,3,4,5.

The first step is to enqueue the original node 1, then dequeue it to discover and enqueue all the children nodes. The process continues with every layer of the tree. In this case, 2 through 4 do not have children and 5  has the child of 6.

The process repeats as node 5 is dequeued, it child 6 is queued. The overall process is a O(n). Total space is O(1).

Easy enough?

### Resources

Trees ([Article](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html))

### Things I want to know more about

* 

Go [Home](index.md)