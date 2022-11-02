## bagging = bootstrap aggregating
在不同数据上独立训练多个同样的模型（学到的参数不同），最终结果取平均或投票
bootatrap: 放回的随机取样
## 原理
在不增加bias的情况下降低variance，非常适合GPU并行
## 适用范围
不稳定的模型，比如决策树
对于稳定的模型没有效果
![alt](../pic/chapter_model_combination/bagging.png)