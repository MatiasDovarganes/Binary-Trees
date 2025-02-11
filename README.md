# Binary-Trees
This file contains implementations of different types of binary trees, including Binary Search Trees (BSTs) and AVL trees. Each tree type is structured to showcase its unique properties and operations.

Binary Search Tree (BST): A BST is a hierarchical data structure where each node follows the rule: left child < parent < right child. This structure allows for efficient searching, insertion, and deletion in O(log n) time on average, though in the worst case (when the tree is unbalanced), operations can degrade to O(n). BSTs are fundamental in computer science for quick lookups and ordered data storage.

AVL Tree: An AVL tree is a self-balancing BST, meaning it automatically maintains a balanced structure to ensure that operations remain O(log n) in all cases. It does this by tracking the height of each node and performing rotations (single or double) whenever the tree becomes unbalanced. This makes AVL trees particularly useful when maintaining consistently fast lookup, insert, and delete times is a priority.
