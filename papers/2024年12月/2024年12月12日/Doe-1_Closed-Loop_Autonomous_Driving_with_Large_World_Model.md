# Doe-1：具备大型世界模型的闭环自动驾驶

发布时间：2024年12月12日

`其他` `自动驾驶`

> Doe-1: Closed-Loop Autonomous Driving with Large World Model

# 摘要

> 端到端自动驾驶因具备从海量数据中学习的潜力，受到的关注与日俱增。然而，现有的多数方法仍为开环模式，存在可扩展性差、高阶交互缺失以及决策效率低下等问题。本文探索了一种自动驾驶的闭环框架，并提出大型驾驶世界模型（Doe-1）用于统一感知、预测和规划。我们将自动驾驶定义为下一个标记生成问题，利用多模态标记完成不同任务。具体而言，我们用自由格式文本（即场景描述）进行感知，用图像标记直接在 RGB 空间生成未来预测。在规划方面，我们采用位置感知标记器将动作有效编码为离散标记。我们训练了一个多模态转换器，以端到端且统一的方式自动回归生成感知、预测和规划标记。在广泛使用的 nuScenes 数据集上的实验表明，Doe-1 在包括视觉问答、动作条件视频生成和运动规划等各类任务中均有效。代码：https://github.com/wzzheng/Doe。

> End-to-end autonomous driving has received increasing attention due to its potential to learn from large amounts of data. However, most existing methods are still open-loop and suffer from weak scalability, lack of high-order interactions, and inefficient decision-making. In this paper, we explore a closed-loop framework for autonomous driving and propose a large Driving wOrld modEl (Doe-1) for unified perception, prediction, and planning. We formulate autonomous driving as a next-token generation problem and use multi-modal tokens to accomplish different tasks. Specifically, we use free-form texts (i.e., scene descriptions) for perception and generate future predictions directly in the RGB space with image tokens. For planning, we employ a position-aware tokenizer to effectively encode action into discrete tokens. We train a multi-modal transformer to autoregressively generate perception, prediction, and planning tokens in an end-to-end and unified manner. Experiments on the widely used nuScenes dataset demonstrate the effectiveness of Doe-1 in various tasks including visual question-answering, action-conditioned video generation, and motion planning. Code: https://github.com/wzzheng/Doe.

[Arxiv](https://arxiv.org/abs/2412.09627)