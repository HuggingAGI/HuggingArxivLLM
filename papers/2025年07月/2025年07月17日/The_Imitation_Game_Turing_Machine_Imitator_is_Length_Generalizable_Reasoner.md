# 模仿游戏：图灵机模仿者是长度泛化推理器

发布时间：2025年07月17日

`LLM理论

摘要讨论了大型语言模型在处理长序列时的长度泛化能力，并提出了一种新的方法TAIL，旨在通过模拟图灵机的执行过程来提升模型的推理能力。这属于LLM理论层面的研究，专注于模型的改进和机制分析。` `人工智能` `计算机科学`

> The Imitation Game: Turing Machine Imitator is Length Generalizable Reasoner

# 摘要

> 解决比训练中遇到的序列更长的问题，即长度泛化能力，是基于Transformer的大型语言模型（LLM）面临的核心挑战。现有研究多聚焦于算术和符号操作任务的数据驱动方法，但这些方法往往局限于特定任务，整体效果有限。为寻求更通用的解决方案，本文将研究范围扩展至更广泛的可计算推理问题，即那些算法能够解决、因而图灵机也能处理的问题。从这一视角出发，我们提出了图灵机模仿学习（TAIL），旨在提升LLMs的长度泛化能力。TAIL通过计算机程序模拟图灵机的执行过程，将推理步骤分解为原子状态，以避免捷径学习，并借助显式内存机制降低基本操作中动态和长距离数据访问的难度。为了验证TAIL的可靠性和通用性，我们构建了一个涵盖8类算法和18项任务的具有挑战性的合成数据集。无需额外复杂机制，TAIL仅通过合成数据显著提升了Qwen2.5-7B在各种任务上的长度泛化能力和性能，超越了之前的方法和DeepSeek-R1。实验结果表明，TAIL实现长度泛化的关键在于图灵机的核心概念，而非特定的思考方式，模型在注意力层展现出与图灵机特性一致的读写行为。这项研究为未来从合成数据学习LLM推理提供了有前景的研究方向。

> Length generalization, the ability to solve problems of longer sequences than those observed during training, poses a core challenge of Transformer-based large language models (LLM). Although existing studies have predominantly focused on data-driven approaches for arithmetic operations and symbolic manipulation tasks, these approaches tend to be task-specific with limited overall performance. To pursue a more general solution, this paper focuses on a broader case of reasoning problems that are computable, i.e., problems that algorithms can solve, thus can be solved by the Turing Machine. From this perspective, this paper proposes Turing MAchine Imitation Learning (TAIL) to improve the length generalization ability of LLMs. TAIL synthesizes chain-of-thoughts (CoT) data that imitate the execution process of a Turing Machine by computer programs, which linearly expands the reasoning steps into atomic states to alleviate shortcut learning and explicit memory fetch mechanism to reduce the difficulties of dynamic and long-range data access in elementary operations. To validate the reliability and universality of TAIL, we construct a challenging synthetic dataset covering 8 classes of algorithms and 18 tasks. Without bells and whistles, TAIL significantly improves the length generalization ability as well as the performance of Qwen2.5-7B on various tasks using only synthetic data, surpassing previous methods and DeepSeek-R1. The experimental results reveal that the key concepts in the Turing Machine, instead of the thinking styles, are indispensable for TAIL for length generalization, through which the model exhibits read-and-write behaviors consistent with the properties of the Turing Machine in their attention layers. This work provides a promising direction for future research in the learning of LLM reasoning from synthetic data.

[Arxiv](https://arxiv.org/abs/2507.13332)