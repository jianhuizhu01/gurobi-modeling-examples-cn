# 使用线性规划进行文本相异度分析

在本教程中，我们将通过一个独特的示例演示如何应用优化方法来评估文本的相异度。这种方法有许多潜在的应用，比如检测抄袭、信息检索、聚类分析、文本分类、主题检测、问答系统、机器翻译和文本摘要。

词移距离（Word Mover's Distance，WMD）是一种广受欢迎的文本相似度度量方法，用于测量两个文档之间的语义距离。在本教程中，我们将实现两个目标：

1. 给定两段文本，将WMD建模为优化问题并计算结果
2. 检查一本书中的抄袭段落，然后在该书中找到与给定段落语义最接近的原始段落

这是一个入门级的建模教程，我们假设您具备Python编程知识，并且具有使用定量方法的相关学科背景。

您可能会发现参考[Gurobi Python API](https://www.gurobi.com/documentation/current/refman/py_python_api_overview.html)文档很有帮助。


## 查看教程

[Google Colab 链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/text_dissimilarity/text_dissimilarity.ipynb)


----
有关许可证或运行教程的详细信息，请参阅[建模示例](../)概述

© Gurobi Optimization, LLC