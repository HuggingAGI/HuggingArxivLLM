# 基于 LLM 的时变图信号在线预测

发布时间：2024年10月24日

`LLM应用` `图信号处理` `气象预测`

> LLM-based Online Prediction of Time-varying Graph Signals

# 摘要

> 在本文中，我们提出了一个全新的框架，借助大型语言模型（LLMs），利用时空平滑性来预测时变图信号中的缺失值。我们发挥LLM的优势实现了消息传递方案。对于每个缺失节点，将其邻居和先前的估计值输入LLM进行处理，以推断缺失的观测值。在风速图信号的在线预测任务中进行测试，我们的模型在准确性上超越了在线图滤波算法，彰显了LLMs在有效处理图中部分观测信号方面的潜力。

> In this paper, we propose a novel framework that leverages large language models (LLMs) for predicting missing values in time-varying graph signals by exploiting spatial and temporal smoothness. We leverage the power of LLM to achieve a message-passing scheme. For each missing node, its neighbors and previous estimates are fed into and processed by LLM to infer the missing observations. Tested on the task of the online prediction of wind-speed graph signals, our model outperforms online graph filtering algorithms in terms of accuracy, demonstrating the potential of LLMs in effectively addressing partially observed signals in graphs.

[Arxiv](https://arxiv.org/abs/2410.18718)