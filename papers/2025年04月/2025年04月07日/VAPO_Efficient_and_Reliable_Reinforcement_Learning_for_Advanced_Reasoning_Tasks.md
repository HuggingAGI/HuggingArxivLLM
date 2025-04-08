# VAPO：面向高级推理任务的高效可靠强化学习方法

发布时间：2025年04月07日

`LLM理论` `人工智能`

> VAPO: Efficient and Reliable Reinforcement Learning for Advanced Reasoning Tasks

# 摘要

> 我们提出了VAPO（基于价值函数的增强近端策略优化框架），这是一个专为基于价值函数范式的推理模型设计的全新框架。在AIME 2024数据集上的基准测试中，VAPO基于Qwen 32B预训练模型，达到了目前最优的性能，评分为【数学公式】。在相同的实验设置下，与之前报告的DeepSeek-R1-Zero-Qwen-32B和DAPO相比，VAPO的表现高出10多个百分点。VAPO的训练过程以其稳定性和高效性著称，仅需5,000步即可达到最优性能。此外，在多次独立运行中，没有出现训练崩溃的情况，这进一步证明了其可靠性。这项研究深入探讨了基于价值函数的强化学习框架在长链式推理中的应用。我们识别出三种困扰基于价值函数方法的关键挑战：价值模型偏差、异质序列长度的存在以及稀疏的奖励信号。通过系统化设计，VAPO提供了一种集成解决方案，有效缓解了这些挑战，从而在长链式推理任务中实现了更优的性能表现。

> We present VAPO, Value-based Augmented Proximal Policy Optimization framework for reasoning models., a novel framework tailored for reasoning models within the value-based paradigm. Benchmarked the AIME 2024 dataset, VAPO, built on the Qwen 32B pre-trained model, attains a state-of-the-art score of $\mathbf{60.4}$. In direct comparison under identical experimental settings, VAPO outperforms the previously reported results of DeepSeek-R1-Zero-Qwen-32B and DAPO by more than 10 points. The training process of VAPO stands out for its stability and efficiency. It reaches state-of-the-art performance within a mere 5,000 steps. Moreover, across multiple independent runs, no training crashes occur, underscoring its reliability. This research delves into long chain-of-thought (long-CoT) reasoning using a value-based reinforcement learning framework. We pinpoint three key challenges that plague value-based methods: value model bias, the presence of heterogeneous sequence lengths, and the sparsity of reward signals. Through systematic design, VAPO offers an integrated solution that effectively alleviates these challenges, enabling enhanced performance in long-CoT reasoning tasks.

[Arxiv](https://arxiv.org/abs/2504.05118)