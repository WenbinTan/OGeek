# OGeek Contest
OGeek算法挑战赛
数据集地址: https://tianchi.aliyun.com/competition/information.htm?spm=5176.100067.5678.2.510271eexsk52S&raceId=231688

## 程序目录（填坑ing）
* OGeekDataParser 用于解析官方所给数据集，并提供读写接口[9.28]
* Sentence2Vec    用于根据现有语料将所给句子转化为词嵌入向量矩阵[10.1]
* Tag_Split       用于创建一个小训练集，减少转化时间[10.3]

## 引用
* 词库来源 - 苏剑林 Github地址: https://github.com/bojone
* 词库下载 - 链接:https://pan.baidu.com/s/1cz0vtOBOtgxsgnl_RY7QZg  密码:ivqv

## 备注
* Sentence2Vec在将数据转换成句向量后，整一个训练集大概为52GB的内容，推荐用Tag_Split做一个合适的小训练集进行训练
* __开始搞特征模型了,如果BaseLine OK的话10号后放上来，停更一段__ [10.4]
* 目前最高F1_score[0.76] By * Algorithm[10.8]






