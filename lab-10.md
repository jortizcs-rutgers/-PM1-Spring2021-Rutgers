# Lab-10
Linked Lists & Stacks

## Problem 1
Delete Middle Node: Implement an function to delete a node in the middle (i.e., any node but
the first and last node, not necessarily the exact middle) of a singly linked list, given only access to
that node.

```
EXAMPLE
Input:the node c from the linked lista->b->c->d->e->f
Result: nothing is returned, but the new linked list looks like a->b->d->e->f
```

Code: https://onlinegdb.com/rkguDk48O


## Problem 2
Observe the code for a Stack implementation in C++:  https://onlinegdb.com/SkCSmxN8d

a. Change the code using into template form to take any type of data.

b. How would you design a stack which, in addition to push and pop, has a function min which returns the minimum element? Push, pop and min should all operate in O(1) time.  By O(1) time, we mean your solution should not search the whole stack or create a temporary stack in order to find the minimum element.

For part (b), create a new Stack that inherits from the templated Stack Object and implements the algorithm you design to find the min in constant time.



