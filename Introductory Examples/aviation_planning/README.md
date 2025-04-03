# 航班中断后的航空计划调整

天气事件是航空业面临的主要威胁。暴风雪、暴雨和结冰跑道的不可预测性使得航空计划人员难以制定准确的时刻表。

本教程将介绍如何在遇到天气中断后，决定哪些航班继续运营、哪些航班取消的优化问题。我们通过构建一个数学优化模型来减少因航班取消带来的收入损失。在这个例子中，我们使用了由[Amadeus](https://amadeus.com/en)收集的法国真实数据。

这是一个入门级的建模教程，我们假设您了解Python，并且具有使用定量方法的学科背景。

您可能会发现参考[Gurobi Python API](https://www.gurobi.com/documentation/current/refman/py_python_api_overview.html)的文档很有帮助。

## 查看教程

[Google Colab链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/aviation_planning/airlineplanning.ipynb)


----
有关许可或运行教程的详细信息，请参阅[建模示例](../)概述

© Gurobi Optimization, LLC