# AVL Tree

**Definition**: An empty tree is height-balanced. If *T* is a nonempty binary tree with T(L) and T(R) as its left
  and right subtrees respectively, then **T** is *height-balanced* iff

1. T(L) and T(R) are height balanced
2. |h(L) - h(R)| <= 1

where h(L) and h(R) are the heights of T(L) and T(R) respectively.

The *balance factor*, *BF(T)*, of a node *T* in a binary tree is defined to be h(L) - h(R), where h(L) and h(R) are
the height of its left and right subtrees. For any node *T* in an AVL tree, *BF(T)* = [-1,0,1].

Time complexity
<table border="1">
  <tr><td></td><td>Average</td><td>Worst Case</td></tr>
  <tr><td>Space</td><td>O(n)</td><td>O(n)</td></tr>
  <tr><td>Search</td><td>O(log n)</td><td>O(log n)</td></tr>
  <tr><td>Insert</td><td>O(log n)</td><td>O(log n)</td></tr>
  <tr><td>Delete</td><td>O(log n)</td><td>O(log n)</td></tr>
</table>

