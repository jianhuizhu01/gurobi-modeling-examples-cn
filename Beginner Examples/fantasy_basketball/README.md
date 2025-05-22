# 梦幻篮球

在过去的十到二十年里，梦幻体育已经发展成为一项主流活动，现在各大联盟都与知名梦幻体育网站建立了官方合作伙伴关系。如果您不熟悉梦幻体育，其目标是从真实比赛中选择球员来组建一支虚拟阵容。

选中的球员的表现会被转换为梦幻积分，例如，一个篮球运动员的得分、篮板、助攻和失误会产生一个单一的梦幻积分值。最高的总分用于决定大型比赛的获胜者。简而言之，您要挑选您的梦之队。

但是选择最好的球员并不那么容易，因为每个球员都被赋予了一个薪资值，而您的阵容总薪资不能超过给定的值（即工资帽）。您的阵容还必须满足位置限制，这使得选择阵容变得更加困难。

本示例首先使用 NBA 比赛数据来构建一个监督机器学习模型，该模型预测球员在单日比赛中的梦幻积分输出。
然后将这些预测用于优化模型中，该模型将从五个主要位置中各选择一名球员，以选出最优团队。

第二部分扩展了优化模型以反映实际的梦幻篮球比赛，展示了不同的约束建模方法，并
介绍了约束的*松弛度*概念。

## 查看notebook

[Google Colab 链接 第1部分](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/fantasy_basketball/fantasy_basketball_part1.ipynb)

[Google Colab 链接 第2部分](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/fantasy_basketball/fantasy_basketball_part2.ipynb)

----
有关许可或运行notebooks的详细信息，请参阅[建模示例](../)概述

© Gurobi Optimization, LLC