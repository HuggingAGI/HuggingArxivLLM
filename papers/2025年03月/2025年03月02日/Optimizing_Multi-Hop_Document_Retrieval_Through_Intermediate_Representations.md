# # 借助中间表示优化多跳文档检索

发布时间：2025年03月02日

`RAG` `问答系统`

> Optimizing Multi-Hop Document Retrieval Through Intermediate Representations

# 摘要

> 在处理复杂查询，尤其是多跳问题时，检索增强生成（RAG）面临诸多挑战。虽然一些方法通过迭代生成内部查询并检索外部文档来应对多跳问题，但这些方法计算开销较高。我们发现，在分层推理过程中，大型语言模型存在一个三阶段信息处理模式：提取、处理和后续提取。这一发现表明，中间层的表示包含更丰富的信息。基于此，我们提出了分层RAG（L-RAG）。与专注于生成新内部查询的方法不同，L-RAG利用中间层的表示，这些表示捕获了下一步信息，从而检索外部知识。L-RAG在性能上与多步方法相当，同时保持了与标准RAG相似的推理开销。实验结果表明，L-RAG在开放领域多跳问答数据集（包括MuSiQue、HotpotQA和2WikiMultiHopQA）上优于现有RAG方法。代码可在https://anonymous.4open.science/r/L-RAG-ADD5/获取。

> Retrieval-augmented generation (RAG) encounters challenges when addressing complex queries, particularly multi-hop questions. While several methods tackle multi-hop queries by iteratively generating internal queries and retrieving external documents, these approaches are computationally expensive. In this paper, we identify a three-stage information processing pattern in LLMs during layer-by-layer reasoning, consisting of extraction, processing, and subsequent extraction steps. This observation suggests that the representations in intermediate layers contain richer information compared to those in other layers. Building on this insight, we propose Layer-wise RAG (L-RAG). Unlike prior methods that focus on generating new internal queries, L-RAG leverages intermediate representations from the middle layers, which capture next-hop information, to retrieve external knowledge. L-RAG achieves performance comparable to multi-step approaches while maintaining inference overhead similar to that of standard RAG. Experimental results show that L-RAG outperforms existing RAG methods on open-domain multi-hop question-answering datasets, including MuSiQue, HotpotQA, and 2WikiMultiHopQA. The code is available in https://anonymous.4open.science/r/L-RAG-ADD5/

[Arxiv](https://arxiv.org/abs/2503.04796)