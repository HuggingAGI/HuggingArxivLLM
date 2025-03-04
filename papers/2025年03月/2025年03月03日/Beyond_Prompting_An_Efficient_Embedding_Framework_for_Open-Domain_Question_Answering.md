# # 超越提示：打造高效嵌入框架，助力开放领域问答

发布时间：2025年03月03日

`LLM应用

理由：这篇论文探讨了大型语言模型在开放领域问答（ODQA）中的应用，提出了一种新的框架EmbQA，通过优化检索和阅读器的性能来提升问答系统的准确性和效率。它属于LLM的应用层面，因为它展示了如何将LLM用于实际任务并提出改进方法。` `问答系统` `信息检索`

> Beyond Prompting: An Efficient Embedding Framework for Open-Domain Question Answering

# 摘要

> 大型语言模型推动了开放领域问答（ODQA）技术迈入新领域。然而，现有的检索-阅读器流水线往往依赖多轮提示指令，导致计算开销高、系统不稳定以及检索覆盖范围有限。针对这些问题，我们提出了EmbQA——一个创新的嵌入层框架，通过优化检索器和阅读器的性能来提供更优的解决方案。具体来说，我们利用无监督对比学习方法优化查询表示，通过轻量级线性层重新排序检索结果，突出最可能包含正确答案的内容。此外，我们引入了探索性嵌入技术，扩展模型的潜在语义空间，丰富候选答案多样性，并借助熵值选择机制自动筛选最可靠答案。实验结果显示，EmbQA在三个开源大型语言模型、三种检索方法和四个开放领域问答基准测试中，均显著超越现有方法，在准确性和效率方面表现优异。

> Large language models have recently pushed open domain question answering (ODQA) to new frontiers. However, prevailing retriever-reader pipelines often depend on multiple rounds of prompt level instructions, leading to high computational overhead, instability, and suboptimal retrieval coverage. In this paper, we propose EmbQA, an embedding-level framework that alleviates these shortcomings by enhancing both the retriever and the reader. Specifically, we refine query representations via lightweight linear layers under an unsupervised contrastive learning objective, thereby reordering retrieved passages to highlight those most likely to contain correct answers. Additionally, we introduce an exploratory embedding that broadens the model's latent semantic space to diversify candidate generation and employs an entropy-based selection mechanism to choose the most confident answer automatically. Extensive experiments across three open-source LLMs, three retrieval methods, and four ODQA benchmarks demonstrate that EmbQA substantially outperforms recent baselines in both accuracy and efficiency.

[Arxiv](https://arxiv.org/abs/2503.01606)