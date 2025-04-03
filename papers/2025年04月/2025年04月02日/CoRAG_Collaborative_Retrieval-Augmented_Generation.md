# CoRAG：协作式增强生成

发布时间：2025年04月02日

`RAG` `问答系统` `协作式知识库`

> CoRAG: Collaborative Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）模型在知识密集型任务中表现尤为出色，尤其在少量样本学习的场景下。我们推出CoRAG框架，将RAG扩展至协作环境，客户通过共享模型和协作式文档库实现联合训练。为评估CoRAG的效果，我们引入了CRAB基准，专注于协作式同质开放领域问答。实验结果表明，在资源有限的场景下，CoRAG持续超越参数化协作学习方法和本地训练的RAG模型。深入分析发现，共享库中相关文档的重要性，以及意外发现的无关文档带来的益处，同时揭示了引入有害文档可能带来的风险。这为协作式RAG引入了一个新的考量：集体丰富知识库与潜在风险之间的权衡。我们的研究不仅证明了CoRAG的可行性，还突出了关键设计挑战，并为未来研究指明了方向。

> Retrieval-Augmented Generation (RAG) models excel in knowledge-intensive tasks, especially under few-shot learning constraints. We introduce CoRAG, a framework extending RAG to collaborative settings, where clients jointly train a shared model using a collaborative passage store. To evaluate CoRAG, we introduce CRAB, a benchmark for collaborative homogeneous open-domain question answering. Our experiments demonstrate that CoRAG consistently outperforms both parametric collaborative learning methods and locally trained RAG models in low-resource scenarios. Further analysis reveals the critical importance of relevant passages within the shared store, the surprising benefits of incorporating irrelevant passages, and the potential for hard negatives to negatively impact performance. This introduces a novel consideration in collaborative RAG: the trade-off between leveraging a collectively enriched knowledge base and the potential risk of incorporating detrimental passages from other clients. Our findings underscore the viability of CoRAG, while also highlighting key design challenges and promising avenues for future research.

[Arxiv](https://arxiv.org/abs/2504.01883)