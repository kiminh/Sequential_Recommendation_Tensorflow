# Sequential_Recommendation_Tensorflow
Several sequential recommended models implemented by tenosrlfow1.x

## 简介
基于Tensorflow自己动手实现的一些序列化推荐模型，有些模型别人实现过了，作为学习，还是对每个模型用最简单的方式亲自实现了一下。

目前实现模型，FPMC，Caser，AttRec，TransRec，GRU4Rec

## 目录结构

## 使用说明

进入models目录下运行run_Model.py即可

## 模型实验

实验数据集: moivelens-1m

| 模型    | 方法    | 损失函数| HR@50 | MRR|
| ------ | ------ | ------ | ------ |-----|
| AttRec | 基于self-Attetion和 MF   |  margin-hingeloss      |    0.4727    |  0.0926   |
| Caser |  CNN捕捉用户序列信息   |  交叉熵      |     0.4997   |   0.1025  |
| GRU4Rec | 利用CRU对用户序列建模   |  BPR/TOP1      |     -   |   -  |
| FPMC | MF + 因子分解的个性化MC  |  S-BPR    |    -    |  -   |
| TransRec | - |  S-BPR      |   -     |   -  |

___



--
