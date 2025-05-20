# GuRE:生成式法律文本检索查询重写器

发布时间：2025年05月19日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLM）来改进法律文本检索系统，特别是通过生成式查询重写器（GuRE）来解决查询与目标文本之间的词汇差异问题。研究展示了LLM在实际应用中的有效性，属于LLM的应用领域。` `信息检索`

> GuRE:Generative Query REwriter for Legal Passage Retrieval

# 摘要

> 法律文本检索（LPR）系统在帮助法律从业者撰写法律论点时发挥着重要作用，但这一领域仍待深入探索。造成这一现状的主要原因是查询与目标文本之间的显著词汇差异。针对这一挑战，我们提出了一种简单而有效的解决方案——生成式查询重写器（GuRE）。通过利用大型语言模型（LLMs）的强大生成能力，我们对 LLM 进行了专门训练，用于优化查询重写。重写后的查询能够显著缓解词汇差异问题，从而帮助检索器更精准地获取目标文本。实验结果表明，GuRE 在提升检索性能方面表现出显著优势，并且在多种基线方法中表现最优。进一步分析显示，不同的训练目标会导致不同的检索行为，使得 GuRE 在实际应用中比直接对检索器进行微调更为合适。代码可在 github.com/daehuikim/GuRE 获取。

> Legal Passage Retrieval (LPR) systems are crucial as they help practitioners save time when drafting legal arguments. However, it remains an underexplored avenue. One primary reason is the significant vocabulary mismatch between the query and the target passage. To address this, we propose a simple yet effective method, the Generative query REwriter (GuRE). We leverage the generative capabilities of Large Language Models (LLMs) by training the LLM for query rewriting. "Rewritten queries" help retrievers to retrieve target passages by mitigating vocabulary mismatch. Experimental results show that GuRE significantly improves performance in a retriever-agnostic manner, outperforming all baseline methods. Further analysis reveals that different training objectives lead to distinct retrieval behaviors, making GuRE more suitable than direct retriever fine-tuning for real-world applications. Codes are avaiable at github.com/daehuikim/GuRE.

[Arxiv](https://arxiv.org/abs/2505.12950)