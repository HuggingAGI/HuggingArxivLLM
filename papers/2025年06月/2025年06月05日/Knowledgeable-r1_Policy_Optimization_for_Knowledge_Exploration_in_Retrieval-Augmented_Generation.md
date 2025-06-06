# 检索增强生成中的知识探索策略优化

发布时间：2025年06月05日

`RAG

理由：这篇论文讨论了检索增强生成（RAG）方法，并提出了一种改进的方法Knowledgeable-r1，以解决现有RAG系统在知识整合和上下文利用方面的不足。论文专注于RAG系统的优化和提升，因此归类为RAG。` `知识密集型任务` `生成模型`

> Knowledgeable-r1: Policy Optimization for Knowledge Exploration in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）是提升知识密集型任务性能的核心方法。然而，现有的 RAG 系统往往过度侧重于检索到的上下文信息，这可能导致对不准确来源的依赖，并忽视模型自身拥有的知识，尤其是在面对误导性或冗余信息时。为了解决这一问题，我们提出了 Knowledgeable-r1，该方法通过联合采样并定义知识能力探索中的多策略分布，激发大型语言模型对参数化知识和上下文知识的自我整合与利用。实验结果表明，Knowledgeable-r1 在参数与上下文冲突任务以及通用 RAG 任务中均表现出色，尤其在反事实场景中比基线方法高出 17.07%，并在各类 RAG 任务中均表现出稳定的优势。我们的代码已开源在 https://github.com/lcy80366872/ knowledgeable-r1。

> Retrieval-augmented generation (RAG) is a mainstream method for improving performance on knowledge-intensive tasks. However,current RAG systems often place too much emphasis on retrieved contexts. This can lead to reliance on inaccurate sources and overlook the model's inherent knowledge, especially when dealing with misleading or excessive information. To resolve this imbalance, we propose Knowledgeable-r1 that using joint sampling and define multi policy distributions in knowledge capability exploration to stimulate large language models'self-integrated utilization of parametric and contextual knowledge. Experiments show that Knowledgeable-r1 significantly enhances robustness and reasoning accuracy in both parameters and contextual conflict tasks and general RAG tasks, especially outperforming baselines by 17.07% in counterfactual scenarios and demonstrating consistent gains across RAG tasks. Our code are available at https://github.com/lcy80366872/ knowledgeable-r1.

[Arxiv](https://arxiv.org/abs/2506.05154)