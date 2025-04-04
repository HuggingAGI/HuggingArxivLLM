# 并行市场环境，为FinRL竞赛而设计

发布时间：2025年04月03日

`Agent`

> Parallel Market Environments for FinRL Contests

# 摘要

> 强化学习在金融领域展现出巨大潜力，为此我们组织了2023-2025年的FinRL竞赛，涵盖多种金融任务。大型语言模型在处理金融文本方面表现出色，而将LLM生成的信号整合到FinRL中是一项创新任务，使代理能够同时利用结构化市场数据和非结构化金融文本。为解决训练中的采样瓶颈，我们引入了基于GPU的并行市场环境以提升采样速度。本文总结了在2023-2025年FinRL竞赛中使用的并行市场环境。两个新环境整合了LLM生成的信号，并支持大规模并行模拟。参赛者利用这些环境训练代理，用于股票和加密货币交易任务。

> Reinforcement learning has shown great potential in finance. We have organized the FinRL Contests 2023-2025 featuring different financial tasks. Large language models have a strong capability to process financial texts. Integrating LLM-generated signals into FinRL is a new task, enabling agents to use both structured market data and unstructured financial text. To address the sampling bottleneck during training, we introduce GPU-based parallel market environments to improve sampling speed. In this paper, we summarize the parallel market environments used in FinRL Contests 2023-2025. Two new environments incorporate LLM-generated signals and support massively parallel simulation. Contestants utilize these environments to train agents for stock and cryptocurrency trading tasks.

[Arxiv](https://arxiv.org/abs/2504.02281)