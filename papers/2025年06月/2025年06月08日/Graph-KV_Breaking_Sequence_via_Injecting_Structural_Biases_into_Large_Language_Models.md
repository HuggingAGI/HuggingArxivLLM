# Graph-KV: 向大型语言模型融入结构偏差以突破序列限制

发布时间：2025年06月08日

`LLM理论` `信息检索`

> Graph-KV: Breaking Sequence via Injecting Structural Biases into Large Language Models

# 摘要

> 现代大型语言模型（LLMs）本质上是自回归的，输入需序列化为平坦序列，而这一过程阻碍了模型在结构化任务中的表现，如检索增强生成（RAG）和处理原生图结构数据，这些任务中段间依赖至关重要。我们提出了Graph-KV框架，旨在突破这一限制。Graph-KV利用文本片段的KV缓存作为浓缩表示，并通过结构归纳偏置管理交互。在该框架中，'目标'片段仅关注指定的'源'片段的KV缓存，而非整个序列的前序片段。这种方法生成图结构块掩码，稀疏化注意力机制，并在LLM中实现类似消息传递的步骤。此外，为目标和源片段设计的位置编码减少了位置偏差和上下文窗口消耗。我们在三个场景中评估了Graph-KV：涵盖直接推理、多跳推理和长文档理解的七个RAG基准；全新的Arxiv-QA任务，其中科学论文以引文ego图形式构建；以及引文网络中的论文主题分类。通过减少位置偏差并利用结构归纳偏置，Graph-KV在多种设置下显著超越基线模型，包括标准的高成本序列编码。代码和Graph-KV数据已公开可用。

> Modern large language models (LLMs) are inherently auto-regressive, requiring input to be serialized into flat sequences regardless of their structural dependencies. This serialization hinders the model's ability to leverage structural inductive biases, especially in tasks such as retrieval-augmented generation (RAG) and reasoning on data with native graph structures, where inter-segment dependencies are crucial. We introduce Graph-KV with the potential to overcome this limitation. Graph-KV leverages the KV-cache of text segments as condensed representations and governs their interaction through structural inductive biases. In this framework, 'target' segments selectively attend only to the KV-caches of their designated 'source' segments, rather than all preceding segments in a serialized sequence. This approach induces a graph-structured block mask, sparsifying attention and enabling a message-passing-like step within the LLM. Furthermore, strategically allocated positional encodings for source and target segments reduce positional bias and context window consumption. We evaluate Graph-KV across three scenarios: (1) seven RAG benchmarks spanning direct inference, multi-hop reasoning, and long-document understanding; (2) Arxiv-QA, a novel academic paper QA task with full-text scientific papers structured as citation ego-graphs; and (3) paper topic classification within a citation network. By effectively reducing positional bias and harnessing structural inductive biases, Graph-KV substantially outperforms baselines, including standard costly sequential encoding, across various settings. Code and the Graph-KV data are publicly available.

[Arxiv](https://arxiv.org/abs/2506.07334)