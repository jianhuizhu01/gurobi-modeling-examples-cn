# 曲线拟合

本 Jupyter Notebook 介绍了一个将函数拟合到一组观测值的示例。已知一个量 y 依赖于另一个量 x。收集了一组 y 和 x 的对应值。我们想要确定一个 x 的函数来解释 y 的值。这个问题使用 Gurobi Python API 被构建为线性规划问题，并使用 Gurobi 优化器求解。

这个模型是 H. Paul Williams 所著《数学规划中的模型构建》第五版第 266 页和第 319-320 页中的示例 11。

这个建模示例属于初级水平，我们假设您了解 Python 并且对构建数学优化模型有一定了解。读者还应参考 Gurobi Python API 的[文档](https://www.gurobi.com/resources/?category-filter=documentation)。

## 查看 notebook

[Google Colab 链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/curve_fitting/curve_fitting.ipynb)


----
有关许可证或运行 notebooks 的详细信息，请参见[建模示例](../)概述

© Gurobi Optimization, LLC