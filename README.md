# Criminal-Record-Management
Creating a java  project to store criminal data using data structures such as Binary Tree, Stack and Linked list
Problem Statement

A database where all the criminal records are stored having the following options to
perform
1. Adding a New Record
2. Displaying all the Records
3. Searching by Id, Year, Category, Location
4. Advance Searching
4.1 Location and Year
4.2 Location and Category
4.3 Category and Year
4.4 Location, Year and Category
5. Updating the imprisonment years left
6. Crime Analysis using a Bar Chart
6.1 Location
6.2 Year
6.3 Category
Explanation
1. Adding a new criminal record from the officer by creating a newnode and adding
it to the record BST according to the file id.
2. Displaying all the records of all the criminals using recursive inorder traversal.
3. Searching by accepting the data from the user and displaying the details if
present (non recursive inorder traversal)
4. Displaying a menu for the particular advanced search option and if the search
elements are present in the record it will display it
5. Updating the imprisonment years left of the prisoner
6. Displaying rate of the crime occurred in the Location, Year, Category and
showing its bar chart with maximum and minimum occurrence

Data Structure Used

BINARY SEARCH TREE
A binary search tree follows some order to arrange the elements. In a Binary search tree,
the value of the left node must be smaller than the parent node, and the value of the
right node must be greater than the parent node. This rule is applied recursively to the
left and right subtrees of the root.
A binary search tree does not store an index of its data elements. Instead, it relies on its
implicit structure (left or right of each node) to keep a record of where each element is.
Time complexity of all BST Operations = O(h). Here, h = Height of binary search
tree.
Instead of traversing every element sequentially until the right one is found, which is
how we work with arrays, we only need to traverse half the tree, then half of half the
tree, then half of half of half the tree and so on. The result is much faster in case of
insertion or searching in comparison to other data structures.


STACK AND LINKED LIST
Use of stack data structure is done in order to perform non recursive inorder
traversal for searching by location,year and category.
Stack helped us to manage the data in the LIFO method.
Use of linked list is done in order to implement binary search tree.
Linked list is a dynamic data structure which makes it easy to add an element to
the binary search tree at the run time and hence there is no need for an initial
size .
