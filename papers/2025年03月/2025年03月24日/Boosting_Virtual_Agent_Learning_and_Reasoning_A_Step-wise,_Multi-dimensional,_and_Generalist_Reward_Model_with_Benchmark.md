# 助力虚拟代理学习与推理：一种逐步、多维、通用的奖励模型及基准

发布时间：2025年03月24日

`Agent` `虚拟代理` `通用人工智能`

> Boosting Virtual Agent Learning and Reasoning: A Step-wise, Multi-dimensional, and Generalist Reward Model with Benchmark

# 摘要

> 基于多模态大型语言模型（MLLMs）的通用虚拟代理（GVAs）在自主任务执行方面展现出巨大潜力。然而，当前训练范式存在两大关键局限：依赖结果监督和需要大量人工标注。为突破这些限制，我们提出了Similar——一种逐步多维通用奖励模型。它不仅为代理训练提供精细信号，还能在推理时选择更优动作进行扩展。具体而言，我们首先系统性地界定了评估代理行为的五个维度。在此基础上，我们设计了MCTS-P算法，用于自动收集和标注逐步、五维的代理执行数据。借助这些数据，我们采用Triple-M策略训练Similar。此外，我们还推出了虚拟代理领域首个针对逐步多维奖励模型训练与评估的基准测试，命名为SRM。该基准包含两个部分：作为Similar训练集的SRMTrain，以及作为手动精选测试集的SRMEval，用于评估奖励模型。实验结果表明，Similar通过其逐步多维评估和协同增益，在训练和推理扩展过程中为GVAs提供了有效的中间信号。代码可在https://github.com/Galery23/Similar-v1获取。

> The development of Generalist Virtual Agents (GVAs) powered by Multimodal Large Language Models (MLLMs) has shown significant promise in autonomous task execution. However, current training paradigms face critical limitations, including reliance on outcome supervision and labor-intensive human annotations. To address these challenges, we propose Similar, a Step-wise Multi-dimensional Generalist Reward Model, which offers fine-grained signals for agent training and can choose better action for inference-time scaling. Specifically, we begin by systematically defining five dimensions for evaluating agent actions. Building on this framework, we design an MCTS-P algorithm to automatically collect and annotate step-wise, five-dimensional agent execution data. Using this data, we train Similar with the Triple-M strategy. Furthermore, we introduce the first benchmark in the virtual agent domain for step-wise, multi-dimensional reward model training and evaluation, named SRM. This benchmark consists of two components: SRMTrain, which serves as the training set for Similar, and SRMEval, a manually selected test set for evaluating the reward model. Experimental results demonstrate that Similar, through its step-wise, multi-dimensional assessment and synergistic gain, provides GVAs with effective intermediate signals during both training and inference-time scaling. The code is available at https://github.com/Galery23/Similar-v1.

[Arxiv](https://arxiv.org/abs/2503.18665)