# # Shop-R1：利用强化学习引导大型语言模型模拟在线购物中的真实用户行为

发布时间：2025年07月23日

`LLM应用

理由：这篇论文提出了一种新的强化学习框架，用于提升大型语言模型在模拟人类行为方面的应用能力，具体是在在线购物环境中。研究的重点在于如何应用LLMs到特定任务中，并通过强化学习改进其表现，属于LLM应用的范畴。` `电子商务`

> Shop-R1: Rewarding LLMs to Simulate Human Behavior in Online Shopping via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）近期在模拟可信人类行为方面展现出强大潜力，尤其是在网络环境中。此前研究通过LLM合成推理依据增强训练数据，并利用监督微调（SFT）提升推理能力，从而改善下游动作预测。然而，这些方法的性能受限于生成推理依据模型的推理能力。本文提出了一种新型强化学习（RL）框架Shop-R1，旨在提升LLMs的推理能力，以更真实地模拟在线购物环境中的人类行为。具体而言，Shop-R1将人类行为模拟任务分为两个阶段：推理依据生成和动作预测，每个阶段由不同奖励信号引导。在推理依据生成阶段，我们利用内部模型信号（如logit分布）以自监督方式引导推理过程。在动作预测阶段，我们提出一种分层奖励结构，带有难度感知缩放机制，防止奖励欺骗并实现精细奖励分配。该设计同时评估高层次动作类型和细粒度子动作细节（属性和值）的正确性，并根据难度按比例奖励输出。实验结果表明，与基线相比，我们的方法实现了超过65%的相对提升。

> Large Language Models (LLMs) have recently demonstrated strong potential in generating 'believable human-like' behavior in web environments. Prior work has explored augmenting training data with LLM-synthesized rationales and applying supervised fine-tuning (SFT) to enhance reasoning ability, which in turn can improve downstream action prediction. However, the performance of such approaches remains inherently bounded by the reasoning capabilities of the model used to generate the rationales. In this paper, we introduce Shop-R1, a novel reinforcement learning (RL) framework aimed at enhancing the reasoning ability of LLMs for simulation of real human behavior in online shopping environments Specifically, Shop-R1 decomposes the human behavior simulation task into two stages: rationale generation and action prediction, each guided by distinct reward signals. For rationale generation, we leverage internal model signals (e.g., logit distributions) to guide the reasoning process in a self-supervised manner. For action prediction, we propose a hierarchical reward structure with difficulty-aware scaling to prevent reward hacking and enable fine-grained reward assignment. This design evaluates both high-level action types and the correctness of fine-grained sub-action details (attributes and values), rewarding outputs proportionally to their difficulty. Experimental results show that our method achieves a relative improvement of over 65% compared to the baseline.

[Arxiv](https://arxiv.org/abs/2507.17842)