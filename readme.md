# 目录

**简单说明**: 

- 这里会记录一些我平时所学的和平时所做的实验, 尽量所有的都以notebook的形式上传, 看起来更加方便. 
- 我建议可以按照这篇文章[机器学习文章总结](https://mathpretty.com/10388.html)来进行看. 基本这里每一个代码我都有相应的, 详细的文章进行介绍.
- (我最初的想法是这里记录原始的, 或是精简过的notebook, 详细的说明在[文艺数学君](https://mathpretty.com/)上进行说明. 想看代码再来这个仓库进行查看)


## Tools

- Python生成词云
- Python生成字符画

## 2019_03_17

- PyTorch实现简单分类
- PyTorch实现CNN, Dogs vs. Cats
- Pytorch维度的理解
- PyTorch对交叉熵的理解(CrossEntropy)

## 2019_03_24

- 模型可视化-Netron
- 残差网络举例, 使用Pytorch训练-验证-测试Resnet50
- 论文介绍 : Decision-based boundary attack

## 2019_04_14

- 正则化技术的介绍
- 交叉检验技术的介绍(CV)

## 2019_04_21

- Pytorch在MNIST实现分类(简单演示)
- Pytorch在MNIST实现分类(动态增加层数,便于之后调试)

## 2019_04_29

- PyTorch实现逻辑回归
- 包含逻辑回归的PPT和代码实现和使用的数据

## 2019_05_27

- CNN的介绍
- Convolution的一些可解释性
- deep dream的实现


## 2019_06_03

- Image Style Transform(图片的风格迁移)
- CNN_MNIST可视化

## 2019_06_10

- Fizz Buzz in Pytorch
- CLASSIFYING NAMES WITH A CHARACTER-LEVEL RNN
- 时间序列分析(使用RNN完成时间序列预测)

## 2019_06_17

- Seq2Seq - translation(一个简单的Seq2Seq的模型，用来实现英文与法文的翻译。)

## 2019_06_24

- Emotion RNN(使用RNN完成简单的情感分类)
- Word Embedding(简单实现Skip-gram算法)

## 2019_07_01

- Attention的简单介绍


## 2019_07_08

- Saliency Maps的简单实现
- LIME与Pytorch的结合使用
- SHAP与Pytorch的结合使用

## 2019_07_15

- GAN生成服从高斯分布的数据
- GAN生成手写数字


## 2019_08_12

- Factor Analysis(因子分析)
- Principal component analysis, PCA(主成分分析)

## 2019_08_26

- 分类器边界的可视化方式.


## 2019_09_09

- 关于GAN的内容学习
  - WGAN-GP

## 2019_11_18

- 关于AutoEncoder的内容学习
  - AE

## 2019_12_16

- 推荐系统
  - 基于矩阵分解的推荐系统, FunkSVD

## 2020_04_06

因为最近在使用Colaboratory, 但是直接传图片, 进行训练会很慢. 所以在这里考虑将图片处理好打包为npy文件上传.

这里包含两个文件, 分别是生成将图片生成npy文件, 以及使用生成的进行测试.

- Npy文件生成 (如何将图片生成对应的npy文件和label的npy文件)
- Npy文件训练 (这一部分使用Colaboratory进行测试)

## 2020_04_06

这个文件夹开始介绍强化学习的相关内容. 
目前这个文件夹还在持续更新. 

- 环境介绍
    - 05_Windy_Gridworld_Playground.ipynb (环境Windy Gridworld Playground的介绍);
- On Policy Learning介绍
    - MC
        - 05_GLIE_BlackJack.ipynb (使用MC方法来优化策略, 使用GLIE算法, 给出最优策略, 用在BlackJack上面);
        - 05_GLIE_Windy_Gridworld.ipynb (使用MC方法, 解决Windy Gridworld上面);
    - TD
        - 05_Sarsa_Windy_Gridworld.ipynb (使用最基础的Sarsa算法, 在windy gridworld中寻找最优路径);
        - 05_Sarsa_Lambda_Windy_Gridworld.ipynb (使用Sarsa($\lambda$)方法, 也就是使用eligibility traces);
- Off Policy Learning介绍
    - MC
        - 05_Importance_Sampling_Random_MC_Windy_Gridworld.ipynb (使用MC+OFF policy的方式, 但是没有收敛)
    - TD
        - 05_Importance_Sampling_Random_TD_Windy_Gridworld.ipynb (使用importance sampling, 并且执行的policy为随机policy, 即每个action执行的概率相同)
        - 05_Importance_Sampling_TD_Q-Learning_Windy_Gridworld.ipynb (q-learning简化前的版本, 此时可以看到有行为策略, 和优化策略)
        - 05_Q-Learning_Windy_Gridworld.ipynb (q-learning介绍)
        - 05_Importance_Sampling_2-step-Q-Learning_Windy_Gridworld.ipynb (使用2-step, 此时要加importance sampling, 测试权重加在不同位置的效果)
        - 05_Importance_Sampling_3-step-Q-Learning_Windy_Gridworld.ipynb (使用3-step, 此时要加importance sampling, 测试权重加在不同位置的效果)

## 2020_06_29

因为之前一直在看RL的内容, 所以都放在了一个文件夹. 
这里单独列出一些零散的知识. 

- importance sampling的介绍.