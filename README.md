# Data-structures-in-js

### TREES
* Abstract data type
* General Tree:
  * A tree has a root node.
  * The root node has 0 or more children.
  *Each child node has 0 or more children.
  (each node in the tree can be seen as a subtree)
*Constraints:
  * A child has only one parent and the root node has no parent.
Note: A tree is a special type of graph. A tree is a graph without cycles.
* Operations:
  * tree.addChild(value)
=> child node (new tree)
add child to tree/subtree and return child node (which should be a tree instance)
  * tree.contains(value)
=> true/false
Return true if value is in tree, false if not
  * tree.traverseDepthFirst(callback)
=> undefined
Invoke the callback for every node in a depth-first order
  * tree.traverseBreadthFirst(callback)
=> undefined
Invoke the callback for every node in a breadth-first order
```
function Tree (value) {
  // implement me...
}

Tree.prototype.addChild = function(value) {
  // implement me...
};
// Time complexity:


Tree.prototype.contains = function(value) {
  // implement me...
};
// Time complexity:


Tree.prototype.traverseDepthFirst = function(fn) {
  // implement me...
};
// Time complexity:


Tree.prototype.traverseBreadthFirst = function(fn) {
  // implement me...
};
// Time complexity:
```












feel free to add more
