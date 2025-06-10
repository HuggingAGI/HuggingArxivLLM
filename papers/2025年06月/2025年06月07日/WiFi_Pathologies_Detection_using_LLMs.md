# # 基于 LLMs 的 WiFi 异常检测
利用大型语言模型 (LLMs) 进行 WiFi 异常检测。

发布时间：2025年06月07日

`LLM应用` `异常检测`

> WiFi Pathologies Detection using LLMs

# 摘要

> 本文中，我们对编码器和解码器模型进行微调，用于检测WiFi网络（即IEEE 802.11网络）中的异常。我们采用手动设计提示词并进行微调的方法。实验结果表明，序列模型在标注数据上实现了高检测精度，而因果模型在未标注数据上表现同样优异。

> In this paper, we fine-tune encoder-only and decoder-only large language models (LLMs) to detect pathologies in IEEE 802.11 networks, commonly known as WiFi. Our approach involves manually crafting prompts followed by fine-tuning. Evaluations show that the sequential model achieves high detection accuracy using labeled data, while the causal model performs equally well for unlabeled data.

[Arxiv](https://arxiv.org/abs/2506.06943)