# 牛油果价格优化：第1部分和第2部分

在拥有良好数据的情况下，牛油果定价和供应问题为展示优化和数据科学的强大功能提供了成熟的机会。本示例演示了如何使用预测性和规范性分析来优化牛油果价格以实现收入最大化。我们将使用回归分析和二次规划来实现这个目标。我们将演示如何在Gurobi Python API中实现这个模型，并使用Gurobi优化器生成最优解。

本示例分为两个部分。**第1部分**包含完整的问题描述，目标是使用二次规划找到使牛油果销售收入最大化的价格。价格和需求之间的关系使用线性回归建模。

**第2部分**利用Gurobi的开源包[Gurobi Machine Learning](https://gurobi-machinelearning.readthedocs.io/en/stable/index.html)，该包允许使用`Scikit Learn`对象拟合价格和需求之间的关系，并直接将其作为约束添加到优化模型中。

这个建模教程属于入门级别，我们假设您了解Python，并且具有使用定量方法的学科背景。

您可能会发现参考[Gurobi Python API](https://www.gurobi.com/documentation/current/refman/py_python_api_overview.html)的文档很有帮助。
这个notebook在我们关于数据科学和数学优化的网络研讨会中有详细解释。您可以点击[这里](https://www.youtube.com/watch?v=AJRP9pPBx6s)观看这些视频。


## 查看notebook

[Google Colab链接 - 第1部分](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/price_optimization/price_optimization.ipynb)

[Google Colab链接 - 第2部分](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/price_optimization/price_optimization_gurobiML.ipynb)


----
有关许可证或运行notebook的详细信息，请参阅[建模示例](../)概述

© Gurobi优化有限责任公司