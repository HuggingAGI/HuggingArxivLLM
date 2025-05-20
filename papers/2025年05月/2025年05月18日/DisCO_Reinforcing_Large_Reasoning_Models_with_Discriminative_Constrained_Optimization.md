# DisCO: 通过判别性约束优化强化大型推理模型

发布时间：2025年05月18日

`LLM应用` `人工智能`

> DisCO: Reinforcing Large Reasoning Models with Discriminative Constrained Optimization

# 摘要

> 近期DeepSeek-R1的成功与开放引发了人们对组相对策略优化（GRPO）作为大型推理模型（LRMs）强化学习方法的广泛关注。本文工作中，我们在二元奖励设置下对GRPO目标进行了分析，揭示了问题层面难度偏差的固有局限性。我们还发现了GRPO与监督学习中传统判别方法之间的联系。基于这些见解，我们引入了一种新的判别式约束优化（DisCO）框架，用于强化LRMs，其核心基于判别式学习原则。

DisCO与GRPO及其近期变体的主要区别在于：
（1）它用由评分函数定义的判别式目标取代了组相对目标；
（2）它放弃了基于剪裁的替代方法，转而采用非剪裁的RL替代目标作为评分函数；
（3）它采用了一种简单而有效的约束优化方法来强制执行KL散度约束，从而确保训练稳定。

因此，DisCO相较于GRPO及其变体具有显著优势：
（i）通过采用判别式目标完全消除了难度偏差；
（ii）通过使用非剪裁评分函数和约束优化方法解决了GRPO及其变体中的熵不稳定问题；
（iii）它允许整合先进的判别式学习技术来应对数据不平衡问题，在训练过程中有相当数量的问题产生了比正面答案更多的负面生成答案。

我们在增强SFT微调模型的数学推理能力方面的实验表明，DisCO显著优于GRPO及其改进变体（如DAPO），在1.5B模型的六项基准任务中，平均性能较GRPO提升7%，较DAPO提升6%。

> The recent success and openness of DeepSeek-R1 have brought widespread attention to Group Relative Policy Optimization (GRPO) as a reinforcement learning method for large reasoning models (LRMs). In this work, we analyze the GRPO objective under a binary reward setting and reveal an inherent limitation of question-level difficulty bias. We also identify a connection between GRPO and traditional discriminative methods in supervised learning. Motivated by these insights, we introduce a new Discriminative Constrained Optimization (DisCO) framework for reinforcing LRMs, grounded in the principle of discriminative learning. The main differences between DisCO and GRPO and its recent variants are: (1) it replaces the group relative objective with a discriminative objective defined by a scoring function; (2) it abandons clipping-based surrogates in favor of non-clipping RL surrogate objectives used as scoring functions; (3) it employs a simple yet effective constrained optimization approach to enforce the KL divergence constraint, ensuring stable training. As a result, DisCO offers notable advantages over GRPO and its variants: (i) it completely eliminates difficulty bias by adopting discriminative objectives; (ii) it addresses the entropy instability in GRPO and its variants through the use of non-clipping scoring functions and a constrained optimization approach; (iii) it allows the incorporation of advanced discriminative learning techniques to address data imbalance, where a significant number of questions have more negative than positive generated answers during training. Our experiments on enhancing the mathematical reasoning capabilities of SFT-finetuned models show that DisCO significantly outperforms GRPO and its improved variants such as DAPO, achieving average gains of 7\% over GRPO and 6\% over DAPO across six benchmark tasks for an 1.5B model.

[Arxiv](https://arxiv.org/abs/2505.12366)