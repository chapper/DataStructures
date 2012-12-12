# B Tree

[wiki entry](http://en.wikipedia.org/wiki/B-tree)

A B-Tree of order *m* is an *m*-way search tree is either empty or satisfies the following:

1. The root node has at least 2 children.
2. All nodes other than the root node and external nodes have at least ceiling(m/2) children.
3. All external nodes are at the same level.

An external node represents a node that can be reaching during a search only if the element being sought is not in the tree.
*Internal nodes* are nodes present in the tree.

A B-tree of order 3 (*m* = 3) is known as a 2-3 tree, as all internal nodes have a degree that is either 2 or 3.
A B-tree of order 4 is known as a 2-3-4 tree, as all internal nodes have a degree that is either 2, 3 or 4.
