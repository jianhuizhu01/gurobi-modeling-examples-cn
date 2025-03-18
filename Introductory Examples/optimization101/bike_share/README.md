# 使用数学优化进行共享单车重新平衡

## 问题
使用2022年7月纽约和新泽西地区Citi-bike的历史数据，我们想要了解：

- 在8月第一周，每个站点每小时的单车需求量是多少？
- 在了解需求的情况下，如何最小化销售损失？

我们使用机器学习（ML）和数学优化（MO）的组合来解决这个问题。

## 仓库指南
- 预测8月第一周每个站点每小时单车流入和流出数量的机器学习模型，
  可以在[predict_bike_flow](predict_bike_flow.ipynb)笔记本中找到。
- 决定每个站点每小时应增加或减少多少单车的数学优化模型
  （目标是最小化总销售损失）在[bike_rebalancing](bike_rebalancing.ipynb)笔记本中。
- 数据来自Citi-bike数据网站。这些数据在[predict_bike_flow](predict_bike_flow.ipynb)笔记本中进行处理。
- [stations_flow.csv](stations_flow.csv)和[top_stations.csv](top_stations.csv)是机器学习模型的输出，
  它们作为数学优化模型的输入。当然，您可以运行[predict_bike_flow](predict_bike_flow.ipynb)笔记本，
  甚至可以根据需要修改它以获得新的结果。只需确保输出格式类似，
  以便您可以使用[bike_rebalancing](bike_rebalancing.ipynb)笔记本中的数学优化模型。

## 查看笔记本

[Google Colab链接](https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/optimization101/bike_share/bike_rebalancing_complete.ipynb)

----
有关许可证或运行笔记本的详细信息，请参阅[建模示例](../../)概述<br>
此笔记本可以使用Gurobi的"在线课程"版本运行。
