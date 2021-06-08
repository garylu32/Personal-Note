# 二分树和分治法

有一个二叉树，n个节点，请问二叉树的高度是多少？  
答案：O(h). 
二叉树最理想的状态是O(logn)  

二叉树在多数情况下的考点是递归。  

## 时间复杂度练习2 
通过O(n)的时间把n的问题，变为了两个n/2的问题，时间复杂度是多少？  Merge sort, quick sort(最好情况）
通过O(1)的时间把n的问题，变为了两个n/2的问题，时间复杂度是多少？  二叉树问题（节点个树 * 每个节点的处理时间）   

## Traverse a Binary Tree
需要背诵：
- preorder 前序遍历
- inorder 中序遍历
- postorder 后序遍历

递归三要素：
1. 递归的定义：递归做了什么？
2. 递归的拆解
3. 递归的出口

## Divide Conquer Algorithm
- Traverse vs. Divide Conquer
They are both Recursion Algorithm.  
Result in parameter vs. Result in return value.  
Top down vs. Bottom down.  

- Merge sort/quick sork
- 90% Binary Tree problems
- DFS (深度优先搜索）面试中经常考察的算法
  - 用递归实现 或者 用非递归实现 
 
**碰到二叉树的问题，想想整棵树在该问题上的结果以及左右儿子在该问题上的结果之间的联系**

