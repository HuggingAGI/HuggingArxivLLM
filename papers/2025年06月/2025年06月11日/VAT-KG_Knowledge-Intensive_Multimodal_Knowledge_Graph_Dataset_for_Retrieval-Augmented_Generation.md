# VAT-KG：面向检索增强生成的知识密集型多模态知识图谱数据集

发布时间：2025年06月11日

`RAG` `多模态` `知识图谱`

> VAT-KG: Knowledge-Intensive Multimodal Knowledge Graph Dataset for Retrieval-Augmented Generation

# 摘要

> 多模态知识图谱（MMKGs）在补充多模态大型语言模型（MLLMs）的隐性知识并借助检索增强生成（RAG）实现更扎实推理方面发挥着关键作用。然而，现有MMKGs的局限性在于：它们通常基于增强现有知识图谱构建，导致知识覆盖范围过时或不完整，且往往仅支持文本和视觉等有限模态。这些限制使其难以适应更广泛的任务需求，尤其是在MLLMs逐渐转向视频和音频等更丰富模态的背景下。为此，我们提出了视觉-音频-文本知识图谱（VAT-KG），这是首个以概念为中心、涵盖视觉、音频和文本信息的知识密集型多模态知识图谱，每个三元组均与多模态数据关联并辅以详尽的概念描述。我们的构建流程通过严格的过滤与对齐步骤，确保多模态数据与细粒度语义的跨模态对齐，从而实现从任意多模态数据集自动构建MMKGs。此外，我们还推出了一种新型多模态RAG框架，能够根据任意模态的查询检索详细的概念级别知识。实验结果表明，VAT-KG在多模态任务中的表现显著优于现有方法，充分证明了其在统一与利用多模态知识方面的实用价值。

> Multimodal Knowledge Graphs (MMKGs), which represent explicit knowledge across multiple modalities, play a pivotal role by complementing the implicit knowledge of Multimodal Large Language Models (MLLMs) and enabling more grounded reasoning via Retrieval Augmented Generation (RAG). However, existing MMKGs are generally limited in scope: they are often constructed by augmenting pre-existing knowledge graphs, which restricts their knowledge, resulting in outdated or incomplete knowledge coverage, and they often support only a narrow range of modalities, such as text and visual information. These limitations reduce their extensibility and applicability to a broad range of multimodal tasks, particularly as the field shifts toward richer modalities such as video and audio in recent MLLMs. Therefore, we propose the Visual-Audio-Text Knowledge Graph (VAT-KG), the first concept-centric and knowledge-intensive multimodal knowledge graph that covers visual, audio, and text information, where each triplet is linked to multimodal data and enriched with detailed descriptions of concepts. Specifically, our construction pipeline ensures cross-modal knowledge alignment between multimodal data and fine-grained semantics through a series of stringent filtering and alignment steps, enabling the automatic generation of MMKGs from any multimodal dataset. We further introduce a novel multimodal RAG framework that retrieves detailed concept-level knowledge in response to queries from arbitrary modalities. Experiments on question answering tasks across various modalities demonstrate the effectiveness of VAT-KG in supporting MLLMs, highlighting its practical value in unifying and leveraging multimodal knowledge.

[Arxiv](https://arxiv.org/abs/2506.21556)