# 强化推测解码实现快速排序

发布时间：2025年05月22日

`LLM应用` `信息检索` `推荐系统`

> Reinforcement Speculative Decoding for Fast Ranking

# 摘要

> 大型语言模型（LLMs）在信息检索（IR）系统和推荐系统（RSs）等排序系统中得到了广泛应用。针对自回归解码的延迟问题，部分研究采用了单令牌解码进行排序近似，但这种方法在尾部位置表现显著下降。虽然投机解码（SD）方法通过多位置验证提供了解决方案，但由于其固有的左到右解码范式，在排序系统中面临两大挑战：首先，排序系统对延迟有严格要求，而 SD 方法的验证轮次仍存在不确定性；其次，SD 方法通常会丢弃前一轮中未被接受项目的列表级排序知识，影响后续多令牌预测，尤其是在候选令牌为未被接受项目时。本文提出了一种强化投机解码方法，旨在实现 LLM 的快速排序推理。为满足排序系统的延迟需求，我们创新性地提出了一种自顶向下的解码范式，通过代理在受限预算下迭代优化排序序列。具体而言，我们设计了一种针对排序任务的策略优化方法，利用强化学习（RL）主动探索经过 LLM 验证的多轮排序修改策略。为了在受限预算下更高效地逼近目标 LLM，我们在 RL 过程中充分利用跨轮次由 LLM 验证的所有项目的列表级排序知识，从而优化代理的修改策略。更重要的是，我们从理论上验证了该范式和实现的稳健性和优势。实验结果表明，我们的方法在 IR 和 RS 任务中均表现出显著的有效性。

> Large Language Models (LLMs) have been widely adopted in ranking systems such as information retrieval (IR) systems and recommender systems (RSs). To alleviate the latency of auto-regressive decoding, some studies explore the single (first) token decoding for ranking approximation, but they suffer from severe degradation in tail positions. Although speculative decoding (SD) methods can be a remedy with verification at different positions, they face challenges in ranking systems due to their left-to-right decoding paradigm. Firstly, ranking systems require strict latency constraints, but verification rounds in SD methods remain agnostic; Secondly, SD methods usually discard listwise ranking knowledge about unaccepted items in previous rounds, hindering future multi-token prediction, especially when candidate tokens are the unaccepted items. In this paper, we propose a Reinforcement Speculative Decoding method for fast ranking inference of LLMs. To meet the ranking systems' latency requirement, we propose an up-to-down decoding paradigm that employs an agent to iteratively modify the ranking sequence under a constrained budget. Specifically, we design a ranking-tailored policy optimization, actively exploring optimal multi-round ranking modification policy verified by LLMs via reinforcement learning (RL). To better approximate the target LLM under the constrained budget, we trigger the agent fully utilizing the listwise ranking knowledge about all items verified by LLMs across different rounds in RL, enhancing the modification policy of the agent. More importantly, we demonstrate the theoretical robustness and advantages of our paradigm and implementation. Experiments on both IR and RS tasks show the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2505.20316)