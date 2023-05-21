# lab5
# BST Class
The BST class is a generic class that represents the binary search tree. It has the following main components:

Node class: A private inner class representing a node in the binary search tree. Each node contains a key-value pair, as well as references to its left and right child nodes.

root instance variable: A reference to the root node of the binary search tree.

put(K key, V value) method: Inserts a key-value pair into the binary search tree. It uses a recursive helper method, put(Node node, K key, V val), to traverse the tree and find the appropriate position for insertion.

get(K key) method: Retrieves the value associated with a given key in the binary search tree. It uses a recursive helper method, get(Node node, K key), to traverse the tree and find the node with the specified key.

delete(K key) method: Deletes a key-value pair from the binary search tree. It uses a recursive helper method, delete(Node node, K key), to traverse the tree and find the node to delete. The method handles three cases: deleting a node with no children, deleting a node with one child, and deleting a node with two children.

findMin(Node node) method: Finds the minimum key in the binary search tree rooted at the given node. It iteratively traverses the left subtree until the left child is null and returns the node.

iterator() method: Returns an iterator for the binary search tree that iterates through the keys in ascending order. It performs an inorder traversal of the tree, using a recursive helper method, inorderTraversal(Node node, List<K> keys), to add the keys to a list.

size() method: Returns the size (number of nodes) of the binary search tree. It uses a recursive helper method, size(Node node), to calculate the size by recursively counting the nodes.
  
  # Main
  The Main class contains a main method that demonstrates the usage of the BST class. It creates an instance of the BST class with key type Integer and value type String. It then performs various operations on the BST, such as inserting key-value pairs, retrieving values, deleting keys, getting the size, and iterating through the keys in ascending order.

The output of the main method demonstrates the functionality of the BST. It retrieves the value associated with a specific key, deletes a key, prints the size of the tree, and prints the keys in ascending order.
