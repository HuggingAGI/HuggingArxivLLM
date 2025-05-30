# 立场报告：元数据增强模型——融合神经网络与语义知识图谱，应用于文化遗产保护

发布时间：2025年05月29日

`LLM应用` `文化遗产` `文化遗产数字化`

> Position Paper: Metadata Enrichment Model: Integrating Neural Networks and Semantic Knowledge Graphs for Cultural Heritage Applications

# 摘要

> 文化遗产数字化为研究开辟了新方向，但元数据的匮乏却阻碍了其在可访问性、互操作性和跨机构协作中的潜力。近年来，神经网络模型如YOLOv11和Detectron2在视觉数据分析领域带来了革命性变化，但它们在特定领域的文化艺术品（如手稿和早期印刷品）上的应用仍受限于缺乏针对结构特征提取和语义互操作性的方法。本文认为，神经网络与语义技术的结合代表了文化遗产数字化过程中的范式转变。我们提出了元数据增强模型（MEM），这是一个结合了微调计算机视觉模型、大型语言模型（LLMs）和结构化知识图谱的概念框架，旨在为数字化藏品丰富元数据。MEM的核心创新是多层视觉机制（MVM），这一迭代过程通过动态检测嵌套特征（如印章中的文字或邮票中的图像）来提升视觉分析。为了展示MEM的潜力，我们将其应用于 Jagiellonian 数字图书馆的早期印刷品数据集，并发布了一个包含105页手稿的标注数据集。我们探讨了在实际GLAM机构中使用MEM面临的技术挑战，包括领域特定的微调需求、与链接数据标准的元数据调整以及计算成本。我们将其呈现为一种灵活且可扩展的方法论。本文探讨了人工智能和语义网技术如何推动文化遗产研究，并在实践中应用这些技术。

> The digitization of cultural heritage collections has opened new directions for research, yet the lack of enriched metadata poses a substantial challenge to accessibility, interoperability, and cross-institutional collaboration. In several past years neural networks models such as YOLOv11 and Detectron2 have revolutionized visual data analysis, but their application to domain-specific cultural artifacts - such as manuscripts and incunabula - remains limited by the absence of methodologies that address structural feature extraction and semantic interoperability. In this position paper, we argue, that the integration of neural networks with semantic technologies represents a paradigm shift in cultural heritage digitization processes. We present the Metadata Enrichment Model (MEM), a conceptual framework designed to enrich metadata for digitized collections by combining fine-tuned computer vision models, large language models (LLMs) and structured knowledge graphs. The Multilayer Vision Mechanism (MVM) appears as the key innovation of MEM. This iterative process improves visual analysis by dynamically detecting nested features, such as text within seals or images within stamps. To expose MEM's potential, we apply it to a dataset of digitized incunabula from the Jagiellonian Digital Library and release a manually annotated dataset of 105 manuscript pages. We examine the practical challenges of MEM's usage in real-world GLAM institutions, including the need for domain-specific fine-tuning, the adjustment of enriched metadata with Linked Data standards and computational costs. We present MEM as a flexible and extensible methodology. This paper contributes to the discussion on how artificial intelligence and semantic web technologies can advance cultural heritage research, and also use these technologies in practice.

[Arxiv](https://arxiv.org/abs/2505.23543)