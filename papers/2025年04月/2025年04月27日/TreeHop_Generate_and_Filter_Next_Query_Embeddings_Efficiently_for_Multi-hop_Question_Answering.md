# TreeHop：用于多跳问答的高效生成与过滤下一个查询嵌入方法

发布时间：2025年04月27日

`RAG` `问答系统` `信息检索`

> TreeHop: Generate and Filter Next Query Embeddings Efficiently for Multi-hop Question Answering

# 摘要

> 检索增强生成（RAG）系统在处理多跳问答（MHQA）时面临重大挑战，复杂的查询往往需要整合多个文档片段的信息。现有解决方案通常依赖迭代式基于LLM的查询改写和路由，这种做法因需反复调用LLM和多阶段流程而导致高昂计算成本。针对这些限制，我们推出TreeHop——一个无需LLM参与查询优化的嵌入式框架。TreeHop通过融合先前查询与检索文档的语义信息动态更新查询嵌入，仅借助嵌入空间操作即可完成迭代检索。这一创新方法将传统的"检索-改写-向量化-检索"循环精简为更高效的"检索-嵌入-检索"循环，显著降低了计算开销。此外，我们引入了基于规则的停止准则，进一步减少冗余检索，实现效率与召回率的平衡。实验结果表明，TreeHop在三个开放领域MHQA数据集上表现优异，仅需5%-0.4%的模型参数量即可达到与先进RAG方法相当的性能，相比现有方法将查询延迟降低了约99%。这使得TreeHop成为多种知识密集型应用中更快、更具成本效益的部署方案。代码和数据已开源：https://github.com/allen-li1231/TreeHop。


> Retrieval-augmented generation (RAG) systems face significant challenges in multi-hop question answering (MHQA), where complex queries require synthesizing information across multiple document chunks. Existing approaches typically rely on iterative LLM-based query rewriting and routing, resulting in high computational costs due to repeated LLM invocations and multi-stage processes. To address these limitations, we propose TreeHop, an embedding-level framework without the need for LLMs in query refinement. TreeHop dynamically updates query embeddings by fusing semantic information from prior queries and retrieved documents, enabling iterative retrieval through embedding-space operations alone. This method replaces the traditional "Retrieve-Rewrite-Vectorize-Retrieve" cycle with a streamlined "Retrieve-Embed-Retrieve" loop, significantly reducing computational overhead. Moreover, a rule-based stop criterion is introduced to further prune redundant retrievals, balancing efficiency and recall rate. Experimental results show that TreeHop rivals advanced RAG methods across three open-domain MHQA datasets, achieving comparable performance with only 5\%-0.4\% of the model parameter size and reducing the query latency by approximately 99\% compared to concurrent approaches. This makes TreeHop a faster and more cost-effective solution for deployment in a range of knowledge-intensive applications. For reproducibility purposes, codes and data are available here: https://github.com/allen-li1231/TreeHop.

[Arxiv](https://arxiv.org/abs/2504.20114)