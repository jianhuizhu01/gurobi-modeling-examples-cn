# 收益管理

这个模型是收益管理问题的一个例子。
收益管理是一种变动定价策略，它基于理解、预测和影响消费者行为，
以便从固定的、时间有限的资源（如航空座位）中获取最大收益或利润。这个收益管理问题被
formulated作为一个三阶段随机规划问题，使用Gurobi Python API构建并由Gurobi优化器求解。

这个模型是H. Paul Williams所著的《数学规划中的模型构建》第五版中的第24个例子，
见第282-284页和337-340页。

这个建模示例属于高级水平，我们假设您了解Python和Gurobi Python API，
并且您具有构建数学优化模型的高级知识。通常，这些示例的目标
函数和/或约束条件比较复杂，或需要使用Gurobi Python API的高级功能。

## 查看笔记本

[Google Colab链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/yield_management/yield_management.ipynb)

请注意，您需要完整的Gurobi许可证才能运行此笔记本。

----
有关许可证的详细信息或运行笔记本的方法，请参阅[建模示例](../)概述

© Gurobi Optimization, LLC
