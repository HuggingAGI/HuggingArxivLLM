# TreeLoRA: 通过分层LoRAs方法实现高效持续学习，由层次化梯度相似性树进行引导

发布时间：2025年06月12日

`LLM理论

理由：这篇论文主要探讨了在持续学习（CL）背景下，针对大型预训练模型（LPMs）提出了一种新的方法TreeLoRA。该方法通过层次化梯度相似性和稀疏梯度更新，优化了模型在多任务环境中的学习效率和性能。论文不仅提供了理论分析，还通过实验验证了其有效性。因此，它属于LLM的理论研究范畴，专注于模型优化和训练策略。` `计算机视觉`

> TreeLoRA: Efficient Continual Learning via Layer-Wise LoRAs Guided by a Hierarchical Gradient-Similarity Tree

# 摘要

> 现实世界中许多应用程序在流数据环境中运行，学习任务依次出现。为适应新任务同时保留过去知识，持续学习（CL）必不可少，以防止灾难性遗忘。如今，随着大型预训练模型（LPMs）的兴起，其巨大的计算需求和参数规模使持续学习的效率变得至关重要。

本文提出TreeLoRA（基于K-D树的低秩适配器），一种通过层次化梯度相似性构建分层适配器的新方法，尤其适合LPMs的高效持续学习。为降低任务相似性估计的计算负担，我们采用强盗算法，基于下限置信度开发了一种高效探索任务结构的算法。此外，稀疏梯度更新的引入促进了参数优化，使该方法更适用于LPMs。

理论分析证明了我们方法的合理性。实验结果表明，TreeLoRA在视觉变压器（ViTs）和大型语言模型（LLMs）上均表现出色，适用于视觉和自然语言处理等多种任务。
    

> Many real-world applications collect data in a streaming environment, where learning tasks are encountered sequentially. This necessitates continual learning (CL) to update models online, enabling adaptation to new tasks while preserving past knowledge to prevent catastrophic forgetting. Nowadays, with the flourish of large pre-trained models (LPMs), efficiency has become increasingly critical for CL, due to their substantial computational demands and growing parameter sizes. In this paper, we introduce TreeLoRA (K-D Tree of Low-Rank Adapters), a novel approach that constructs layer-wise adapters by leveraging hierarchical gradient similarity to enable efficient CL, particularly for LPMs. To reduce the computational burden of task similarity estimation, we employ bandit techniques to develop an algorithm based on lower confidence bounds to efficiently explore the task structure. Furthermore, we use sparse gradient updates to facilitate parameter optimization, making the approach better suited for LPMs. Theoretical analysis is provided to justify the rationale behind our approach, and experiments on both vision transformers (ViTs) and large language models (LLMs) demonstrate the effectiveness and efficiency of our approach across various domains, including vision and natural language processing tasks.

[Arxiv](https://arxiv.org/abs/2506.10355)