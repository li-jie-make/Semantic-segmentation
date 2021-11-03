# Semantic-segmentation
飞桨常规赛：遥感影像地块分割 - 10月第6名方案
# 1、代码内容说明

* train.ipynb文件为训练、测试、推理的代码文件。
* 配置文件再/home/aistudio/config文件夹下

# 2、模型构建思路及调优过程

* 模型使用paddleseg中的segformer网络
* 数据集划分，训练集、测试机比例8：2
* 训练轮数24000iters
* 24000的checkpoint在线测试精度57.40718，提交时未保留checkpoint
