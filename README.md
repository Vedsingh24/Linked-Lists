# Linked-Lists
Linked lists are one of the fundamental linear data structure which find and invaluable use-case in data management. the fundamental building block of a linked list is a the node. There are two types of linked lists in discussion here, those being singly and doubly linked list. One of the key differences between the two is that there is no restriction of direction in the latter. 
The Algortihm for a singly linked list is:
1. Create a class Node which has two attributes: data and next. Next is a pointer to the next node.
2. Create another class which has two attributes: head and tail.
3. addNode() will add a new node to the list:
4. Create a new node.
5. It first checks, whether the head is equal to null which means the list is empty.
6. If the list is empty, both head and tail will point to the newly added node.
7. If the list is not empty, the new node will be added to end of the list such that tail's next will point to the newly added node. This new node will become the new tail of the list.
9. display() will display the nodes present in the list:
10. Define a node current which initially points to the head of the list.
11. Traverse through the list till current points to null.
12. Display each node by making current to point to node next to it in each iteration.

The Algortihm for a doubly linked list is as follows:
1: IF ptr = NULL
  Write OVERFLOW
 Go to Step 9
 [END OF IF] 
2: SET NEW_NODE = ptr
3: SET ptr = ptr -> NEXT
4: SET NEW_NODE -> DATA = VAL
5: SET NEW_NODE -> PREV = NULL
6: SET NEW_NODE -> NEXT = START
7: SET head -> PREV = NEW_NODE
8: SET head = NEW_NODE
9: EXIT
