# 最优子集选择：L0回归

## 动机

线性回归发明于19世纪初，在200多年后的今天，它仍然被广泛应用于实践中的描述和预测目的：

- 在计量经济学中，通过对销售收入与价格以及其他特征（如人口统计、竞争对手和零售信息）进行回归分析，可以估算特定产品的价格弹性。
- 在医疗领域，它可以用来预测患者在医院急诊室的停留时间（即住院时长），基于患者信息、分诊评估、医学检查结果和到达日期/时间。
- 在社会科学中，它可以揭示学生未来的学业表现，从而采取主动措施改善其学习成果。

一般来说，线性回归用于模拟连续变量与其他解释变量（可以是连续的或分类的）之间的关系。在应用这种技术时，寻找能够最大化其性能的特征子集通常很有意义。

这个建模示例属于中级水平，我们假设您了解Python并熟悉Gurobi Python API。此外，您还应该具备构建数学优化模型的相关知识。

## 解决方案

一个混合整数二次规划（MIQP）公式，用于找到线性回归问题的权重估计，其中恰好有's'个权重必须为非零。

## 解决方案的主要特点

- 最小化训练残差平方和（RSS）。
- 使用交叉验证和网格搜索来选择模型中包含的特征数量。
- 与scikit-learn的普通最小二乘（OLS）回归和Lasso实现进行基准比较。

## 附加价值

与Lasso不同，L0回归具有尺度不变性，且不会给权重估计增加偏差。此外，这种方法还可以指定额外的线性约束，例如：

- 强制特征组稀疏性
- 限制成对多重共线性
- 限制全局多重共线性
- 考虑固定的非线性变换集

## 成功案例

Bertsimas等人（2016）成功地将数学规划应用于求解线性回归的最优子集选择问题。

## 查看notebook

[Google Colab链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/linear_regression/l0_regression.ipynb)

----
有关许可证或运行notebook的详细信息，请参阅[建模示例](../)概述


Copyright © 2020 Gurobi Optimization, LLC
