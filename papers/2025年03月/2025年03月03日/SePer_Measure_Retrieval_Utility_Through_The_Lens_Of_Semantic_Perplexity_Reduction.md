# SePer：从语义困惑度降低的角度评估检索效用

发布时间：2025年03月03日

`RAG

理由：这篇论文专注于研究和改进检索增强生成（RAG）方法中的评估问题，提出了一种新的评估方法，并引入了新的指标来衡量检索质量。因此，它属于RAG类别。`

> SePer: Measure Retrieval Utility Through The Lens Of Semantic Perplexity Reduction

# 摘要

> 大型语言模型（LLMs）通过检索增强生成（RAG）方法显著提升了生成性能。然而，现有研究在评估RAG效果时存在两个局限：一是将检索与生成组件一并评估，模糊了检索的独立贡献；二是使用传统指标如NDCG评估检索器，导致对检索在生成过程中的实际效用理解不足。为解决这些问题，本研究提出了一种基于信息增益的自动评估方法，通过RAG框架下的信息增益来衡量检索质量。具体而言，我们引入了语义困惑度（SePer）这一指标，用于捕捉LLM对检索信息正确性的内部信念。通过检索后语义困惑度的降低程度，我们量化了检索的效用。实验结果表明，SePer不仅与人类偏好高度一致，还能在各类RAG场景下提供更精准、高效的检索效用评估。

> Large Language Models (LLMs) have demonstrated improved generation performance by incorporating externally retrieved knowledge, a process known as retrieval-augmented generation (RAG). Despite the potential of this approach, existing studies evaluate RAG effectiveness by 1) assessing retrieval and generation components jointly, which obscures retrieval's distinct contribution, or 2) examining retrievers using traditional metrics such as NDCG, which creates a gap in understanding retrieval's true utility in the overall generation process. To address the above limitations, in this work, we introduce an automatic evaluation method that measures retrieval quality through the lens of information gain within the RAG framework. Specifically, we propose Semantic Perplexity (SePer), a metric that captures the LLM's internal belief about the correctness of the retrieved information. We quantify the utility of retrieval by the extent to which it reduces semantic perplexity post-retrieval. Extensive experiments demonstrate that SePer not only aligns closely with human preferences but also offers a more precise and efficient evaluation of retrieval utility across diverse RAG scenarios.

[Arxiv](https://arxiv.org/abs/2503.01478)