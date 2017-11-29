# 基于决策树和Alpha- Beta剪枝的五子棋程序

## 决策树
决策树(Decision Tree）是在已知各种情况发生概率的基础上，通过构成决策树来求取净现值的期望值大于等于零的概率，评价项目风险，判断其可行性的决策分析方法，是直观运用概率分析的一种图解法。由于这种决策分支画成图形很像一棵树的枝干，故称决策树。

## 极大极小值原理
Minimax算法 又名极小化极大算法，是一种找出失败的最大可能性中的最小值的算法（即最小化对手的最大得益，最大化己方利益）。通常以递归形式来实现，适用于处理离散的零和博弈问题。
Minimax算法常用于五子棋/国际象棋等由两方较量的游戏和程序。

## Alpha-Beta剪枝

Alpha-Beta剪枝是一种简化决策树的方法，其可以将复杂度为 $p$ 的决策树简化为 $\sqrt{p}$

## 使用方法

``` shell
git clone https://github.com/leonidas141/Gobang-minmax/
cd Gobang-minmax/
python main.py
```
高难度请使用
```
python main.py hard
```
