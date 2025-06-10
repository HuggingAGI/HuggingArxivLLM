# # RAG 事件推理：构建增强型事件知识库与证明助手辅助推理

发布时间：2025年06月08日

`RAG` `历史学`

> Reasoning with RAGged events: RAG-Enhanced Event Knowledge Base Construction and reasoning with proof-assistants

# 摘要

> 从叙事文本中提取历史事件的结构化计算表示在手动构建时仍然面临巨大的计算成本。RDF/OWL推理器虽支持基于图的推理，但受限于一阶逻辑片段，难以实现更深入的时间和语义分析。本文提出了一种创新解决方案，通过结合纯基础生成、知识图谱增强和检索增强生成（RAG）三种策略，利用GPT-4、Claude和Llama 3.2等多个大型语言模型（LLMs）开发自动历史事件提取模型。我们采用色诺芬的历史文本进行了全面评估。研究发现，不同增强策略在性能维度上各有侧重：基础生成在覆盖范围和历史广度方面表现最佳，Claude和GPT-4能够提取全面的事件；而RAG增强则在精度方面更具优势，显著提升了坐标准确性和元数据完整性。模型架构决定了增强策略的敏感性：大型模型展现出强大的基线性能，并通过逐步改进的RAG策略实现提升，而Llama 3.2则表现出从竞争性性能到完全失败的巨大波动。此外，我们开发了一个自动化翻译管道，将提取的RDF表示转换为Coq证明助手规格，从而实现了超越RDF能力的高阶推理，包括多步因果验证、带公元前日期的时间算术以及关于历史因果关系的形式证明。Coq的形式化验证表明，RAG发现的事件类型代表了合法的领域特定语义结构，而非本体论违规。

> Extracting structured computational representations of historical events from narrative text remains computationally expensive when constructed manually. While RDF/OWL reasoners enable graph-based reasoning, they are limited to fragments of first-order logic, preventing deeper temporal and semantic analysis. This paper addresses both challenges by developing automatic historical event extraction models using multiple LLMs (GPT-4, Claude, Llama 3.2) with three enhancement strategies: pure base generation, knowledge graph enhancement, and Retrieval-Augmented Generation (RAG). We conducted comprehensive evaluations using historical texts from Thucydides. Our findings reveal that enhancement strategies optimize different performance dimensions rather than providing universal improvements. For coverage and historical breadth, base generation achieves optimal performance with Claude and GPT-4 extracting comprehensive events. However, for precision, RAG enhancement improves coordinate accuracy and metadata completeness. Model architecture fundamentally determines enhancement sensitivity: larger models demonstrate robust baseline performance with incremental RAG improvements, while Llama 3.2 shows extreme variance from competitive performance to complete failure. We then developed an automated translation pipeline converting extracted RDF representations into Coq proof assistant specifications, enabling higher-order reasoning beyond RDF capabilities including multi-step causal verification, temporal arithmetic with BC dates, and formal proofs about historical causation. The Coq formalization validates that RAG-discovered event types represent legitimate domain-specific semantic structures rather than ontological violations.

[Arxiv](https://arxiv.org/abs/2506.07042)