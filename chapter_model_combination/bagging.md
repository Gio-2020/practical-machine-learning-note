## bagging = bootstrap aggregating
训练多个独立的模型，最终结果取平均或投票
bootatrap: 放回的随机取样
## 原理
在不增加bias的情况下降低variance
## 适用范围
不稳定的模型，比如决策树
对于稳定的模型没有效果
![alt](../pic/chapter_model_combination/bagging.png)