# FactCG: 基于图的多跳数据增强事实核查

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要讨论了如何改进LLM（大型语言模型）在检测幻觉方面的性能，提出了一种新的合成数据生成方法CG2C，并展示了其在实际应用中的效果。这属于LLM在实际问题中的应用，因此分类为LLM应用。` `事实检查`

> FactCG: Enhancing Fact Checkers with Graph-Based Multi-Hop Data

# 摘要

> 以往研究训练基于事实的分类模型来检测LLM中的幻觉，主要依赖公开的NLI数据和合成数据。然而，传统NLI数据集并不适合文档级推理，而这对检测LLM幻觉至关重要。最近的方法通过迭代删除文档中的句子，并使用LLM提示进行事实性标注来生成文档级合成数据。虽然有效，但这种方法对长文档计算成本高，且受限于LLM的能力。本文分析了现有最先进模型使用的合成训练数据与真实LLM输出之间的差异，并提出了一种新的合成数据生成方法CG2C，利用从文档中提取的上下文图进行多跳推理。我们的事实检查模型FactCG在使用相同骨干模型的情况下，通过更连贯的推理展示了更好的性能。实验表明，它在LLM-Aggrefact基准测试中甚至优于GPT-4-o，且模型规模更小。

> Prior research on training grounded factuality classification models to detect hallucinations in large language models (LLMs) has relied on public natural language inference (NLI) data and synthetic data. However, conventional NLI datasets are not well-suited for document-level reasoning, which is critical for detecting LLM hallucinations. Recent approaches to document-level synthetic data generation involve iteratively removing sentences from documents and annotating factuality using LLM-based prompts. While effective, this method is computationally expensive for long documents and limited by the LLM's capabilities. In this work, we analyze the differences between existing synthetic training data used in state-of-the-art models and real LLM output claims. Based on our findings, we propose a novel approach for synthetic data generation, CG2C, that leverages multi-hop reasoning on context graphs extracted from documents. Our fact checker model, FactCG, demonstrates improved performance with more connected reasoning, using the same backbone models. Experiments show it even outperforms GPT-4-o on the LLM-Aggrefact benchmark with much smaller model size.

[Arxiv](https://arxiv.org/abs/2501.17144)