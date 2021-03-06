学习笔记

### 深度优先搜索和广度优先搜索
遍历搜索：在树（图/状态集）中寻找特定结点

每个结点都要访问一次
每个结点仅要访问一次
访问顺序不限：DFS，BFS

### 贪心算法
贪心算法是一种在每一步选择中都采取在当前状态下最好或最优(即最有利)的选择，从而希望导致结果是全局最好或最优的算法。

贪心算法与动态规划的不同在于它对每个子问题的解决方案都做出选择，不能回退。动态规划则会保存以前的运算结果，并根据以前的结果对当前进行选择，有回退功能。
贪心：当下做局部最优判断
回溯：能够回退
动态规划：最优判断+回退
应用：哈夫曼编码、最小生成树

### 二分查找
三个前提条件：

* 目标函数单调性(单调递增或者递减)
* 存在上下界(bounded)
* 能够通过索引访问(index accessible)