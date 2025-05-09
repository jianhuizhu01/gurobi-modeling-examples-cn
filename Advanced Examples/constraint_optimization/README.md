# 约束优化

本模型是约束优化问题的一个示例。考虑整数规划模型中的一个约束，其中约束中的所有决策变量都是二进制的，目标是找到另一个涉及相同二进制变量的约束，该约束在逻辑上等同于原始约束，但具有最小可能的右侧绝对值。这个问题使用Gurobi Python API formulated为线性规划问题，并使用Gurobi优化器求解。

该模型是H. Paul Williams所著《Model Building in Mathematical Programming》第五版第273页和328-330页中的示例18。

这个建模示例属于高级水平，我们假设您了解Python和Gurobi Python API，并且具有构建数学优化模型的高级知识。通常，这些示例的目标函数和/或约束是复杂的，或需要Gurobi Python API的高级功能。

## 查看notebook

[Google Colab链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/constraint_optimization/constraint_optimization.ipynb)


----
有关许可或运行notebooks的详细信息，请参阅[建模示例](../)概述

© Gurobi优化有限责任公司