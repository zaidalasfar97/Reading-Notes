# What is a Linked List ?
#### A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.
#### There are two types of Linked List - Singly and Doubly. We will be implementing a Singly Linked List in this implementation.

# Terminology: 
##### 1-Linked List - A data structure that contains nodes that links/points to the next node in the list.
##### 2-Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
##### 3-Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
##### 4-Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
##### 5-Next - Each node contains a property called Next. This property contains the reference to the next node.
##### 6- Head - The Head is a reference of type Node to the first node in a linked list.
##### 7- Current - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.


# Traversal Big O
##### The Big O of time for Includes would be O(n). This is because, at its worse case, the node we are looking for will be the very last node in the linked list. n represents the number of nodes in the linked list.

##### The Big O of space for Includes would be O(1). This is because there is no additional space being used than what is already given to us with the linked list input.


# What’s a Linked List, Anyway? 
# Linear data structures
#### If we really want to understand the basics of linked lists, it’s important that we talk about what type of data structure they are.One characteristic of linked lists is that they are linear data structures, which means that there is a sequence and an order to how they are constructed and traversed.


# Memory management
##### The biggest differentiator between arrays and linked lists is the way that they use memory in our machines.



# what even is Big O?

#### Big O is really all over and omnipresent within computer science . Big O Notation is a way of evaluating the performance of an algorithm.