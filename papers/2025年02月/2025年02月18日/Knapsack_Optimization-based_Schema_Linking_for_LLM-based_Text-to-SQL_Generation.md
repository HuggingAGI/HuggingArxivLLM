# 基于背包优化的模式链接方法在LLM文本到SQL生成中的应用

发布时间：2025年02月18日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLM）生成SQL语句，并提出了一种新的模式链接方法KaSLA，以优化模型在SQL生成任务中的表现。虽然论文中提到了LLM的应用，但其核心贡献在于提出了一种新的方法来改进SQL生成的效果，因此属于LLM应用类别。` `数据工程`

> Knapsack Optimization-based Schema Linking for LLM-based Text-to-SQL Generation

# 摘要

> 从用户查询生成SQL语句是一个长期存在的技术挑战，模式链接的准确性直接影响后续SQL生成效果。目前的模式链接模型仍存在遗漏关键模式元素或包含过多冗余元素的问题。这是因为常用的召回率和精确率指标无法有效捕捉相关元素的遗漏，无法真实反映模式链接性能。针对这一问题，我们提出了一种增强的模式链接指标，并引入了基于背包优化的模式链接代理KaSLA。KaSLA采用分层链接策略，先识别最优表链接，再进行列链接以减少候选空间。在每个链接过程中，KaSLA利用背包优化方法，平衡相关元素的链接和冗余元素的控制。实验结果显示，KaSLA-1.6B在模式链接效果上优于包括deepseek-v3在内的大型LLM。在Spider和BIRD基准测试中，KaSLA能够显著提升现有最优文本到SQL模型的SQL生成性能。


> Generating SQLs from user queries is a long-standing challenge, where the accuracy of initial schema linking significantly impacts subsequent SQL generation performance. However, current schema linking models still struggle with missing relevant schema elements or an excess of redundant ones. A crucial reason for this is that commonly used metrics, recall and precision, fail to capture relevant element missing and thus cannot reflect actual schema linking performance. Motivated by this, we propose an enhanced schema linking metric by introducing a restricted missing indicator. Accordingly, we introduce Knapsack optimization-based Schema Linking Agent (KaSLA), a plug-in schema linking agent designed to prevent the missing of relevant schema elements while minimizing the inclusion of redundant ones. KaSLA employs a hierarchical linking strategy that first identifies the optimal table linking and subsequently links columns within the selected table to reduce linking candidate space. In each linking process, it utilize a knapsack optimization approach to link potentially relevant elements while accounting for a limited tolerance of potential redundant ones.With this optimization, KaSLA-1.6B achieves superior schema linking results compared to large-scale LLMs, including deepseek-v3 with state-of-the-art (SOTA) schema linking method. Extensive experiments on Spider and BIRD benchmarks verify that KaSLA can significantly improve the SQL generation performance of SOTA text-to-SQL models by substituting their schema linking processes.

[Arxiv](https://arxiv.org/abs/2502.12911)