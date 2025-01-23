# 自适应检索无需自我认知？让不确定性回归本源

发布时间：2025年01月22日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在问答系统中的应用，特别是如何通过自适应检索方法结合LLMs的内在知识和外部信息来提升问答的准确性。论文还对比了多种自适应检索方法和不确定性估计技术的效率和性能，这些都是RAG领域的核心问题。因此，这篇论文应被分类为RAG。` `问答系统` `信息检索`

> Adaptive Retrieval Without Self-Knowledge? Bringing Uncertainty Back Home

# 摘要

> 检索增强生成（RAG）提升了问答（QA）的准确性，并有效缓解了大型语言模型（LLMs）中的幻觉问题，但代价是显著增加了计算开销。此外，RAG并非总是必要，因为它可能引入无关信息。近期，自适应检索方法将LLMs的内在知识与外部信息结合，利用LLM的自我知识进行优化，但这些方法往往缺乏效率评估和与不确定性估计技术的对比。为此，我们全面分析了35种自适应检索方法（包括8种最新方法和27种不确定性估计技术），在6个数据集上使用10个指标评估QA性能、自我知识和效率。结果显示，不确定性估计技术在效率和自我知识方面通常优于复杂管道，同时保持了相当的QA性能。

> Retrieval Augmented Generation (RAG) improves correctness of Question Answering (QA) and addresses hallucinations in Large Language Models (LLMs), yet greatly increase computational costs. Besides, RAG is not always needed as may introduce irrelevant information. Recent adaptive retrieval methods integrate LLMs' intrinsic knowledge with external information appealing to LLM self-knowledge, but they often neglect efficiency evaluations and comparisons with uncertainty estimation techniques. We bridge this gap by conducting a comprehensive analysis of 35 adaptive retrieval methods, including 8 recent approaches and 27 uncertainty estimation techniques, across 6 datasets using 10 metrics for QA performance, self-knowledge, and efficiency. Our findings show that uncertainty estimation techniques often outperform complex pipelines in terms of efficiency and self-knowledge, while maintaining comparable QA performance.

[Arxiv](https://arxiv.org/abs/2501.12835)