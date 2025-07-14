# 视觉语义描述生成：多模态大语言模型在图像-文本匹配中的应用

发布时间：2025年07月11日

`LLM应用`

> Visual Semantic Description Generation with MLLMs for Image-Text Matching

# 摘要

> 图像-文本匹配（ITM）致力于解决视觉与文本模态统一这一核心难题。由于图像特征是连续高维的，而文本是离散结构化的，二者在表征上存在本质差异。我们提出了一种创新框架，通过将多模态大语言模型（MLLMs）作为视觉语义解析器，有效弥合了模态间差距。通过生成丰富的视觉语义描述（VSD），MLLMs为跨模态对齐提供了语义锚点。我们的方法包含两大核心模块：实例级对齐通过融合视觉特征与VSD，显著增强图像表达的语义丰富性；原型级对齐则通过VSD聚类，确保类别级别的一致性。这些模块可轻松集成到现有ITM模型中。实验结果表明，在Flickr30K和MSCOCO数据集上，该方法实现了显著的性能提升。此外，该方法在新闻和遥感等跨领域ITM任务中也展现了卓越的零样本泛化能力。项目代码和模型检查点已开源，地址为https://github.com/Image-Text-Matching/VSD。

> Image-text matching (ITM) aims to address the fundamental challenge of aligning visual and textual modalities, which inherently differ in their representations, continuous, high-dimensional image features vs. discrete, structured text. We propose a novel framework that bridges the modality gap by leveraging multimodal large language models (MLLMs) as visual semantic parsers. By generating rich Visual Semantic Descriptions (VSD), MLLMs provide semantic anchor that facilitate cross-modal alignment. Our approach combines: (1) Instance-level alignment by fusing visual features with VSD to enhance the linguistic expressiveness of image representations, and (2) Prototype-level alignment through VSD clustering to ensure category-level consistency. These modules can be seamlessly integrated into existing ITM models. Extensive experiments on Flickr30K and MSCOCO demonstrate substantial performance improvements. The approach also exhibits remarkable zero-shot generalization to cross-domain tasks, including news and remote sensing ITM. The code and model checkpoints are available at https://github.com/Image-Text-Matching/VSD.

[Arxiv](https://arxiv.org/abs/2507.08590)