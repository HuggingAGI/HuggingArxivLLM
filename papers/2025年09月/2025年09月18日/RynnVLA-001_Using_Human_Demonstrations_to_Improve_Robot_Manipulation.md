# RynnVLA-001：借助人类示范提升机器人操作能力

发布时间：2025年09月18日

`Agent` `工业与制造`

> RynnVLA-001: Using Human Demonstrations to Improve Robot Manipulation

# 摘要

> 本文提出RynnVLA-001——一种基于人类演示的大规模视频生成预训练构建的视觉-语言-动作（VLA）模型。我们设计了新颖的两阶段预训练方法：第一阶段为“以自我为中心的视频生成预训练”，在1200万段以自我为中心的操作视频上训练图像到视频模型，使其能根据初始帧和语言指令预测未来帧；第二阶段为“以人为中心的轨迹感知建模”，通过联合预测未来关键点轨迹对其进行扩展，从而有效连接视觉帧预测与动作预测。此外，为增强动作表示，我们提出ActionVAE——一种变分自编码器，能将动作序列压缩为紧凑的潜在嵌入，降低VLA输出空间的复杂度。在相同的下游机器人数据集上微调后，RynnVLA-001的性能超越了当前最先进的基线模型，这表明所提出的预训练策略能为VLA模型提供更有效的初始化。

> This paper presents RynnVLA-001, a vision-language-action(VLA) model built upon large-scale video generative pretraining from human demonstrations. We propose a novel two-stage pretraining methodology. The first stage, Ego-Centric Video Generative Pretraining, trains an Image-to-Video model on 12M ego-centric manipulation videos to predict future frames conditioned on an initial frame and a language instruction. The second stage, Human-Centric Trajectory-Aware Modeling, extends this by jointly predicting future keypoint trajectories, thereby effectively bridging visual frame prediction with action prediction. Furthermore, to enhance action representation, we propose ActionVAE, a variational autoencoder that compresses sequences of actions into compact latent embeddings, reducing the complexity of the VLA output space. When finetuned on the same downstream robotics datasets, RynnVLA-001 achieves superior performance over state-of-the-art baselines, demonstrating that the proposed pretraining strategy provides a more effective initialization for VLA models.

[Arxiv](https://arxiv.org/abs/2509.15212)