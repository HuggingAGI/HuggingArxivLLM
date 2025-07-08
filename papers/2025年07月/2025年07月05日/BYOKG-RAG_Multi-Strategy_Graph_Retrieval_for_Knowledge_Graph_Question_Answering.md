# # BYOKG-RAG：针对知识图问答的多策略图检索

发布时间：2025年07月05日

`RAG` `知识图谱` `问答系统`

> BYOKG-RAG: Multi-Strategy Graph Retrieval for Knowledge Graph Question Answering

# 摘要

> 知识图谱问答（KGQA）因输入图的结构和语义差异而面临重大挑战。现有方法依赖大型语言模型（LLM）代理进行图遍历和检索，但这种方法容易出现实体链接错误，并且难以推广到自定义知识图谱（“带你的知识图谱”）。为此，我们提出了BYOKG-RAG框架，通过协同结合LLM和专用图检索工具来增强KGQA。在BYOKG-RAG中，LLM生成关键图构件（问题实体、候选答案、推理路径和OpenCypher查询），而图工具将这些构件链接到知识图谱并检索相关图上下文。通过迭代优化图链接和检索，BYOKG-RAG最终生成高质量答案。通过从不同图工具检索上下文，BYOKG-RAG为自定义知识图谱上的问答提供了更通用和稳健的解决方案。在涵盖多种知识图谱类型的五个基准测试中，BYOKG-RAG比第二好的图检索方法高出4.5个百分点，并且在自定义知识图谱上表现出更好的泛化能力。BYOKG-RAG框架已开源，地址为https://github.com/awslabs/graphrag-toolkit。


> Knowledge graph question answering (KGQA) presents significant challenges due to the structural and semantic variations across input graphs. Existing works rely on Large Language Model (LLM) agents for graph traversal and retrieval; an approach that is sensitive to traversal initialization, as it is prone to entity linking errors and may not generalize well to custom ("bring-your-own") KGs. We introduce BYOKG-RAG, a framework that enhances KGQA by synergistically combining LLMs with specialized graph retrieval tools. In BYOKG-RAG, LLMs generate critical graph artifacts (question entities, candidate answers, reasoning paths, and OpenCypher queries), and graph tools link these artifacts to the KG and retrieve relevant graph context. The retrieved context enables the LLM to iteratively refine its graph linking and retrieval, before final answer generation. By retrieving context from different graph tools, BYOKG-RAG offers a more general and robust solution for QA over custom KGs. Through experiments on five benchmarks spanning diverse KG types, we demonstrate that BYOKG-RAG outperforms the second-best graph retrieval method by 4.5% points while showing better generalization to custom KGs. BYOKG-RAG framework is open-sourced at https://github.com/awslabs/graphrag-toolkit.

[Arxiv](https://arxiv.org/abs/2507.04127)