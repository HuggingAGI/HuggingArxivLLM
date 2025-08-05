# 拆解熵与性能的关系：探索强化学习效果提升的关键所在

发布时间：2025年08月04日

`LLM理论

摘要中的论文探讨了强化学习在提升大型语言模型推理能力中的应用，特别是熵与性能之间的平衡，属于理论层面的研究。`

> Decomposing the Entropy-Performance Exchange: The Missing Keys to Unlocking Effective Reinforcement Learning

# 摘要

> 近年来，可验证奖励的强化学习（RLVR）成为提升大型语言模型（LLMs）推理能力的重要手段。然而，RLVR的核心挑战在于如何平衡策略的熵与性能之间的关系。尽管这一交换过程至关重要，但目前对于其何时以及如何最有效地发挥作用仍缺乏细致入微的理解。为填补这一空白，我们对RLVR在不同粒度级别下的熵-性能交换机制进行了系统性实证分析。具体而言，我们首先根据熵的变化将训练过程划分为两个不同阶段，即上升阶段和平台期阶段，然后系统性地研究了该机制在阶段级别、实例级别和标记级别粒度下的差异。我们的分析表明，在上升阶段，负样本中的熵减少有助于有效推理模式的学习，进而推动性能的快速提升。此外，在平台期阶段，学习效率与低困惑度样本中出现的高熵标记以及位于序列末尾的标记密切相关。受这些发现的启发，我们提出了两种方法，通过动态调整奖励信号，利用困惑度和位置信息，将RL更新集中在具有高学习潜力的标记上，与基线方法相比，在多种LLMs上实现了性能提升。

> Recently, reinforcement learning with verifiable rewards (RLVR) has been widely used for enhancing the reasoning abilities of large language models (LLMs). A core challenge in RLVR involves managing the exchange between entropy and performance of policies. Despite the importance of this exchange, a fine-grained understanding of when and how this exchange operates most effectively remains limited. To bridge this gap, we conduct a systematic empirical analysis of the entropy-performance exchange mechanism of RLVR across different levels of granularity. Specifically, we first divide the training process into two distinct stages based on entropy dynamics, i.e., rising stage and plateau stage, and then systematically investigate how this mechanism varies across stage-level, instance-level, and token-level granularitiess. Our analysis reveals that, in the rising stage, entropy reduction in negative samples facilitates the learning of effective reasoning patterns, which in turn drives rapid performance gains. Moreover, in the plateau stage, learning efficiency strongly correlates with high-entropy tokens present in low-perplexity samples and those located at the end of sequences. Motivated by these findings, we propose two methods that dynamically adjust the reward signal using perplexity and positional information to focus RL updates on tokens that exhibit high learning potential, achieving improvements compared to the baseline methods on various LLMs.

[Arxiv](https://arxiv.org/abs/2508.02260)