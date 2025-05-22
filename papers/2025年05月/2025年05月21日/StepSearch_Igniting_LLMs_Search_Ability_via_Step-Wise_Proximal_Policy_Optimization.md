# StepSearch: 借助逐步近端策略优化，激发 LLMs 的搜索潜能

发布时间：2025年05月21日

`Agent` `问答系统` `多跳推理`

> StepSearch: Igniting LLMs Search Ability via Step-Wise Proximal Policy Optimization

# 摘要

> # 摘要
高效的多跳推理要求基于大型语言模型（LLMs）的智能体逐步获取高价值的外部知识。此前研究通过强化学习（RL）训练LLMs执行基于搜索的文档检索，显著提升了问答性能，但在复杂多跳问答任务上表现欠佳，原因在于仅依赖全局信号的稀疏奖励。

为填补这一研究空白，我们提出了StepSearch——一个基于逐步邻近策略优化方法的搜索LLMs框架。它包含更丰富详细的中间搜索奖励，以及基于信息增益和冗余惩罚的词级别过程监督，以更好地指导每一步搜索。我们通过一系列数据管道方法，基于开源数据集构建了一个细粒度问答数据集，其中包含子问题级别的搜索轨迹。

在标准多跳问答基准测试中，StepSearch显著超越了全局奖励基线模型。仅使用19k训练数据，就为3B和7B模型分别带来了11.2%和4.2%的绝对性能提升。这充分证明了细粒度、逐步监督在优化深度搜索LLMs中的有效性。我们的实现已开源，地址为https://github.com/zxh20001117/StepSearch。


> Efficient multi-hop reasoning requires Large Language Models (LLMs) based agents to acquire high-value external knowledge iteratively. Previous work has explored reinforcement learning (RL) to train LLMs to perform search-based document retrieval, achieving notable improvements in QA performance, but underperform on complex, multi-hop QA resulting from the sparse rewards from global signal only. To address this gap in existing research, we introduce StepSearch, a framework for search LLMs that trained with step-wise proximal policy optimization method. It consists of richer and more detailed intermediate search rewards and token-level process supervision based on information gain and redundancy penalties to better guide each search step. We constructed a fine-grained question-answering dataset containing sub-question-level search trajectories based on open source datasets through a set of data pipeline method. On standard multi-hop QA benchmarks, it significantly outperforms global-reward baselines, achieving 11.2% and 4.2% absolute improvements for 3B and 7B models over various search with RL baselines using only 19k training data, demonstrating the effectiveness of fine-grained, stepwise supervision in optimizing deep search LLMs. Our implementation is publicly available at https://github.com/zxh20001117/StepSearch.

[Arxiv](https://arxiv.org/abs/2505.15107)