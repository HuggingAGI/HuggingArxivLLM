# # 开发基于视觉增强的问答系统，结合可扩展的视觉嵌入检索与后交互重排序器

发布时间：2025年07月16日

`RAG` `信息抽取` `问答系统`

> Developing Visual Augmented Q&A System using Scalable Vision Embedding Retrieval & Late Interaction Re-ranker

# 摘要

> 传统信息抽取系统在仅使用文本的语言模型时面临挑战，因为它们忽略了如表格、图表、图像等信息图（信息的视觉元素），而这些元素常用于传达复杂信息。多模态大语言模型（MLLM）则面临在海量数据中寻找关键信息的难题，即要么需要处理更长的上下文长度，要么需要在大量文档中进行搜索。基于视觉语言模型的晚交互机制在检索增强的视觉问答任务中表现出色。然而，将其应用于基于RAG的多模态问答任务时仍存在一些挑战。首先，许多广泛使用的向量数据库不支持原生多向量检索。其次，晚交互机制需要额外计算，这会增加空间占用并可能阻碍企业级应用。最后，当前的晚交互机制尚未充分利用近似最近邻搜索索引方法来大幅提高检索速度。本文探讨了一种实用的方法，旨在在不牺牲性能质量的前提下，使视觉检索过程具备可扩展性和高效性。我们提出了一种多步骤的自定义实现方案，结合了广泛采用的混合搜索（元数据与嵌入）和最新的晚交互重排序器，以检索出最佳匹配页面。最后，多模态大语言模型（MLLM）被提示为阅读器，从上下文化的最佳匹配页面中生成答案。通过实验，我们发现所提出的方案具有可扩展性（显著提升速度）和稳定性（不降低性能质量），因此可以作为企业级生产系统使用。

> Traditional information extraction systems face challenges with text only language models as it does not consider infographics (visual elements of information) such as tables, charts, images etc. often used to convey complex information to readers. Multimodal LLM (MLLM) face challenges of finding needle in the haystack problem i.e., either longer context length or substantial number of documents as search space. Late interaction mechanism over visual language models has shown state of the art performance in retrieval-based vision augmented Q&A tasks. There are yet few challenges using it for RAG based multi-modal Q&A. Firstly, many popular and widely adopted vector databases do not support native multi-vector retrieval. Secondly, late interaction requires computation which inflates space footprint and can hinder enterprise adoption. Lastly, the current state of late interaction mechanism does not leverage the approximate neighbor search indexing methods for large speed ups in retrieval process. This paper explores a pragmatic approach to make vision retrieval process scalable and efficient without compromising on performance quality. We propose multi-step custom implementation utilizing widely adopted hybrid search (metadata & embedding) and state of the art late interaction re-ranker to retrieve best matching pages. Finally, MLLM are prompted as reader to generate answers from contextualized best matching pages. Through experiments, we observe that the proposed design is scalable (significant speed up) and stable (without degrading performance quality), hence can be used as production systems at enterprises.

[Arxiv](https://arxiv.org/abs/2507.12378)