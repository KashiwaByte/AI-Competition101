# 常用工具概览
![image.png](https://kashiwa-pic.oss-cn-beijing.aliyuncs.com/20240310173432.png)
数据可视化可以加强感知
Matplotlib成熟但更多
Seaborn代码更精简



![image.png](https://kashiwa-pic.oss-cn-beijing.aliyuncs.com/20240310174017.png)

Scikit-learn机器学习开源库的王者，集成常用模型，同时也集成了常用的模型指标,常用的数据编码，方便模型读取。可以让我们高效解决一些细枝末节的代码。   

lightbm/xgboost/catboost：三个实用的开源boost开源项目


# 数据预处理
## 比赛数据情况
![image.png](https://kashiwa-pic.oss-cn-beijing.aliyuncs.com/20240310174736.png)

## 连续特征的预处理
![image.png](https://kashiwa-pic.oss-cn-beijing.aliyuncs.com/20240310174951.png)
1. 补充
2. 剔除
3. 归一化


## 离散特征预处理
![image.png](https://kashiwa-pic.oss-cn-beijing.aliyuncs.com/20240310175652.png)
补充缺失值：填入一些不容易重复的值


# 模型验证方式
交叉验证：能够极大地提升数据的利用率
![image.png](https://kashiwa-pic.oss-cn-beijing.aliyuncs.com/20240310175953.png)

## 交叉验证
KFold：纯随机切分
StratifiedKFold：每个fold内标签分布稳定
ShuffleSplit：设置的随机，不保证遍历所有数据
![image.png](https://kashiwa-pic.oss-cn-beijing.aliyuncs.com/20240310180339.png)
