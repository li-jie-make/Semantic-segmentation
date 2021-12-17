# Semantic-segmentation
飞桨常规赛：遥感影像地块分割 - 11月第3名方案
# 1、代码内容说明

* main.ipynb文件为训练、测试、推理的代码文件。
* 配置文件再/home/aistudio/config文件夹下

# 2、模型构建思路及调优过程

* 模型使用paddleseg中的SegFormer_B3网络
* 数据集划分，训练集、测试机比例8：2
* 训练轮数160000iters
* 160000的checkpoint在线测试精度64.06232，提交时未保留checkpoint
