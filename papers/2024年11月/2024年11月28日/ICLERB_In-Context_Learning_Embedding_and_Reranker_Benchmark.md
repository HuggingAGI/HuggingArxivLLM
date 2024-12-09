# ICLERB：上下文学习嵌入与重排序基准

发布时间：2024年11月28日

`RAG` `人工智能`

> ICLERB: In-Context Learning Embedding and Reranker Benchmark

# 摘要

> In-Context Learning（ICL）能让大型语言模型（LLMs）依据带有相关信息的提示来执行新任务。Retrieval-Augmented Generation（RAG）在查询时将检索到的文档融入LLM的上下文，从而增强ICL。然而，传统的检索方法注重语义相关性，把检索当作搜索问题。在本文中，我们提议将ICL的检索重新界定为推荐问题，旨在选出在ICL任务中效用最大的文档。我们引入了In-Context Learning Embedding and Reranker Benchmark（ICLERB），这是一个全新的评估框架，依据检索器在ICL设定中提升LLM准确性的能力来对其进行比较。另外，我们提出了一种新颖的来自AI反馈的强化学习排序（RLRAIF）算法，旨在利用LLM的最少反馈来微调检索模型。我们的实验结果显示出ICLERB与现有基准之间的显著差异，并且表明用我们的RLRAIF算法微调的小型模型优于大型的最先进检索模型。这些发现凸显了现有评估方法的局限性以及对适应ICL的专用基准和训练策略的需求。

> In-Context Learning (ICL) enables Large Language Models (LLMs) to perform new tasks by conditioning on prompts with relevant information. Retrieval-Augmented Generation (RAG) enhances ICL by incorporating retrieved documents into the LLM's context at query time. However, traditional retrieval methods focus on semantic relevance, treating retrieval as a search problem. In this paper, we propose reframing retrieval for ICL as a recommendation problem, aiming to select documents that maximize utility in ICL tasks. We introduce the In-Context Learning Embedding and Reranker Benchmark (ICLERB), a novel evaluation framework that compares retrievers based on their ability to enhance LLM accuracy in ICL settings. Additionally, we propose a novel Reinforcement Learning-to-Rank from AI Feedback (RLRAIF) algorithm, designed to fine-tune retrieval models using minimal feedback from the LLM. Our experimental results reveal notable differences between ICLERB and existing benchmarks, and demonstrate that small models fine-tuned with our RLRAIF algorithm outperform large state-of-the-art retrieval models. These findings highlight the limitations of existing evaluation methods and the need for specialized benchmarks and training strategies adapted to ICL.

[Arxiv](https://arxiv.org/abs/2411.18947)