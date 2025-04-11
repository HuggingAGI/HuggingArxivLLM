# TokenFocus-VQA：位置感知聚焦与多视角聚合提升LVLM文本到图像对齐

发布时间：2025年04月10日

`LLM应用` `计算机视觉` `图像生成`

> TokenFocus-VQA: Enhancing Text-to-Image Alignment with Position-Aware Focus and Multi-Perspective Aggregations on LVLMs

# 摘要

> 尽管文本到图像（T2I）生成模型近年来取得了显著进展，现有的视觉-语言对齐评估方法在细粒度语义匹配上仍面临挑战。当前基于全局相似度指标的方法往往忽视了文本描述与视觉内容之间关键的token级别对应关系。为此，我们提出了TokenFocus-VQA，这是一种全新的评估框架，通过视觉问答（VQA）范式结合位置特定概率优化，利用大型视觉-语言模型（LVLMs）。我们的关键创新在于设计了一种基于token的损失函数，该函数有选择性地关注与关键语义元素相对应的预定义词汇位置的概率分布，从而能够精确测量细粒度语义对齐。该框架进一步整合了集成学习技术，从多种LVLM架构中聚合多角度评估，从而实现进一步的性能提升。在NTIRE 2025 T2I质量评估挑战Track 1上的评估表明，我们的TokenFocus-VQA在公共评估中获得第2名（0.8445，仅比第1名低0.0001），在官方私有测试集上获得第2名（0.8426），相较于传统评估方法，它在捕捉微妙的文本-图像对应关系方面表现出色。


> While text-to-image (T2I) generation models have achieved remarkable progress in recent years, existing evaluation methodologies for vision-language alignment still struggle with the fine-grained semantic matching. Current approaches based on global similarity metrics often overlook critical token-level correspondences between textual descriptions and visual content. To this end, we present TokenFocus-VQA, a novel evaluation framework that leverages Large Vision-Language Models (LVLMs) through visual question answering (VQA) paradigm with position-specific probability optimization. Our key innovation lies in designing a token-aware loss function that selectively focuses on probability distributions at pre-defined vocabulary positions corresponding to crucial semantic elements, enabling precise measurement of fine-grained semantical alignment. The proposed framework further integrates ensemble learning techniques to aggregate multi-perspective assessments from diverse LVLMs architectures, thereby achieving further performance enhancement. Evaluated on the NTIRE 2025 T2I Quality Assessment Challenge Track 1, our TokenFocus-VQA ranks 2nd place (0.8445, only 0.0001 lower than the 1st method) on public evaluation and 2nd place (0.8426) on the official private test set, demonstrating superiority in capturing nuanced text-image correspondences compared to conventional evaluation methods.

[Arxiv](https://arxiv.org/abs/2504.07556)