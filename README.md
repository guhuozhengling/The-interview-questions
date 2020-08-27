# The-interview-questions

高频算法面试题总结，题目来源于力扣会员内容，如侵犯您的权力，请联系我删除。

内容为以下范围内的典型题目我自己的思路讲解以及c++解法，如需方便阅读的pdf版本可以联系我获取：

1.经典题目（10道）

经典的互联网名企面试题目

2.数组（10道）

数组是最基本的数据结构之一，用于按顺序存储元素的集合。有很多面试中的算法问题，并不需要复杂的数据结构支撑，用数组就能考察出很多方面。经典的排序，二分搜索等问题，就是在数组这种最基础的结构中处理的。

3.字符串（5道）

字符串是一个由 unicode 字符构成的数组，因此它和数组是比较相似的。你可以执行几乎所有我们在数组中使用的操作。String 作为最常见的编程语言类型之一，也是算法面试的考察重点之一。

4.链表 （5道）

与数组相似，链表也是一种线性数据结构。它通过引用字段将所有分离的元素链接在一起。链表的出现在某种程度上是为了避免数组的一大缺陷，即分配数组的时候需要开辟一段连续的内存空间，但链表也牺牲了数组的一些优点，链表不能通过下标进行快速查询。所以在考虑是否需要运用链表的时候，务必要想清楚你的算法是否需要经常随机访问元素。

5.堆与栈（4道）

“堆、栈、队列” 是几个非常容易混淆的数据结构，堆（Heap）是一个可以被看成近似完全二叉树的数组。树上的每一个结点对应数组的一个元素。除了最底层外，该树是完全充满的，而且是从左到右填充。堆结构的一个常见应用是建立优先队列（Priority Queue）。栈通常出现在力扣中等难度偏上的面试题目中。栈的最大特点就是后进先出（LIFO），需要和队列先进先出（FIFO）有所区分。

6.哈希表（4道）

哈希表（Hash Table，也叫散列表），支持快速插入和搜索。是根据键（Key）而直接访问在内存存储位置的数据结构。也就是说，它通过计算一个关于键值的函数，将所需查询的数据映射到表中一个位置来访问记录，这加快了查找速度。这个映射函数称做哈希函数，存放记录的数组称做哈希表。

有两种不同类型的哈希表：哈希集合和哈希映射。

哈希集合是集合数据结构的实现之一，用于存储非重复值。
哈希映射是映射 数据结构的实现之一，用于存储 (key, value) 键值对。
在标准模板库的帮助下，哈希表是易于使用的。大多数常见语言（如Java，C ++ 和 Python）都支持哈希集合和哈希映射。

7.树（6道）

树是一种经常用到的数据结构，用来模拟具有树状结构性质的数据集合。树是面试的热门考点，尤其是二叉搜索树（BST）。大部分关于树的面试题都与递归有关，掌握好树能证明你对递归有很好的认识，也能帮助你学习图论。

8.分治算法（4道）

在计算机科学中，分治法是构建基于多项分支递归的一种很重要的算法范式。字面上的解释是「分而治之」，就是把一个复杂的问题分成两个或更多的相同或相似的子问题，直到最后子问题可以简单的直接求解，原问题的解即子问题的解的合并。

这个技巧是很多高效算法的基础，如排序算法（快速排序、归并排序）、傅立叶变换（快速傅立叶变换）。

9.回溯算法（4道）

回溯是一种试探算法，和暴力搜索相比，根据每一步小心试探得到的情况进行评估，如果当前的情况已经无法满足要求，那么我们就没有必要继续进行下去，可以帮助我们避免走很多弯路。

在回溯中，当出现非法的情况时，算法可以回退到之前的情景，可以是返回一步，有时候甚至可以返回多步，然后再去尝试别的路径和办法。

利用回溯算法解决问题，可以采用以下的套路：

首先判断当前情况是否非法，如果非法就立即返回
看看当前情况是否已经满足递归结束条件，如果是就将当前结果保存起来并返回
在当前情况下，遍历所有可能出现的情况并进行下一步的尝试
递归完毕后，立即回溯，回溯的方法就是取消前一步进行的尝试

10.图论（5道）

图可以说是知识点最丰富的一个数据结构，而围绕图的算法也是各式各样。

图的存储和表达方式：邻接矩阵（Adjacency Matrix）、邻接链表（Adjacency List）
图的遍历：深度优先、广度优先
二部图的检测（Bipartite）、树的检测、环的检测
拓扑排序
并查集
最短路径：Dijkstra、Bellman-Ford
其中，关于图的遍历：深度优先和广度优先搜索的考察是近年来面试的重中之重。

11.动态规划（6道）

动态规划是通过把原问题分解为相对简单的子问题的方式求解复杂问题的方法。在求最优解问题时通常可以把问题分解成多个子问题，通过递归找到每个子问题的最优解，然后用数学方法对各个子问题的最优解进行组合得出最终的结果。

动态规划有两个重要的属性：

最优子结构（Optimal Substructure）：一般找到了最优子结构，也就能推导出一个状态转移方程 f(n)，通过这个状态转移方程，我们能很快地写出问题的递归实现方法。
重叠子问题（Overlapping Sub-problems）：当我们通过递归寻找每个子问题的最优解时，会重复遇到更小的子问题，而且这些子问题会重叠地出现在子问题里。虽然我们无法通过数学的方法去避免重复计算，但是可以借助编程的技巧去保证每个重叠的子问题只会被求解一次。

12.数学（4道）

不论是数学与计算，还是对 bit 进行操作，你都需要和数字打交道。面试中提出的大部分数学问题都不需要超出初中阶段的数学知识。本章精选了 2020 年互联网名企面试中的高频数学题目。

13.设计（3道）

这类问题通常要求你实现一个给定的类的接口，并可能涉及使用一种或多种数据结构。 这些问题对于提高数据结构是很好的练习。
