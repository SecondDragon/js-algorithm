# js-algorithm
Use js to implement leetcode algorithm



| 题目编号(topic number)                                    | 文件名(file name)                                            | 描述                                                         | description                                                  |
| --------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1~50                                                      | [part1](https://github.com/JunLiangWangX/js-algorithm/tree/main/part1) | 题1到题50归档集合                                            | Question 1 to Question 50 archive collection                 |
| [#51](https://leetcode.cn/problems/n-queens/)             | [N-Queens](https://github.com/JunLiangWangX/js-algorithm/blob/main/51.N-Queens.js) | n 皇后问题研究的是如何将 n 个皇后放置在 n×n 的棋盘上，并且使皇后彼此之间不能相互攻击。给你一个整数 n ，返回所有不同的 n 皇后问题 的解决方案。 | The n-queens puzzle is the problem of placing n queens on an n x n chessboard such that no two queens attack each other.Given an integer n, return all distinct solutions to the n-queens puzzle. You may return the answer in any order. |
| [#52](https://leetcode.cn/problems/n-queens-ii/)          | [N-QueensII](https://github.com/JunLiangWangX/js-algorithm/blob/main/52.N-QueensII.js) | n 皇后问题 研究的是如何将 n 个皇后放置在 n × n 的棋盘上，并且使皇后彼此之间不能相互攻击。给你一个整数 n ，返回 n 皇后问题 不同的解决方案的数量。 | The n-queens puzzle is the problem of placing n queens on an n x n chessboard such that no two queens attack each other.Given an integer n, return the number of distinct solutions to the n-queens puzzle. |
| [#53](https://leetcode.cn/problems/maximum-subarray/)     | [MaximumSubarray](https://github.com/JunLiangWangX/js-algorithm/blob/main/53.MaximumSubarray.js) | 给你一个整数数组 `nums` ，请你找出一个具有最大和的连续子数组（子数组最少包含一个元素），返回其最大和。 | Given an integer array nums, find the subarray with the largest sum, and return its sum. |
| [#54](https://leetcode.cn/problems/spiral-matrix/)        | [SpiralMatrix](https://github.com/JunLiangWangX/js-algorithm/blob/main/54.SpiralMatrix.js) | **子数组** 是数组中的一个连续部分。给你一个 `m` 行 `n` 列的矩阵 `matrix` ，请按照 **顺时针螺旋顺序** ，返回矩阵中的所有元素。 | Given an `m x n` `matrix`, return *all elements of the* `matrix` *in spiral order*. |
| [#55](https://leetcode.cn/problems/jump-game/)            | [JumpGame](https://github.com/JunLiangWangX/js-algorithm/blob/main/55.JumpGame.js) | 给定一个非负整数数组 `nums` ，你最初位于数组的 **第一个下标** 。数组中的每个元素代表你在该位置可以跳跃的最大长度。判断你是否能够到达最后一个下标。 | You are given an integer array nums. You are initially positioned at the array's first index, and each element in the array represents your maximum jump length at that position.Return true if you can reach the last index, or false otherwise. |
| [#56](https://leetcode.cn/problems/merge-intervals/)      | [MergeIntervals](https://github.com/JunLiangWangX/js-algorithm/blob/main/56.MergeIntervals.js) | 以数组 intervals 表示若干个区间的集合，其中单个区间为 intervals[i] = [starti, endi] 。请你合并所有重叠的区间，并返回 一个不重叠的区间数组，该数组需恰好覆盖输入中的所有区间 。 | Given an array of intervals where intervals[i] = [starti, endi], merge all overlapping intervals, and return an array of the non-overlapping intervals that cover all the intervals in the input. |
| [#57](https://leetcode.cn/problems/insert-interval/)      | [InsertInterval](https://github.com/JunLiangWangX/js-algorithm/blob/main/57.InsertInterval.js) | 给你一个 **无重叠的** *，*按照区间起始端点排序的区间列表。在列表中插入一个新的区间，你需要确保列表中的区间仍然有序且不重叠（如果有必要的话，可以合并区间）。 | Gives you a **non-overlapping** * list of intervals sorted by their start and end points. To insert a new interval into a list, you need to make sure that the intervals in the list are still ordered and not overlapping (merging intervals if necessary). |
| [#58](https://leetcode.cn/problems/length-of-last-word/)  | [LengthOfLastWord](https://github.com/JunLiangWangX/js-algorithm/blob/main/58.LengthOfLastWord.js) | 给你一个字符串 s，由若干单词组成，单词前后用一些空格字符隔开。返回字符串中 最后一个 单词的长度。单词 是指仅由字母组成、不包含任何空格字符的最大子字符串。 | Given a string s consisting of words and spaces, return the length of the last word in the string.A word is a maximal substring consisting of non-space characters only. |
| [#59](https://leetcode.cn/problems/spiral-matrix-ii/)     | [SpiralMatrixII](https://github.com/JunLiangWangX/js-algorithm/blob/main/59.SpiralMatrixII.js) | 给你一个正整数 `n` ，生成一个包含 `1` 到 `n^2` 所有元素，且元素按顺时针顺序螺旋排列的 `n x n` 正方形矩阵 `matrix` 。 | Given a positive integer n, generate an n x n matrix filled with elements from 1 to n^2 in spiral order. |
| [#60](https://leetcode.cn/problems/permutation-sequence/) | [PermutationSequence](https://github.com/JunLiangWangX/js-algorithm/blob/main/60.PermutationSequence.js) | 给出集合 [1,2,3,...,n]，其所有元素共有 n! 种排列。按照排列升序返回第 k 个排列。 | Given a set [1,2,3,...,n], where all elements can form n! kind of permutation. Return the kth permutation in ascending order. |
| [#61](https://leetcode.cn/problems/rotate-list/)          | [RotateList](https://github.com/JunLiangWangX/js-algorithm/blob/main/61.RotateList.js) | 给你一个链表的头节点 `head` ，旋转链表，将链表每个节点向右移动 `k` 个位置。 | Given the `head` of a linked list, rotate the list to the right by `k` places. |
| [#62](https://leetcode.cn/problems/unique-paths/)         | [UniquePaths](https://github.com/JunLiangWangX/js-algorithm/blob/main/62.UniquePaths.js) | 一个机器人位于一个 m x n 网格的左上角机器人每次只能向下或者向右移动一步。机器人试图达到网格的右下角问总共有多少条不同的路径？ | A robot is located in the upper left corner of an m x n grid. The robot can only move one step down or to the right at a time. How many different ways are there always in the bottom right corner of the robot trying to figure out the network grid? |
| [#63](https://leetcode.cn/problems/unique-paths-ii/)      | [UniquePathsII](https://github.com/JunLiangWangX/js-algorithm/blob/main/63.UniquePathsII.js) | 一个机器人位于一个 m x n 网格的左上角 。机器人每次只能向下或者向右移动一步。机器人试图达到网格的右下角。现在考虑网格中有障碍物。那么从左上角到右下角将会有多少条不同的路径？网格中的障碍物和空位置分别用 1 和 0 来表示。 | A robot is located in the upper left corner of an m x n grid. The robot can only move one step down or to the right at a time. The robot tries to reach the bottom right corner of the grid. Now consider that there are obstacles in the grid. So how many different paths will there be from top left to bottom right? Obstacles and empty positions in the grid are represented by 1 and 0, respectively. |
| [#64](https://leetcode.cn/problems/minimum-path-sum/)     | [MinimumPathSum](https://leetcode.cn/problems/minimum-path-sum/) | 给定一个包含非负整数的 m x n 网格 grid ，请找出一条从左上角到右下角的路径，使得路径上的数字总和为最小。说明：每次只能向下或者向右移动一步。 | Given a m x n grid filled with non-negative numbers, find a path from top left to bottom right, which minimizes the sum of all numbers along its path.Note: You can only move either down or right at any point in time. |
| [#65](https://leetcode.cn/problems/valid-number/)         | [ValidNumber](https://github.com/JunLiangWangX/js-algorithm/blob/main/65.ValidNumber.js) | 给定一个字符串，判断字符串是否一个有效的数字                 | Given a string, determine whether it is a valid number       |
| [#66](https://leetcode.cn/problems/plus-one/)             | [PlusOne](https://github.com/JunLiangWangX/js-algorithm/blob/main/66.PlusOne.js) | 给定一个由 整数 组成的 非空 数组所表示的非负整数，在该数的基础上加一。最高位数字存放在数组的首位， 数组中每个元素只存储单个数字。你可以假设除了整数 0 之外，这个整数不会以零开头。 | You are given a large integer represented as an integer array digits, where each digits[i] is the ith digit of the integer. The digits are ordered from most significant to least significant in left-to-right order. The large integer does not contain any leading 0's.Increment the large integer by one and return the resulting array of digits. |
| [#67](https://leetcode.cn/problems/add-binary/)           | [AddBinary](https://github.com/JunLiangWangX/js-algorithm/blob/main/67.AddBinary.js) | 给你两个二进制字符串 `a` 和 `b` ，以二进制字符串的形式返回它们的和。 | Given two binary strings `a` and `b`, return *their sum as a binary string*. |
| [#68](https://leetcode.cn/problems/text-justification/)   | [TextJustification](https://github.com/JunLiangWangX/js-algorithm/blob/main/68.TextJustification.js) | 给定一个单词数组 `words` 和一个长度 `maxWidth` ，重新排版单词，使其成为每行恰好有 `maxWidth` 个字符，且左右两端对齐的文本。 | Given an array of strings words and a width maxWidth, format the text such that each line has exactly maxWidth characters and is fully (left and right) justified. |
| [#59](https://leetcode.cn/problems/sqrtx/)                | [Sqrt(x)](https://github.com/JunLiangWangX/js-algorithm/blob/main/69.Sqrt(x).js) | 给你一个非负整数 x ，计算并返回 x 的 算术平方根 。结果只保留 整数部分 | Given a non-negative integer x, compute and return the arithmetic square root of x. Only the integer part of the result is kept |

