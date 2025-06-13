# TableRAG：面向异构文档推理的检索增强生成框架

发布时间：2025年06月12日

`RAG` `问答系统` `数据处理`

> TableRAG: A Retrieval Augmented Generation Framework for Heterogeneous Document Reasoning

# 摘要

> 检索增强生成（RAG）在开放领域问答任务中表现优异，但现有方法在处理包含文本与表格的异构文档时存在明显局限。传统的展平表格和分块策略不仅破坏了表格结构，还导致信息丢失，影响了大型语言模型在复杂查询中的推理能力。为此，我们提出TableRAG——一个融合文本理解与复杂表格操作的混合框架。TableRAG通过以下四个步骤迭代运行：上下文感知的查询分解、文本检索、SQL编程与执行，以及组合中间答案生成。同时，我们开发了HeteQA，一个专为评估多跳异构推理能力设计的新基准。实验结果表明，TableRAG在公共数据集和HeteQA基准上均显著优于现有方法，树立了异构文档问答任务的新技术水平。TableRAG已在GitHub上开源，地址为https://github.com/yxh-y/TableRAG/tree/main。


> Retrieval-Augmented Generation (RAG) has demonstrated considerable effectiveness in open-domain question answering. However, when applied to heterogeneous documents, comprising both textual and tabular components, existing RAG approaches exhibit critical limitations. The prevailing practice of flattening tables and chunking strategies disrupts the intrinsic tabular structure, leads to information loss, and undermines the reasoning capabilities of LLMs in multi-hop, global queries. To address these challenges, we propose TableRAG, an hybrid framework that unifies textual understanding and complex manipulations over tabular data. TableRAG iteratively operates in four steps: context-sensitive query decomposition, text retrieval, SQL programming and execution, and compositional intermediate answer generation. We also develop HeteQA, a novel benchmark designed to evaluate the multi-hop heterogeneous reasoning capabilities. Experimental results demonstrate that TableRAG consistently outperforms existing baselines on both public datasets and our HeteQA, establishing a new state-of-the-art for heterogeneous document question answering. We release TableRAG at https://github.com/yxh-y/TableRAG/tree/main.

[Arxiv](https://arxiv.org/abs/2506.10380)