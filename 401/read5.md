
**Linked List:** A data structure that contains nodes divided into types ex of them

*Singly :* where each node contains the address of the next node. The address part in a node is also known as a pointer.

**Doubly :** where each node contains the address of the next anmd previous node. The address part in a node is also known as a pointer.

The pointer that holds the address of the initial node is known as a head pointer.

last node in the linked list points to null

Traversal a linked list is not going by length but by using Next untill Next value is NULL if we face NULL we got back with an error (**NullReferenceException** )

*Time Complexity :*Big O(n),, as the worst case senario is to find the node at the end

*Space Complexity* :Big O(1): as there is no afitional space has been used.