# 潜在奖励：LLM驱动的片段式强化学习信用分配

发布时间：2024年12月15日

`Agent

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来改进强化学习（RL）中的信用分配问题，提出了一个基于LLM的符号决策框架LaRe。该框架通过LLM生成的语义代码来弥合语言知识与符号潜在奖励之间的鸿沟，并设计了潜在奖励自我验证机制以提升LLM推理的稳定性和可靠性。这些内容主要涉及如何将LLM应用于强化学习中的代理（Agent）决策过程，因此将其分类为Agent。` `决策系统`

> Latent Reward: LLM-Empowered Credit Assignment in Episodic Reinforcement Learning

# 摘要

> # 摘要
强化学习（RL）在现实应用中常面临反馈延迟和稀疏的问题，即便只有阶段性奖励。以往的方法在奖励重新分配和信用分配上有所进展，但仍面临冗余导致的训练困难和任务绩效评估多面性带来的模糊归因等挑战。幸运的是，大型语言模型（LLM）蕴含丰富的决策知识，为奖励重新分配提供了有力工具。然而，由于语言知识与符号形式要求的不匹配，以及推理中的随机性和幻觉，直接部署LLM并非易事。为此，我们提出了LaRe，一种基于LLM的符号决策框架，旨在改进信用分配。LaRe的核心是潜在奖励概念，它通过多维绩效评估，从多角度实现目标达成，并促进更有效的奖励重新分配。我们发现，LLM生成的语义代码能够弥合语言知识与符号潜在奖励之间的鸿沟，因为它可执行符号对象。同时，我们设计了潜在奖励自我验证机制，以提升LLM推理的稳定性和可靠性。理论上，潜在奖励中与奖励无关的冗余消除有助于通过更准确的奖励估计提升RL性能。大量实验结果表明，LaRe（i）在时间信用分配上优于现有方法，（ii）在多代理贡献分配上表现出色，（iii）在某些任务中甚至优于使用真实奖励训练的策略。

> Reinforcement learning (RL) often encounters delayed and sparse feedback in real-world applications, even with only episodic rewards. Previous approaches have made some progress in reward redistribution for credit assignment but still face challenges, including training difficulties due to redundancy and ambiguous attributions stemming from overlooking the multifaceted nature of mission performance evaluation. Hopefully, Large Language Model (LLM) encompasses fruitful decision-making knowledge and provides a plausible tool for reward redistribution. Even so, deploying LLM in this case is non-trivial due to the misalignment between linguistic knowledge and the symbolic form requirement, together with inherent randomness and hallucinations in inference. To tackle these issues, we introduce LaRe, a novel LLM-empowered symbolic-based decision-making framework, to improve credit assignment. Key to LaRe is the concept of the Latent Reward, which works as a multi-dimensional performance evaluation, enabling more interpretable goal attainment from various perspectives and facilitating more effective reward redistribution. We examine that semantically generated code from LLM can bridge linguistic knowledge and symbolic latent rewards, as it is executable for symbolic objects. Meanwhile, we design latent reward self-verification to increase the stability and reliability of LLM inference. Theoretically, reward-irrelevant redundancy elimination in the latent reward benefits RL performance from more accurate reward estimation. Extensive experimental results witness that LaRe (i) achieves superior temporal credit assignment to SOTA methods, (ii) excels in allocating contributions among multiple agents, and (iii) outperforms policies trained with ground truth rewards for certain tasks.

[Arxiv](https://arxiv.org/abs/2412.11120)