# MMGraphRAG：借助可解释的多模态知识图谱，为视觉与语言搭建桥梁

发布时间：2025年07月28日

`RAG` `知识图谱` `多模态`

> MMGraphRAG: Bridging Vision and Language with Interpretable Multimodal Knowledge Graphs

# 摘要

> 检索增强生成（RAG）通过从外部知识库中检索相关信息来提升语言模型的生成能力。但传统RAG方法却有个短板——它们无法有效利用多模态信息。多模态RAG方法通过将图像和文本映射到共享嵌入空间进行融合来弥补这一不足，但它们仍然无法捕捉知识结构和模态间的逻辑链条。此外，这些方法需要针对特定任务进行大规模训练，导致泛化能力有限。

为了解决这些问题，我们提出了MMGraphRAG。它通过场景图优化视觉内容，并结合基于文本的知识图谱构建多模态知识图谱（MMKG）。该方法采用谱聚类实现跨模态实体链接，并沿推理路径检索上下文以引导生成过程。实验结果显示，MMGraphRAG在DocBench和MMLongBench数据集上达到了当前最优的性能水平，展现了强大的领域适应能力和清晰的推理路径。

> Retrieval-Augmented Generation (RAG) enhances language model generation by retrieving relevant information from external knowledge bases. However, conventional RAG methods face the issue of missing multimodal information. Multimodal RAG methods address this by fusing images and text through mapping them into a shared embedding space, but they fail to capture the structure of knowledge and logical chains between modalities. Moreover, they also require large-scale training for specific tasks, resulting in limited generalizing ability. To address these limitations, we propose MMGraphRAG, which refines visual content through scene graphs and constructs a multimodal knowledge graph (MMKG) in conjunction with text-based KG. It employs spectral clustering to achieve cross-modal entity linking and retrieves context along reasoning paths to guide the generative process. Experimental results show that MMGraphRAG achieves state-of-the-art performance on the DocBench and MMLongBench datasets, demonstrating strong domain adaptability and clear reasoning paths.

[Arxiv](https://arxiv.org/abs/2507.20804)