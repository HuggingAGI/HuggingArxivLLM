# 面向视觉信息提取的富含关系型视觉文档生成器

发布时间：2025年04月14日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）生成视觉文档，并通过两阶段方法克服现有生成器的限制。它展示了LLMs在视觉文档理解中的具体应用，属于LLM应用类别。` `文档处理` `视觉信息提取`

> Relation-Rich Visual Document Generator for Visual Information Extraction

# 摘要

> 尽管大型语言模型（LLMs）和多模态LLM（MLLMs）在视觉文档理解（VDU）领域取得了进展，但关系丰富的文档中视觉信息提取（VIE）仍然面临布局多样性和训练数据不足的挑战。现有合成文档生成器虽然试图缓解数据稀缺问题，但要么依赖手动设计的布局和模板，要么采用限制布局多样性的基于规则方法。此外，现有布局生成方法仅关注拓扑模式，忽视文本内容，难以生成内容与布局间存在复杂关联的文档。本文提出了一种关系丰富的视觉文档生成器（RIDGE），通过两阶段方法克服这些限制：（1）内容生成，利用LLMs通过层次结构文本格式生成文档内容，捕捉实体类别和关系；（2）内容驱动的布局生成，仅从光学字符识别（OCR）结果中学习生成多样化且合理的布局，无需人工标注。实验结果表明，我们的方法显著提升了文档理解模型在各种VIE基准测试中的性能。代码和模型将在https://github.com/AI-Application-and-Integration-Lab/RIDGE上提供。

> Despite advances in Large Language Models (LLMs) and Multimodal LLMs (MLLMs) for visual document understanding (VDU), visual information extraction (VIE) from relation-rich documents remains challenging due to the layout diversity and limited training data. While existing synthetic document generators attempt to address data scarcity, they either rely on manually designed layouts and templates, or adopt rule-based approaches that limit layout diversity. Besides, current layout generation methods focus solely on topological patterns without considering textual content, making them impractical for generating documents with complex associations between the contents and layouts. In this paper, we propose a Relation-rIch visual Document GEnerator (RIDGE) that addresses these limitations through a two-stage approach: (1) Content Generation, which leverages LLMs to generate document content using a carefully designed Hierarchical Structure Text format which captures entity categories and relationships, and (2) Content-driven Layout Generation, which learns to create diverse, plausible document layouts solely from easily available Optical Character Recognition (OCR) results, requiring no human labeling or annotations efforts. Experimental results have demonstrated that our method significantly enhances the performance of document understanding models on various VIE benchmarks. The code and model will be available at https://github.com/AI-Application-and-Integration-Lab/RIDGE .

[Arxiv](https://arxiv.org/abs/2504.10659)