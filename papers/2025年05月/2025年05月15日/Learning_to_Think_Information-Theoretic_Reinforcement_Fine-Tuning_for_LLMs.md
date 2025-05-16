# # 学习思考：基于信息论的强化微调技术助力大型语言模型

发布时间：2025年05月15日

`LLM理论` `人工智能`

> Learning to Think: Information-Theoretic Reinforcement Fine-Tuning for LLMs

# 摘要

> 大型语言模型 (LLMs) 在复杂任务中表现卓越，这得益于其推理能力的提升。然而，现有方法往往忽视推理效果与计算效率之间的平衡，导致推理链过长且 token 资源浪费。为解决这一问题，我们提出了 Learning to Think (L2T)，一个基于信息论的强化微调框架，旨在让 LLMs 以更少的 token 实现最优推理。具体而言，L2T 将每个查询-响应交互视为一个多幕剧式的分层会话，并提出了一种通用的密集过程奖励机制，量化每幕参数层面的信息增益，无需额外标注或任务特定的评估器。我们还提出了一种基于 PAC-Bayes 界限和费舍尔信息矩阵快速估计该奖励的方法。理论分析表明，该方法不仅保持了高估计精度，还显著降低了计算复杂度。通过即时奖励每幕的贡献并惩罚过度更新，L2T 通过强化学习优化模型，最大化每幕的利用率并实现高效更新。实验结果表明，L2T 在不同任务中均表现出显著优势，同时提升了推理效果和效率。

> Large language models (LLMs) excel at complex tasks thanks to advances in reasoning abilities. However, existing methods overlook the trade-off between reasoning effectiveness and computational efficiency, often encouraging unnecessarily long reasoning chains and wasting tokens. To address this, we propose Learning to Think (L2T), an information-theoretic reinforcement fine-tuning framework for LLMs to make the models achieve optimal reasoning with fewer tokens. Specifically, L2T treats each query-response interaction as a hierarchical session of multiple episodes and proposes a universal dense process reward, i.e., quantifies the episode-wise information gain in parameters, requiring no extra annotations or task-specific evaluators. We propose a method to quickly estimate this reward based on PAC-Bayes bounds and the Fisher information matrix. Theoretical analyses show that it significantly reduces computational complexity with high estimation accuracy. By immediately rewarding each episode's contribution and penalizing excessive updates, L2T optimizes the model via reinforcement learning to maximize the use of each episode and achieve effective updates. Empirical results on various reasoning benchmarks and base models demonstrate the advantage of L2T across different tasks, boosting both reasoning effectiveness and efficiency.

[Arxiv](https://arxiv.org/abs/2505.10425)