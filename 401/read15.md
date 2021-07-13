Hello I want to talk about what i understand about socket.io.
Socket.IO is like Self closing Door , if anyone open it , it will automatically close*  ,,, as it gives a real time communication rather than normal http request as it's always waiting for any request to be happen so it can make a respone without asking it to do .. so for example lets assume that ww have a web page that has a page for users to send feedbacks ,,, and a page for admins to read user feedback the user establishing an event ,, which is already resgistered on the server(it was waiting the client to do this) (just Do it !) ,,, after that the server will accept the user request and will make an interaction by emitting this feedback on an event that was already waiting for this feedback in the admin page.

.on : register an event 
.emit : send an event 

these are the main events there are some additional like those events which responsible in specifying the room or the name space , or those who sends to everyone expect someone that's provided by the library. 
![client.server communication](https://miro.com/app/board/o9J_l6rYdRE=/)

Trees
-Node_  - A Tree node is a component which may contain it’s own values or null , and references to other nodes
_Root_: parent , first one on the tree
_K_ - A:max number of childs any node can have , ex binary search tree is equal to two
-   _Left_  - A reference to one child node, in a binary tree
-   _Right_  - A reference to the other child node, in a binary tree
-   _Edge_  - The edge in a tree is the link between a parent and child node
-   _Leaf_  - A leaf is a node that does not have any children.
-   _Height_  - The height of a tree is the number of edges from the root to the furthest leaf(end of tree probably)
## Traversals
traverse tree , two common ways DFS,BFS
techniques:
-   Pre-order:  `root >> left >> right`
-   In-order:  `left >> root >> right`
-   Post-order:  `left >> right >> root`

*A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the  `root`  are placed to the left, and all values that are larger than the  `root`  are placed to the right.*