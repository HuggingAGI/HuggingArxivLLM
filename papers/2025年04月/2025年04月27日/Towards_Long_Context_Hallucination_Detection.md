# 迈向长上下文幻觉检测

发布时间：2025年04月27日

`LLM应用` `信息检索` `数据处理`

> Towards Long Context Hallucination Detection

# 摘要

> 大型语言模型 (LLMs) 在各种任务中表现卓越，但容易出现上下文幻觉，生成缺乏依据或与上下文矛盾的信息。尽管已有许多研究探讨了 LLMs 中的上下文幻觉问题，但在长上下文输入中解决这一难题仍是一个开放性问题。本研究构建了一个专门用于长上下文幻觉检测的数据集，并提出了一种创新架构，使预训练编码模型（如 BERT）能够通过分解和聚合机制处理长上下文并有效检测上下文幻觉。实验结果表明，该架构在各种指标上显著优于之前类似规模的模型及基于 LLM 的模型，推理速度也大幅提高。

> Large Language Models (LLMs) have demonstrated remarkable performance across various tasks. However, they are prone to contextual hallucination, generating information that is either unsubstantiated or contradictory to the given context. Although many studies have investigated contextual hallucinations in LLMs, addressing them in long-context inputs remains an open problem. In this work, we take an initial step toward solving this problem by constructing a dataset specifically designed for long-context hallucination detection. Furthermore, we propose a novel architecture that enables pre-trained encoder models, such as BERT, to process long contexts and effectively detect contextual hallucinations through a decomposition and aggregation mechanism. Our experimental results show that the proposed architecture significantly outperforms previous models of similar size as well as LLM-based models across various metrics, while providing substantially faster inference.

[Arxiv](https://arxiv.org/abs/2504.19457)