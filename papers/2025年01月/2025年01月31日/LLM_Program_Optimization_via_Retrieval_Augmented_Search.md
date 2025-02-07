# 基于检索增强搜索的 LLM 程序优化

发布时间：2025年01月31日

`RAG

理由：这篇论文提出了一种名为检索增强搜索（RAS）的方法，该方法通过从训练数据集中检索上下文示例来指导大型语言模型（LLM）的优化过程。这种方法的核心是利用检索机制来增强LLM的性能，属于检索增强生成（Retrieval-Augmented Generation, RAG）的范畴。因此，将其分类为RAG是合适的。` `程序优化`

> LLM Program Optimization via Retrieval Augmented Search

# 摘要

> 随着大型语言模型（LLMs）的兴起，其在解决复杂编程任务中的应用备受关注。最近的研究表明，LLMs在程序优化方面展现出巨大潜力，这是编程语言研究中的一大挑战。我们提出了一种名为检索增强搜索（RAS）的黑箱适应方法，该方法通过束搜索优化候选方案，并在每一步从慢-快程序对训练数据集中检索上下文示例来指导LLM。关键发现是，基于LLM生成的自然语言描述进行上下文检索的效果显著优于基于源代码的检索。此外，我们还提出了一种名为AEGIS的方法，通过将训练示例分解为“原子编辑”来提升可解释性，这些编辑更具增量性。实验表明，RAS的表现比现有最先进的黑箱适应策略高出1.8倍，而AEGIS在更小的编辑量下表现高出1.37倍。

> With the advent of large language models (LLMs), there has been a great deal of interest in applying them to solve difficult programming tasks. Recent work has demonstrated their potential at program optimization, a key challenge in programming languages research. We propose a blackbox adaptation method called Retrieval Augmented Search (RAS) that performs beam search over candidate optimizations; at each step, it retrieves in-context examples from a given training dataset of slow-fast program pairs to guide the LLM. Critically, we find that performing contextual retrieval based on an LLM-generated natural language description significantly outperforms retrieval based on the source code. In addition, we propose a method called AEGIS for improving interpretability by decomposing training examples into "atomic edits" that are significantly more incremental in nature. We show that RAS performs 1.8$\times$ better than prior state-of-the-art blackbox adaptation strategies, and that AEGIS performs 1.37$\times$ better while performing significantly smaller edits.

[Arxiv](https://arxiv.org/abs/2501.18916)