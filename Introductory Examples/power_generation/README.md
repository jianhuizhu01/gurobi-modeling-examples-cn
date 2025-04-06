# 优化发电调度

假设我们负责美国佐治亚州的发电任务。假定我们已知所有可用发电厂的信息以及一天中每个小时的用电需求。我们能否制定一个调度计划来决定每个发电厂应该发多少电，以及何时"开启"和"关闭"这些发电厂？如何在此过程中将总成本降到最低？

在本教程中，我们使用数学优化方法对这个决策问题进行建模。在这个发电问题中，目标是最小化总成本。决策变量用于建模发电调度。约束条件包括确保供电满足需求等基本要求，以及每个发电厂的最小和最大产能等实际限制。通过找到最优的成本效益调度方案，该模型帮助发电厂运营者在最小化总成本的同时获得最佳的设施输出。

这是一个入门级的建模教程，我们假设你已掌握 Python 并具有使用定量方法的学科背景。

你可能会发现参考 [Gurobi Python API](https://www.gurobi.com/documentation/current/refman/py_python_api_overview.html) 的文档会有所帮助。

## 查看教程

[Google Colab 链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/power_generation/optimize_power_schedule.ipynb)


----
关于许可证或运行教程的详细信息，请参阅[建模示例](../)概述

© Gurobi Optimization, LLC