# # 深度搜索在异构企业数据上的基准测试与性能评估

发布时间：2025年06月29日

`RAG` `信息检索`

> Benchmarking Deep Search over Heterogeneous Enterprise Data

# 摘要

> 我们提出了一种新的基准，用于评估Deep Search——一种现实且复杂的检索增强生成（RAG），需要在多样、稀疏但相关来源中进行多跳推理，同时具备来源感知能力。这些来源包括文档、会议记录、Slack消息、GitHub内容和URL，它们结构各异，常常包含人际互动。我们通过模拟产品规划、开发和支持阶段的业务流程，使用合成数据管道构建了这一基准，生成了具有现实噪声的互联内容以及保证有确切答案的多跳问题。我们发布了包含可回答和不可回答查询的基准，以及包含39,190个企业资料的检索池，支持对长上下文LLM和RAG系统的细粒度评估。实验结果表明，即使是表现最佳的智能体RAG方法，在我们的基准上也仅能达到32.96的平均性能得分。进一步分析表明，检索是主要瓶颈：现有方法难以进行深度搜索并检索所有必要证据。因此，它们常常基于部分上下文进行推理，导致性能显著下降。


> We present a new benchmark for evaluating Deep Search--a realistic and complex form of retrieval-augmented generation (RAG) that requires source-aware, multi-hop reasoning over diverse, sparsed, but related sources. These include documents, meeting transcripts, Slack messages, GitHub, and URLs, which vary in structure and often contain human-to-human interactions. We build it using a synthetic data pipeline that simulates business workflows across product planning, development, and support stages, generating interconnected content with realistic noise and multi-hop questions with guaranteed ground-truth answers. We release our benchmark with both answerable and unanswerable queries, and retrieval pool of 39,190 enterprise artifacts, enabling fine-grained evaluation of long-context LLM and RAG systems. Our experiments reveal that even the best-performing agentic RAG methods achieve an average performance score of 32.96 on our benchmark. With further analysis, we highlight retrieval as the main bottleneck: existing methods struggle to conduct deep searches and retrieve all necessary evidence. Consequently, they often reason over partial context, leading to significant performance degradation.

[Arxiv](https://arxiv.org/abs/2506.23139)