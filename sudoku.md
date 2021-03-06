# 数独 (sudoku.c)

## 题目描述

# sudoku

数独是根据 9*9 盘面上的已知数字，推理出所有剩余空格的数字，并满足每一行、每一列、每一个粗线宫内的数字均含 1 - 9，不重复。

**水龙之魂**设计出了全球最难的“数独游戏”，并刊登在报纸上，让大家去挑战。

**ant-hengxin**自称解决了这些数独问题，请你判断他是否真的解决了这些数独问题。

![A.png](https://cdn.acwing.com/media/article/image/2019/04/18/19_165f3c0a61-1.png)

## 输入格式

输入共9行

输入的每1行包含9个正整数x，代表蚂蚁填好的数独（蚂蚁可能会乱填数独，导致出现大于9的数）

## 输出格式

输出共一行，输出"YES"或在"NO"(不含双引号)

YES 代表ant-hengxin填好的数独合法

NO 代表ant-hengxin填好的数独不合法

## 脚注

左上角的3*3粗宫格内出现了2个1，不合法`

## 样例

### 样例输入

8 1 2 7 5 3 6 4 9
9 4 3 6 8 2 1 7 5
6 7 5 4 9 1 2 8 3
1 5 4 2 3 7 8 9 6
3 6 9 8 4 5 7 2 1
2 8 7 1 6 9 5 3 4
5 2 1 9 7 4 3 6 8
4 3 8 5 2 6 9 1 7
7 9 6 3 1 8 4 5 2

### 样例输出

YES

### 样例输入

8 1 2 7 5 3 6 4 9
9 4 1 6 8 2 3 7 5
6 7 5 4 9 1 2 8 3
1 5 4 2 3 7 8 9 6
3 6 9 8 4 5 7 2 1
2 8 7 1 6 9 5 3 4
5 2 3 9 7 4 1 6 8
4 3 8 5 2 6 9 1 7
7 9 6 3 1 8 4 5 2  

### 样例输出

NO
