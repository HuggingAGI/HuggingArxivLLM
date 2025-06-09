# 联合梯度协同攻击：统一针对检索增强生成系统的基于梯度中毒攻击方法

发布时间：2025年06月06日

`RAG`

> Joint-GCG: Unified Gradient-Based Poisoning Attacks on Retrieval-Augmented Generation Systems

# 摘要

> 检索增强生成（RAG）系统通过结合外部语料库中的相关文档，显著扩展了大型语言模型（LLM）的能力，使其能够利用海量且最新的外部知识。然而，这种依赖外部知识的特性使得RAG系统容易遭受语料库投毒攻击，即通过注入中毒文档来操纵生成输出。现有的投毒攻击策略通常将检索和生成阶段视为独立的，这限制了它们的攻击效果。为此，我们提出Joint-GCG框架，通过三项创新首次实现了对检索器和生成器模型的基于梯度攻击的统一：(1) 跨词汇表投影，用于对齐嵌入空间；(2) 梯度标记化对齐，用于同步标记级梯度信号；(3) 自适应加权融合，用于动态平衡攻击目标。实验结果表明，Joint-GCG在多个检索器和生成器模型上实现了最高25%和平均5%的攻击成功率提升。尽管在白盒假设下进行了优化，但生成的中毒样本对未见过的模型表现出前所未有的迁移能力。Joint-GCG通过在检索和生成阶段统一基于梯度的攻击，从根本上改变了我们对RAG系统漏洞的理解。我们的代码可在https://github.com/NicerWang/Joint-GCG获取。

> Retrieval-Augmented Generation (RAG) systems enhance Large Language Models (LLMs) by retrieving relevant documents from external corpora before generating responses. This approach significantly expands LLM capabilities by leveraging vast, up-to-date external knowledge. However, this reliance on external knowledge makes RAG systems vulnerable to corpus poisoning attacks that manipulate generated outputs via poisoned document injection. Existing poisoning attack strategies typically treat the retrieval and generation stages as disjointed, limiting their effectiveness. We propose Joint-GCG, the first framework to unify gradient-based attacks across both retriever and generator models through three innovations: (1) Cross-Vocabulary Projection for aligning embedding spaces, (2) Gradient Tokenization Alignment for synchronizing token-level gradient signals, and (3) Adaptive Weighted Fusion for dynamically balancing attacking objectives. Evaluations demonstrate that Joint-GCG achieves at most 25% and an average of 5% higher attack success rate than previous methods across multiple retrievers and generators. While optimized under a white-box assumption, the generated poisons show unprecedented transferability to unseen models. Joint-GCG's innovative unification of gradient-based attacks across retrieval and generation stages fundamentally reshapes our understanding of vulnerabilities within RAG systems. Our code is available at https://github.com/NicerWang/Joint-GCG.

[Arxiv](https://arxiv.org/abs/2506.06151)