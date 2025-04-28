# PropRAG: 通过束搜索在命题路径上引导检索

发布时间：2025年04月25日

`RAG` `问答系统` `知识图谱`

> PropRAG: Guiding Retrieval with Beam Search over Proposition Paths

# 摘要

> 检索增强生成（RAG）已成为为大型语言模型（LLMs）配备最新知识并缓解持续学习中灾难性遗忘的标准非参数方法。然而，基于独立段落检索的标准RAG无法捕捉人类记忆中复杂推理（关联性）和上下文理解（意义构建）所需的相互关联本质。尽管结构化RAG方法如HippoRAG利用三元组构建的知识图谱（KGs），但固有的上下文丢失限制了其保真度。我们引入了PropRAG框架，该框架利用上下文丰富的命题以及基于命题路径的新型束搜索算法，显式地发现多步推理链。PropRAG的在线检索过程无需调用生成式LLMs，而是依靠高效的图遍历和预计算的嵌入，从而避免了在线LLM推理成本以及证据收集期间的潜在不一致。LLMs被有效地用于离线高质量命题提取和检索后的答案生成。PropRAG在PopQA（55.3%）、2Wiki（93.7%）、HotpotQA（97.0%）和MuSiQue（77.3%）上实现了零样本Recall@5的最先进结果，同时在F1分数方面也达到了顶尖水平（例如MuSiQue上的52.4%）。通过更丰富的表示和显式的、无需LLM的在线路径查找改进证据检索，PropRAG推动了非参数持续学习的发展。

> Retrieval Augmented Generation (RAG) has become the standard non-parametric approach for equipping Large Language Models (LLMs) with up-to-date knowledge and mitigating catastrophic forgetting common in continual learning. However, standard RAG, relying on independent passage retrieval, fails to capture the interconnected nature of human memory crucial for complex reasoning (associativity) and contextual understanding (sense-making). While structured RAG methods like HippoRAG utilize knowledge graphs (KGs) built from triples, the inherent context loss limits fidelity. We introduce PropRAG, a framework leveraging contextually rich propositions and a novel beam search algorithm over proposition paths to explicitly discover multi-step reasoning chains. Crucially, PropRAG's online retrieval process operates entirely without invoking generative LLMs, relying instead on efficient graph traversal and pre-computed embeddings. This avoids online LLM inference costs and potential inconsistencies during evidence gathering. LLMs are used effectively offline for high-quality proposition extraction and post-retrieval for answer generation. PropRAG achieves state-of-the-art zero-shot Recall@5 results on PopQA (55.3%), 2Wiki (93.7%), HotpotQA (97.0%), and MuSiQue (77.3%), alongside top F1 scores (e.g., 52.4% on MuSiQue). By improving evidence retrieval through richer representation and explicit, LLM-free online path finding, PropRAG advances non-parametric continual learning.

[Arxiv](https://arxiv.org/abs/2504.18070)