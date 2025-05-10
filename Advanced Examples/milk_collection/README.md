# 牛奶收集问题

牛奶收集问题是一个有容量限制的车辆路径问题的示例。在这个问题中，一辆容量有限的油罐车从一组农场收集牛奶，目标是确定油罐车的最优路线。该问题使用 Gurobi Python API 构建为二进制优化问题，并通过 Gurobi 优化器求解。

本模型是 H. Paul Williams 所著《数学规划中的模型构建》第五版第 278-281 页和 336-337 页中的示例 23。

这个建模示例属于高级水平，我们假设您了解 Python 和 Gurobi Python API，并且具有构建数学优化模型的高级知识。通常，这些示例的目标函数和/或约束条件比较复杂，或需要使用 Gurobi Python API 的高级功能。

## 查看笔记本

[Google Colab 链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/milk_collection/milk_collection.ipynb)

----
有关许可或运行笔记本的详细信息，请参见[建模示例](../)概述

© Gurobi Optimization, LLC