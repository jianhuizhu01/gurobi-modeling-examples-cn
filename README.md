[![Gurobi](assets/img/gurobi-light.png)](https://www.gurobi.com)

# Gurobi数学建模示例

## 目标受众
数据科学家、工程师、计算机科学家、经济学家，以及一般具有数学建模背景和Python基础知识的专业人员。

## 建模示例的目标
+ 说明数学优化的广泛适用性。
+ 展示如何构建数学优化模型。

这些建模示例使用 Gurobi Python API 进行编码，并以 Jupyter Notebooks 的形式发布。

这些建模示例展示了 Gurobi Python API 的重要功能，包括添加决策变量、构建线性表达式、添加约束以及添加目标函数。它们涉及更高级的功能，如广义约束、分段线性函数和多目标分层优化。它们还展示了常见的约束类型，如“分配约束”、“平衡约束”、“排序约束”、“优先约束”等。

这些示例来自不同的业务目的，反映了构建数学优化模型的不同水平。

## 入门示例（Introductory Examples）

入门示例将引导您完成构建数学优化模型的过程。基本要求是您了解 Python 并且具有使用定量方法的学科背景。

- [Gurobipy 简介（Intro to Gurobipy）:](./Introductory%20Examples/intro_to_gurobipy)
  本教程在 2023 年 Gurobi Days Digital 活动中提供。它是对 Gurobi Python API（Gurobipy）的介绍。它将带您了解 Gurobipy 的基础知识，并通过一些小例子解释其用法。
- [数学优化建模简介（Intro to Mathematical Optimization Modeling）:](./Introductory%20Examples/milp_tutorial)
  本教程以一个简单的分配问题为例，讨论数学建模的基础知识。
- 优化入门101（Optimization 101）:
  本教程基于[面向数据科学家的优化入门101（Optimization 101 for Data Scientists）](https://www.gurobi.com/events/optimization-101-for-data-scientists/)网络研讨会，由两个包含练习和问题的建模环节以及一个用例讨论组成。
- 以下示例以非常详细的方式逐步讨论输入数据和优化模型。
  - [航班中断后的航空公司规划（Airline Planning After Flight Disruption）](./Introductory%20Examples/aviation_planning)
  - [音乐推荐（Music Recommendation）](./Introductory%20Examples/music_recommendation)
  - [文本差异度（Text Dissimilarity）](./Introductory%20Examples/text_dissimilarity)
  - [发电（Power Generation）](./Introductory%20Examples/power_generation)
  - [价格优化（Price Optimization）](./Introductory%20Examples/price_optimization)


## 初级示例（Beginner Examples）

初学者级别的笔记本假设你了解 Python 并且对构建数学优化模型有一些了解。

- [三维井字棋游戏（3D Tic-Tac-Toe）](./Introductory%20Examples/3d_tic_tac_toe):
  这个示例将向您展示二进制规划模型如何用于捕捉简单的逻辑约束。
- [信号塔（Cell Tower）](./Introductory%20Examples//cell_tower_coverage):
  在这个例子中，你将学习如何定义和解决一个覆盖类型的问题，即如何配置一个信号塔网络，以向最多的人提供信号覆盖。
- [曲线拟合（Curve Fitting）](./Introductory%20Examples/curve_fitting):
  尝试这个 Jupyter Notebook 建模示例，了解如何将函数拟合到一组观测值。
- 设施选址（Facility Location）:
  在这个示例中，我们将向您展示如何解决设施选址问题，该问题涉及确定为一组超市供应货物所需的仓库数量和位置。
- 梦幻篮球（Fantasy Basketball）:
  此示例在梦幻篮球中结合了机器学习和优化建模。
- 食品计划（Food Program）:
  在全球运输网络中运输食品是一项具有挑战性的任务。在本笔记本中，我们将构建一个优化模型，以根据联合国世界粮食计划署的真实数据建立食品供应链。
- 市场份额分配（Market Sharing）:
  在本示例中，我们将向您展示如何解决一个目标规划问题，该问题涉及将零售商分配给公司的两个部门，以优化多个市场份额目标之间的权衡。
- 营销活动优化（Marketing Campaign Optimization）:
  几乎每个行业的公司都在寻求优化其营销活动。在这个Jupyter Notebook中，我们将探讨银行和金融服务行业中常见的营销活动优化问题，该问题涉及确定向单个客户提供哪些产品，以便在满足各种业务约束的同时最大化总预期利润。
- 海上风力发电（Offshore Wind Farming）:
  在这个例子中，我们将学习如何解决海上风力发电问题。该问题的目标是确定应铺设哪些海底电缆以最低成本连接海上风电场电力网络。
- 供应网络设计1（Supply Network Design 1）:
  尝试这个Jupyter Notebook建模示例，学习如何解决经典的供应网络设计问题，该问题涉及找到通过网络的最小成本流。我们将向您展示——给定一组工厂、仓库和客户——如何使用数学优化来确定在最小化运输成本的同时满足客户需求的最佳方法。在第2部分中，我们还确定要打开或关闭哪些仓库以最小化总成本。
- Covid-19设施优化（Covid19 Facility Optimization）:
  这个COVID-19医疗设施容量优化问题是设施选址（Facility Location）问题的一个变体，向您展示如何确定医疗设施的最佳位置和容量。


## 进阶示例（Intermediate Examples）

中级水平的示例假设你了解 Python 并且熟悉 Gurobi Python API。此外，你应该具备构建数学优化模型的知识。

- 农产品定价（Agricultural Pricing）:
  尝试这个示例，了解如何使用数学优化来解决一个常见但关键的农产品定价问题：确定一个国家乳制品的价格和需求，以最大化这些产品销售所得的总收入。您将学习如何使用 Gurobi Python API 将此问题建模为二次优化问题，并使用 Gurobi 优化器进行求解。
- 线性回归（Linear Regression）:
  在此示例中，你将学习如何使用数学规划进行带特征选择的线性回归。我们将向你展示如何构建此线性回归问题的混合整数二次规划（MIQP）模型。
- 汽车租赁（Car Rental）:
  本笔记本将教你如何使用数学优化来确定汽车租赁公司每天应该拥有多少辆车以及这些车每天应位于何处，以实现每周利润最大化。第二部分考虑了数学优化如何用于确定汽车租赁公司应在哪些地点扩展维修能力的扩展内容。
- 客户分配（Customer Assignment）:
  此笔记本是设施选址问题的中级版本。此外，我们展示了如何在预处理中使用机器学习，以减少大数据集的计算负担。
- 经济规划（Economic Planning）:
  在此示例中，你将了解到数学优化如何用于解决一个国家可能面临的宏观经济规划问题。目标是确定经济的不同可能增长模式。
- 效率分析（Efficiency Analysis）:
  数学优化如何用于衡量组织的效率？在此示例中，您将了解如何将效率分析模型制定为线性规划问题。
- 发电（Electrical Power Generation）:
  此模型是发电问题（也称为机组组合问题）的一个示例。它选择一组最优的发电站开启，以满足24小时时间范围内的预期电力需求。在第二部分中，该模型得到扩展，并增加了使用水力发电厂满足需求的选项。
- 工厂规划（Factory Planning）:
  在此示例中，我们创建了一个可使利润最大化的最佳生产计划。在第二部分中，我们创建了一个不仅能使利润最大化，还能确定对机器进行维护操作的月份的最佳生产计划。
- 食品制造（Food Manufacturing）:
  您将学习如何为一种需要多种配料的产品制定最佳的多周期生产计划——每种配料都有不同的成本、限制和特性。在第二部分中，考虑了额外的约束条件，这些约束条件将问题类型从线性规划（LP）问题转变为混合整数规划（MIP）问题，使其更难求解。
- 逻辑设计（Logical Design）:
  在这个示例中，你将学习如何解决逻辑设计问题，该问题涉及使用最少数量的或非门（具有两个输入和一个输出的设备）构建一个电路，该电路将执行由真值表指定的逻辑功能。
- 采矿（Mining）:
  在此示例中，您将学习如何对涉及在五年内优化一组矿山运营的多周期生产计划问题进行建模和求解。
- 露天采矿（Opencast Mining）:
  此笔记本展示了一个数学优化问题，用于确定选择哪些挖掘地点以最大限度地提高矿石开采的毛利。
- 发电（Power Generation）:
  假设我们知道所有可用发电厂的集合以及一天中每小时的电力需求。我们希望创建一个时间表，以决定每个发电厂应产生多少电力，以及何时将发电厂“开启”和“关闭”，以便将总成本降至最低。
- 炼油厂（Refinery）:
  此模型是生产计划问题的一个示例，在该问题中，必须就生产哪些产品以及使用哪些资源做出决策。
- 技术人员路线规划与调度（Technician Routing and Scheduling）:
  尝试这个建模示例，了解数学优化如何帮助电信公司实现技术人员分配、调度和路线决策的自动化并加以改进，以确保实现最高水平的客户满意度。您将学习如何构建具有时间窗约束的多仓库车辆路径问题。
- 露天采矿（Opencast Mining）:
  该模型是生产计划问题的一个示例。一家矿业公司希望确定选择哪些挖掘地点，以最大限度地提高矿石开采的毛利。

## 高级示例（Advanced Examples）

对于高级水平的建模示例，我们假设你了解Python和Gurobi Python API，并且对构建数学优化模型有高级知识。通常，这些示例的目标函数和约束条件很复杂，或者需要Gurobi Python API的高级功能。

- 约束优化（Constraint Optimization）:
  在此示例中，我们考虑整数规划模型的一个约束，其中该约束中的所有决策变量都是二进制的，目标是找到另一个涉及相同二进制变量的约束，该约束在逻辑上与原始约束等效，但右侧的绝对值尽可能小。
- 分散规划（Decentralization Planning）:
  该模型是设施选址问题的高级版本。给定一家公司的一系列部门以及这些部门可能所在的潜在城市，我们希望确定每个部门的“最佳”位置，以实现毛利润最大化。
- 农场规划（Farm Planning）:
  这是一个高级生产规划问题的例子。
- 指数跟踪（Index Tracking）:
  指数跟踪投资组合优化。
- 丢失行李分配（Lost Luggage Distribution）:
  这是一个带时间窗的车辆路径问题示例。它涉及帮助一家公司确定将丢失或延误的行李运送给合法所有者所需的最少货车数量，并确定货车对客户的最佳分配。
- 人力规划（Manpower Planning）:
  此笔记本解决了一个人员配置规划问题，其中必须在人员招聘、培训、裁员和员工排班方面做出选择。
- 牛奶收集（Milk Collection）:
  这是一个容量受限的车辆路径问题示例。只有一辆容量有限的油罐车，你需要确定油罐车每天从一组农场收集牛奶的最佳路线。
- 投资组合选择优化（Portfolio Selection Optimization）:
  该模型是经典马科维茨投资组合选择优化模型的一个示例。我们希望找到在一组股票中进行投资的投资组合比例，以平衡风险和回报。它是一个二次规划（QP）模型，分别具有用于回报和风险的向量和矩阵数据。
- 汇集问题（Pooling）:
  众多行业的公司——包括石油化工炼油、废水处理和采矿——使用数学优化来解决汇集问题。这个问题可以被视为最小成本流问题和混合问题的推广。
- 蛋白质比较（Protein Comparison）:
  你将学习如何将蛋白质比较问题建模为二次分配问题。它涉及测量两种蛋白质的相似性。
- 蛋白质折叠（Protein Folding）:
  该问题涉及一种蛋白质，它由一条氨基酸链组成。目标是预测这条链的最佳折叠方式。
- 铁路调度（Railway Dispatching）:
  在这个笔记本中，我们研究容量有限的情况下共享资源（轨道和车站）的火车调度问题。目标是最小化延误。
- 旅行推销员（Traveling Salesman）:
  本笔记本涵盖了现存最著名的组合优化问题之一：旅行推销员问题（TSP）。TSP 的目标——找到访问每个城市一次并返回原始城市的最短可能路线——很简单，但解决这个问题是一项复杂而具有挑战性的努力。这个示例使用了 Gurobi 的[回调（callback）](https://www.gurobi.com/documentation/current/refman/py_cb_s.html)功能。
- 员工排班（Workforce Scheduling）:
  在本笔记本中，我们将展示如何使用数学优化来生成最佳员工排班，以最小化公司需要雇用的临时员工数量并最大限度地提高员工公平性。该问题被表述为多目标混合整数规划（MIP）模型，并使用 Gurobi 的[多目标功能（multiple objectives feature）](https://www.gurobi.com/documentation/current/refman/multiple_objectives.html)。
- 收益管理（Yield Management）:
  在此示例中，我们将向您展示航空公司如何使用人工智能技术制定最佳的座位定价策略。您将学习如何将此收益管理问题表述为一个三阶段随机规划问题。

## 按业务需求对示例分类

<details>  
  <summary>自动化</summary>
  <!--All you need is a blank line-->

  <ul>
    <li><a href="">Marketing Campaign Optimization</a> (beginner)</li>
    <li><a href="">Supply Network Design</a> (beginner)</li>
    <li><a href="">Technician Routing and Scheduling</a> (intermediate)</li>
    <li><a href="">Manpower Planning</a> (advanced)</li>
    <li><a href="">Workforce Scheduling</a> (advanced) </li>
  </ul>
</details>

<details>
  <summary>客户管理</summary>
  <!--All you need is a blank line-->

  <ul>
    <li><a href="">Supply Network Design</a> (beginner)</li>
    <li><a href="">Covid19 Facility Optimization</a> (beginner)</li>
    <li><a href="">Yield Management</a> (advanced)</li>
  </ul>
</details>

<details>
<summary>预测</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Price Optimization</a> (introductory)</li>
    <li><a href="">Music Recommendation</a> (introductory)</li>
    <li><a href="">Fantasy Basketball</a> (beginner)</li>
    <li><a href="">Covid19 Facility Optimization</a> (beginner)</li>
    <li><a href="">Agricultural Pricing</a> (intermediate)</li>
    <li><a href="">Linear Regression</a> (intermediate)</li>
  </ul>
</details>

<details>
<summary>库存优化</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Price Optimization</a> (introductory)</li>
    <li><a href="">Food Program</a> (beginner)</li>
    <li><a href="">Car Rental</a> (intermediate)</li>
    <li><a href="">Economic Planning</a> (intermediate)</li>
    <li><a href="">Factory Planning</a> (intermediate)</li>
    <li><a href="">Food Manufacturing</a> (intermediate)</li>
    <li><a href="">Farm Planning</a> (advanced)</li>
  </ul>
</details>  

<details>
<summary>选址规划</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Cell Tower</a> (beginner)</li>
    <li><a href="">Facility Location</a> (beginner)</li>
    <li><a href="">Car Rental</a> (intermediate)</li>
    <li><a href="">Customer Assignment</a> (intermediate)</li>
    <li><a href="">Opencast Mining</a> (intermediate)</li>
    <li><a href="">Decentralization Planning</a> (advanced)</li>
  </ul>
</details>

<details>
<summary>物流</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Price Optimization</a> (introductory)</li>
    <li><a href="">Supply Network Design</a> (beginner)</li>
    <li><a href="">Food Program</a> (beginner)</li>
    <li><a href="">Traveling Salesman</a> (advanced)</li>
  </ul>
</details>

<details>
<summary>营销</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Music Recommendation</a> (introductory)</li>
    <li><a href="">Marketing Campaign Optimization</a> (beginner)</li>
    <li><a href="">Customer Assignment</a> (intermediate)</li>
  </ul>
</details>

<details>
<summary>网络优化</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Airline Planning After Flight Disruption</a> (introductory)</li>
    <li><a href="">Food Program</a> (beginner)</li>
    <li><a href="">Supply Network Design</a> (beginner)</li>
  </ul>
</details>

<details>
<summary>运营</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Airline Planning After Flight Disruption</a> (introductory)</li>
    <li><a href="">Price Optimization</a> (introductory)</li>
    <li><a href="">Covid19 Facility Optimization</a> (beginner)</li>
    <li><a href="">Power Generation</a> (intermediate)</li>
  </ul>
</details>

<details>
<summary>投资组合管理</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Portfolio Selection Optimization</a> (advanced)</li>
    <li><a href="">Index Tracking</a> (advanced)</li>
  </ul>
</details>

<details>
<summary>生产</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Economic Planning</a> (intermediate)</li>
    <li><a href="">Efficiency Analysis</a> (intermediate)</li>
    <li><a href="">Electrical Power Generation</a> (intermediate)</li>
    <li><a href="">Factory Planning</a> (intermediate)</li>
    <li><a href="">Food Manufacturing</a> (intermediate)</li>
    <li><a href="">Mining</a> (intermediate)</li>
    <li><a href="">Power Generation</a> (intermediate)</li>
    <li><a href="">Refinery</a> (intermediate)</li>
    <li><a href="">Farm Planning</a> (advanced)</li>
  </ul>
</details>

<details>
<summary>研究</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Curve Fitting</a> (beginner)</li>
    <li><a href="">Linear Regression</a> (intermediate)</li>
    <li><a href="">Efficiency Analysis</a> (intermediate)</li>
    <li><a href="">Constraint Optimization</a> (intermediate)</li>
  </ul>
</details>

<details>
<summary>资源</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Price Optimization</a> (introductory)</li>
    <li><a href="">Economic Planning</a> (intermediate)</li>
    <li><a href="">Electrical Power Generation</a> (intermediate)</li>
    <li><a href="">Power Generation</a> (intermediate)</li>
    <li><a href="">Food Manufacturing</a> (intermediate)</li>
    <li><a href="">Farm Planning</a> (advanced)</li>
    <li><a href="">Yield Management</a> (advanced)</li>
  </ul>
</details>

<details>
<summary>路线规划</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Food Program</a> (beginner)</li>
    <li><a href="">Technician Routing and Scheduling</a> (intermediate)</li>
    <li><a href="">Lost Luggage Distribution</a> (advanced)</li>
    <li><a href="">Milk Collection</a> (advanced)</li>    
    <li><a href="">Traveling Salesman</a> (advanced)</li>
  </ul>
</details>

<details>
<summary>销售优化</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Price Optimization</a> (introductory)</li>
    <li><a href="">Marketing Campaign Optimization</a> (beginner)</li>
    <li><a href="">Customer Assignment</a> (intermediate)</li>
    <li><a href="">Food Manufacturing</a> (intermediate)</li>
  </ul>
</details>

<details>
<summary>供应链</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Market Sharing</a> (beginner)</li>
    <li><a href="">Supply Network Design</a> (beginner)</li>
    <li><a href="">Food Program</a> (beginner)</li>
    <li><a href="">Power Generation</a> (intermediate)</li>
    <li><a href="">Traveling Salesman</a> (advanced)</li>
  </ul>
</details>

<details>
<summary>分配/调度</summary>
<!--All you need is a blank line-->

  <ul>
    <li><a href="">Technician Routing and Scheduling</a> (intermediate)</li>
    <li><a href="">Manpower Planning</a> (advanced)</li>
    <li><a href="">Traveling Salesman</a> (advanced)</li>
    <li><a href="">Railway Dispatching</a> (advanced)</li>
    <li><a href="">Workforce Scheduling</a> (advanced)</li>
  </ul>
</details>


也可以在[Gurobi网站](https://www.gurobi.com/jupyter_models/)上根据难度级别和业务需求浏览这些示例。


