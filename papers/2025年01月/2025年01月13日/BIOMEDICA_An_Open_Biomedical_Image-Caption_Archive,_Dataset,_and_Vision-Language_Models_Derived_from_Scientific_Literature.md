# BIOMEDICA: 一个开放的生物医学图像-描述存档、数据集及基于科学文献的视觉-语言模型

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了视觉语言模型（VLMs）在生物医学领域的应用，特别是通过构建一个大规模的多模态数据集（BIOMEDICA）来训练和改进VLMs。论文还提到了一套通过流式传输在BIOMEDICA数据集上持续预训练的CLIP风格模型（BMCA-CLIP），并展示了这些模型在多个生物医学任务中的性能提升。这些内容主要涉及LLM（大型语言模型）在实际应用中的使用和改进，因此分类为“LLM应用”是合适的。` `生物医学` `计算机视觉`

> BIOMEDICA: An Open Biomedical Image-Caption Archive, Dataset, and Vision-Language Models Derived from Scientific Literature

# 摘要

> # 摘要
视觉语言模型（VLMs）的发展依赖于大规模且多样化的多模态数据集。然而，由于缺乏跨生物学和医学的注释且公开可访问的数据集，通用生物医学VLMs的进展受到限制。现有研究多局限于狭窄领域，未能涵盖科学文献中完整的生物医学知识多样性。为此，我们推出了BIOMEDICA，一个可扩展的开源框架，用于提取、注释和序列化PubMed Central开放获取子集的全部内容，形成一个易于使用且公开可访问的数据集。该框架生成了一个包含超过2400万独特图像-文本对的综合档案，数据来自600多万篇文章，并提供了元数据和专家注释。我们通过发布BMCA-CLIP展示了该资源的实用性和可访问性，这是一套通过流式传输在BIOMEDICA数据集上持续预训练的CLIP风格模型，无需本地下载27 TB数据。我们的模型在40个任务中平均实现了最先进的性能，涵盖病理学、放射学、眼科、皮肤病学、外科、分子生物学、寄生虫学和细胞生物学，零样本分类平均提升6.56%（皮肤病学和眼科分别高达29.8%和17.5%），图像-文本检索表现更强，同时计算资源消耗减少10倍。为促进可重复性和合作，我们向研究社区公开了代码库和数据集。

> The development of vision-language models (VLMs) is driven by large-scale and diverse multimodal datasets. However, progress toward generalist biomedical VLMs is limited by the lack of annotated, publicly accessible datasets across biology and medicine. Existing efforts are restricted to narrow domains, missing the full diversity of biomedical knowledge encoded in scientific literature. To address this gap, we introduce BIOMEDICA, a scalable, open-source framework to extract, annotate, and serialize the entirety of the PubMed Central Open Access subset into an easy-to-use, publicly accessible dataset.Our framework produces a comprehensive archive with over 24 million unique image-text pairs from over 6 million articles. Metadata and expert-guided annotations are also provided. We demonstrate the utility and accessibility of our resource by releasing BMCA-CLIP, a suite of CLIP-style models continuously pre-trained on the BIOMEDICA dataset via streaming, eliminating the need to download 27 TB of data locally.On average, our models achieve state-of-the-art performance across 40 tasks - spanning pathology, radiology, ophthalmology, dermatology, surgery, molecular biology, parasitology, and cell biology - excelling in zero-shot classification with a 6.56% average improvement (as high as 29.8% and 17.5% in dermatology and ophthalmology, respectively), and stronger image-text retrieval, all while using 10x less compute. To foster reproducibility and collaboration, we release our codebase and dataset for the broader research community.

[Arxiv](https://arxiv.org/abs/2501.07171)