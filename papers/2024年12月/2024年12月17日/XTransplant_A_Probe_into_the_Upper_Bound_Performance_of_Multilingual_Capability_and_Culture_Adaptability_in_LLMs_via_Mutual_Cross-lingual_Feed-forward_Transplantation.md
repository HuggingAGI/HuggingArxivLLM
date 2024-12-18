# XTransplant：借由相互跨语言前馈移植探索大型语言模型中多语言能力与文化适应性的上限表现

发布时间：2024年12月17日

`LLM应用` `语言模型` `多语言处理`

> XTransplant: A Probe into the Upper Bound Performance of Multilingual Capability and Culture Adaptability in LLMs via Mutual Cross-lingual Feed-forward Transplantation

# 摘要

> 当前的大型语言模型（LLMs）在多语言能力和文化适应性方面常显失衡，很大程度上归因于其以英语为核心的预训练数据。为化解这一失衡状况，我们提出了一种叫 XTransplant 的探测方法，它在推理阶段借助跨语言前馈移植来探寻跨语言潜在交互，以期让模型能发挥英语和非英语语言的长处。通过大量的试点实验，我们实证表明，LLMs 的多语言能力和文化适应性，分别从 En -> non-En 和 non-En -> En 方向，都有通过 XTransplant 显著提升的可能，凸显了当前 LLMs 多语言潜力的未充分利用。而且这些试点实验中观察到的模式进一步催生了离线缩放推理策略，该策略在多语言和文化感知任务中展现出持续的性能提升，有时甚至超越了多语言监督微调。我们也真心希望我们的进一步分析和讨论能助力更深入地洞察 XTransplant 机制。

> Current large language models (LLMs) often exhibit imbalances in multilingual capabilities and cultural adaptability, largely due to their English-centric pretraining data. To address this imbalance, we propose a probing method named XTransplant that explores cross-lingual latent interactions via cross-lingual feed-forward transplantation during inference stage, with the hope of enabling the model to leverage the strengths of both English and non-English languages. Through extensive pilot experiments, we empirically prove that both the multilingual capabilities and cultural adaptability of LLMs hold the potential to be significantly improved by XTransplant, respectively from En -> non-En and non-En -> En, highlighting the underutilization of current LLMs' multilingual potential. And the patterns observed in these pilot experiments further motivate an offline scaling inference strategy, which demonstrates consistent performance improvements in multilingual and culture-aware tasks, sometimes even surpassing multilingual supervised fine-tuning. And we do hope our further analysis and discussion could help gain deeper insights into XTransplant mechanism.

[Arxiv](https://arxiv.org/abs/2412.12686)