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