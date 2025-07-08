# 信息追踪：交互引导大型语言模型

发布时间：2025年07月03日

`LLM应用` `问答系统`

> Conformal Information Pursuit for Interactively Guiding Large Language Models

# 摘要

> 指令微调的大型语言模型（LLMs）在交互式问答任务中有着重要应用。与单轮对话不同，LLM代理通过逐步向用户查询相关信息来做出预测。本文研究了如何通过顺序查询策略最小化预期的查询次数。其中，信息追求（IP）是一种贪心算法，每次迭代时选择能够最大化信息增益或最小化不确定性的问题。然而，由于LLMs的概率预测可能出现过拟合或欠拟合，准确估计互信息或条件熵在实际操作中非常困难，导致查询选择和预测性能不佳。为此，我们提出了基于一致性预测集的替代方法——一致性信息追求（C-IP）。具体来说，C-IP通过预测集与条件熵之间的关系，利用一致性预测集的平均大小来估计不确定性。与条件熵相比，一致性预测集是一种无需分布假设且更稳健的不确定性测量方法。实验结果表明，在经典的20问游戏中，C-IP不仅表现出色，而且在问答链长度上也优于传统方法。此外，在 MediQ 数据集上的交互式医疗场景实验中，C-IP不仅与直接单轮预测的性能相当，还提供了更高的可解释性。

> A significant use case of instruction-finetuned Large Language Models (LLMs) is to solve question-answering tasks interactively. In this setting, an LLM agent is tasked with making a prediction by sequentially querying relevant information from the user, as opposed to a single-turn conversation. This paper explores sequential querying strategies that aim to minimize the expected number of queries. One such strategy is Information Pursuit (IP), a greedy algorithm that at each iteration selects the query that maximizes information gain or equivalently minimizes uncertainty. However, obtaining accurate estimates of mutual information or conditional entropy for LLMs is very difficult in practice due to over- or under-confident LLM probabilities, which leads to suboptimal query selection and predictive performance. To better estimate the uncertainty at each iteration, we propose Conformal Information Pursuit (C-IP), an alternative approach to sequential information gain based on conformal prediction sets. More specifically, C-IP leverages a relationship between prediction sets and conditional entropy at each iteration to estimate uncertainty based on the average size of conformal prediction sets. In contrast to conditional entropy, we find that conformal prediction sets are a distribution-free and robust method of measuring uncertainty. Experiments with 20 Questions show that C-IP obtains better predictive performance and shorter query-answer chains compared to previous approaches to IP and uncertainty-based chain-of-thought methods. Furthermore, extending to an interactive medical setting between a doctor and a patient on the MediQ dataset, C-IP achieves competitive performance with direct single-turn prediction while offering greater interpretability.

[Arxiv](https://arxiv.org/abs/2507.03279)