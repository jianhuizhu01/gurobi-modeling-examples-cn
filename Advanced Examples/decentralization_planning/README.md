# 去中心化规划

本模型是一个设施选址问题的示例。给定公司的一组部门，以及这些部门可能设立的城市地点，我们希望确定每个部门的"最佳"位置，以实现利润最大化。这个问题使用Gurobi Python API被建模为二次分配问题，并通过Gurobi优化器求解。

本模型是H. Paul Williams所著《数学规划中的模型构建》第五版第265页和317-319页中的示例10。

这个建模示例属于高级水平，我们假设您了解Python和Gurobi Python API，并且在构建数学优化模型方面具有进阶知识。通常，这些示例的目标函数和/或约束条件较为复杂，或需要使用Gurobi Python API的高级功能。

## 查看notebook

[Google Colab链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/decentralization_planning/decentralization_planning.ipynb)

----
有关许可或运行notebooks的详细信息，请参阅[建模示例](../)概述

© Gurobi Optimization, LLC