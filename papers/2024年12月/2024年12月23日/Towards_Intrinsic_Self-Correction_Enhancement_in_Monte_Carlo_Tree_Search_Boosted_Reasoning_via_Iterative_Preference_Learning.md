# 通过迭代偏好学习，在蒙特卡罗树搜索助力的推理中实现内在的自我校正增强

发布时间：2024年12月23日

`LLM应用` `语言模型`

> Towards Intrinsic Self-Correction Enhancement in Monte Carlo Tree Search Boosted Reasoning via Iterative Preference Learning

# 摘要

> 当前，有一些最先进的方法旨在通过受 AlphaZero 启发的迭代偏好学习来提升大型语言模型（LLMs）的推理能力，在此基础上，我们提议通过内在的自我校正在一定程度上进一步增强逐步推理能力。我们的工作借助逐步偏好学习，通过强化学习来强化自我验证。最初，我们通过一个两阶段的训练程序开展工作。在第一阶段，LLM 的自我校正推理能力借助其自身的预测得以增强，在一定程度上完全依赖内在自我校正中的自生成数据。在第二阶段，应用第一阶段实现的增强的自我校正策略来利用基线逐步偏好学习。在算术推理任务的评估中，我们的方法比 OpenMath2-Llama3.1-8B、dart-math-mistral-7b-uniform 在 MATH 上的准确率分别提高到 71.34％（+4.18％）和 48.06％（+4.94％），比 LLama-3.1-8B-Instruct、Mistral-7B-Instruct-v0.1 在 GSM8K 上的准确率分别提高到 86.76％（+2.00％）和 38.06％（+2.28％）。

> With current state-of-the-art approaches aimed at enhancing the reasoning capabilities of Large Language Models(LLMs) through iterative preference learning inspired by AlphaZero, we propose to further enhance the step-wise reasoning capabilities through intrinsic self-correction to some extent. Our work leverages step-wise preference learning to enhance self-verification via reinforcement learning. We initially conduct our work through a two-stage training procedure. At the first stage, the self-correction reasoning ability of an LLM is enhanced through its own predictions, relying entirely on self-generated data within the intrinsic self-correction to some extent. At the second stage, the baseline step-wise preference learning is leveraged via the application of the enhanced self-correct policy achieved at the first stage. In the evaluation of arithmetic reasoning tasks, our approach outperforms OpenMath2-Llama3.1-8B, dart-math-mistral-7b-uniform on MATH with increases in accuracy to 71.34%(+4.18%) and 48.06%(+4.94%) and LLama-3.1-8B-Instruct, Mistral-7B-Instruct-v0.1 on GSM8K with increases in accuracy to 86.76%(+2.00%) and 38.06%(+2.28%).

[Arxiv](https://arxiv.org/abs/2412.17397)