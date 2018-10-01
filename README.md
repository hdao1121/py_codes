# py_codes

A collection of python challenges that are fun to solve

### Word Adjacent Search
Given a 2D board and a list of words from the dictionary, find all words in the board.

Each word must be constructed from letters of sequentially adjacent cell, where "adjacent" cells are those horizontally or vertically neighboring. The same letter cell may not be used more than once in a word.

```
Input:
words = ["oath","pea","eat","rain"]
board =
[
  ['o','a','a','n'],
  ['e','t','a','e'],
  ['i','h','k','r'],
  ['i','f','l','v']
]

Output: ["eat","oath"]
```

### Max Points on a Line
Given n points on a 2D plane, find the maximum number of points that lie on the same straight line.

Example 1:
```
Input: [[1,1],[2,2],[3,3]]
Output: 3
Explanation:
^
|
|        o
|     o
|  o  
+------------->
0  1  2  3  4
```
Example 2:

```
Input: [[1,1],[3,2],[5,3],[4,1],[2,3],[1,4]]
Output: 4
Explanation:
^
|
|  o
|     o        o
|        o
|  o        o
+------------------->
0  1  2  3  4  5  6
```

### First Missing Positive
Given an unsorted integer array, find the smallest missing positive integer.

```
Example 1:

Input: [1,2,0]
Output: 3
```
```
Example 2:

Input: [3,4,-1,1]
Output: 2
```
```
Example 3:

Input: [7,8,9,11,12]
Output: 1
```

Note:
The algorithm should run in O(n) time and uses constant extra space.
