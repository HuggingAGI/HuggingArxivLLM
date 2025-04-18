# 人与AI在基于LLM的相关性判断中的提示敏感性比较分析

发布时间：2025年04月16日

`LLM应用` `信息检索` `相关性评估`

> A Human-AI Comparative Analysis of Prompt Sensitivity in LLM-Based Relevance Judgment

# 摘要

> 大型语言模型（LLMs）在信息检索（IR）任务中的相关性判断自动化应用日益广泛，其表现常与人工标注接近，甚至达到人类间的共识水平。为了评估基于LLM的相关性判断的稳健性和可靠性，我们系统性地研究了提示敏感性对任务的影响。我们从15位人类专家和15个LLMs中收集了三种任务——二元、分级和成对——的相关性评估提示，总共获得90个提示。在过滤掉3位人类和3个LLM提供的不可用提示后，我们使用剩余的72个提示，结合三种不同的LLMs作为评估者，对来自TREC深度学习数据集（2020和2021年）的文档/查询对进行了标注。我们通过Cohen's 【数学公式】和成对一致性的度量方法，将LLM生成的标签与TREC官方的人工标签进行了比较。除了研究提示变化对与人工标签一致性的影响外，我们还比较了人类生成和LLM生成的提示，并分析了不同LLMs作为评估者之间的差异。此外，我们将人类和LLM生成的提示与Bing和TREC 2024检索增强生成（RAG）赛道中用于相关性评估的标准UMBRELA提示进行了对比。为了支持未来基于LLM的评估研究，我们在GitHub上公开了所有数据和提示，链接为https://github.com/Narabzad/prompt-sensitivity-relevance-judgements/。

> Large Language Models (LLMs) are increasingly used to automate relevance judgments for information retrieval (IR) tasks, often demonstrating agreement with human labels that approaches inter-human agreement. To assess the robustness and reliability of LLM-based relevance judgments, we systematically investigate impact of prompt sensitivity on the task. We collected prompts for relevance assessment from 15 human experts and 15 LLMs across three tasks~ -- ~binary, graded, and pairwise~ -- ~yielding 90 prompts in total. After filtering out unusable prompts from three humans and three LLMs, we employed the remaining 72 prompts with three different LLMs as judges to label document/query pairs from two TREC Deep Learning Datasets (2020 and 2021). We compare LLM-generated labels with TREC official human labels using Cohen's $κ$ and pairwise agreement measures. In addition to investigating the impact of prompt variations on agreement with human labels, we compare human- and LLM-generated prompts and analyze differences among different LLMs as judges. We also compare human- and LLM-generated prompts with the standard UMBRELA prompt used for relevance assessment by Bing and TREC 2024 Retrieval Augmented Generation (RAG) Track. To support future research in LLM-based evaluation, we release all data and prompts at https://github.com/Narabzad/prompt-sensitivity-relevance-judgements/.

[Arxiv](https://arxiv.org/abs/2504.12408)