# PKU-Database-Project-5

单人小组从任务一、任务二中选择一个，从任务三、任务四和任务五中选择一个完成；其他小组同时完成任务一和任务二，从任务三、四、五中选择一个完成。所有任务都可以通过询问大模型来得到参考SQL代码。
## 任务一：针对movielen数据集的分析查询

1.	列出平均得分前10的电影。
2.	列出每个类型的平均得分前10的电影
3.	列出每个用户综合评价排在前5的电影类型
4.	列出每个用户观影次数排在前5的电影类型

## 任务二：SQL中的滑动窗口
给定一只股票的日线收盘价数据，计算金叉（也即5日线上穿10日线）出现的位置。我们给了三个公司google、apple，tesla的股票数据集。

**下面的三个任务基于“世界幸福指数数据集”，各字段含义见文档说明。**

## 任务三：基于SQL的多元线性回归
定义如下幸福指数数据表`happyness(Overall_rank, Country, Score, GDP_per_capita, Social_support, Healthy_life_expectancy, Freedom_to_make_life_choices, Generosity, Perceptions_of_corruption)`。请以`score`作为因变量，`GDP_per_capita`, `Social_support`,   `Healthy_life_expectancy`, `Freedom_to_make_life_choices`, `Generosity`, `Perceptions_of_corruption`作为自变量，用SQL完成多元线性回归算法。

## 任务四：基于SQL的决策树
定义如下幸福指数数据表`happyness(Overall_rank, Country, Score, GDP_per_capita, Social_support, Healthy_life_expectancy , Freedom_to_make_life_choices,  Generosity, Perceptions_of_corruption)`，`score`被划分为high, middle, low三个类别（这个请自己选择划分区间）。请以`score`作为分类属性，用SQL完成决策树分类算法。

## 任务五：基于SQL的聚类
定义如下幸福指数数据表`happyness(Overall_rank, Country, Score, GDP_per_capita,	Social_support, Healthy_life_expectancy, Freedom_to_make_life_choices	, Generosity, Perceptions_of_corruption)`。请选择属性`Score`, `GDP_per_capita`, `Social_support`, `Healthy_life_expectancy`, `Freedom_to_make_life_choices`, `Generosity`, `Perceptions_of_corruption`，对它们进行归一化处理，并用归一化之后的结果来计算样本之间的距离，用SQL完成 $k$-means算法，指定 $k=3$。
