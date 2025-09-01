# KG-CQR：基于知识图谱结构化关系表示的上下文查询检索

发布时间：2025年08月29日

`RAG` `基础理论`

> KG-CQR: Leveraging Structured Relation Representations in Knowledge Graphs for Contextual Query Retrieval

# 摘要

> 知识图谱（KGs）与大型语言模型（LLMs）的融合为提升检索增强生成（RAG）系统的检索阶段带来了巨大潜力。本研究提出了KG-CQR——一种新型上下文查询检索（CQR）框架，它利用以语料库为中心的KG丰富复杂输入查询的上下文表示，从而增强检索阶段。不同于现有方法主要解决语料库级上下文缺失问题，KG-CQR聚焦于通过结构化关系表示来丰富查询——它会提取并补全相关的KG子图，进而生成语义丰富的查询上下文。KG-CQR包含子图提取、补全及上下文生成模块，是一个模型无关的流水线，可确保在不同规模的LLM上无需额外训练便能实现扩展。在RAGBench和MultiHop-RAG数据集上的实验结果显示，KG-CQR性能卓越：相较于强大的基线模型，其mAP提升4-6%，Recall@25提升2-3%。此外，在多跳问答等挑战性RAG任务的评估中发现，整合KG-CQR后，系统在检索有效性上的表现持续优于现有基线。

> The integration of knowledge graphs (KGs) with large language models (LLMs) offers significant potential to improve the retrieval phase of retrieval-augmented generation (RAG) systems. In this study, we propose KG-CQR, a novel framework for Contextual Query Retrieval (CQR) that enhances the retrieval phase by enriching the contextual representation of complex input queries using a corpus-centric KG. Unlike existing methods that primarily address corpus-level context loss, KG-CQR focuses on query enrichment through structured relation representations, extracting and completing relevant KG subgraphs to generate semantically rich query contexts. Comprising subgraph extraction, completion, and contextual generation modules, KG-CQR operates as a model-agnostic pipeline, ensuring scalability across LLMs of varying sizes without additional training. Experimental results on RAGBench and MultiHop-RAG datasets demonstrate KG-CQR's superior performance, achieving a 4-6% improvement in mAP and a 2-3% improvement in Recall@25 over strong baseline models. Furthermore, evaluations on challenging RAG tasks such as multi-hop question answering show that, by incorporating KG-CQR, the performance consistently outperforms the existing baseline in terms of retrieval effectiveness

[Arxiv](https://arxiv.org/abs/2508.20417)