# 视觉文本处理：全面综述与统一评估

发布时间：2025年04月30日

`LLM应用` `计算机视觉` `视觉文本处理`

> Visual Text Processing: A Comprehensive Review and Unified Evaluation

# 摘要

> 视觉文本在文档和场景图像中扮演着重要角色，它不仅承载着丰富的语义信息，还在计算机视觉领域引发了广泛关注。在基础模型的推动下，视觉文本处理领域取得了显著进展，从传统的文本检测和识别，扩展到文本图像重建和图像操作等创新任务。然而，文本的独特属性仍然带来了不少挑战。要想开发出更强大的视觉文本处理模型，就必须深入挖掘并有效利用这些独特的文本特征。在本综述中，我们从多角度全面剖析了视觉文本处理的最新进展，重点关注两大核心问题：一是各类视觉文本任务中最适合的文本特征是什么，二是如何将这些独特特征高效整合到处理框架中。此外，我们推出了 VTPBench，一个涵盖广泛视觉文本数据集的新基准。借助多模态大型语言模型（MLLMs）强大的视觉质量评估能力，我们还提出了 VTPScore 这一创新评估指标，旨在确保评估的公平与可靠。通过对20多种特定模型的实证研究，我们发现当前技术仍有巨大的提升空间。我们希望这项研究能够成为推动视觉文本处理领域未来探索与创新的重要资源。相关代码和数据仓库已开放，地址为 https://github.com/shuyansy/Visual-Text-Processing-survey。

> Visual text is a crucial component in both document and scene images, conveying rich semantic information and attracting significant attention in the computer vision community. Beyond traditional tasks such as text detection and recognition, visual text processing has witnessed rapid advancements driven by the emergence of foundation models, including text image reconstruction and text image manipulation. Despite significant progress, challenges remain due to the unique properties that differentiate text from general objects. Effectively capturing and leveraging these distinct textual characteristics is essential for developing robust visual text processing models. In this survey, we present a comprehensive, multi-perspective analysis of recent advancements in visual text processing, focusing on two key questions: (1) What textual features are most suitable for different visual text processing tasks? (2) How can these distinctive text features be effectively incorporated into processing frameworks? Furthermore, we introduce VTPBench, a new benchmark that encompasses a broad range of visual text processing datasets. Leveraging the advanced visual quality assessment capabilities of multimodal large language models (MLLMs), we propose VTPScore, a novel evaluation metric designed to ensure fair and reliable evaluation. Our empirical study with more than 20 specific models reveals substantial room for improvement in the current techniques. Our aim is to establish this work as a fundamental resource that fosters future exploration and innovation in the dynamic field of visual text processing. The relevant repository is available at https://github.com/shuyansy/Visual-Text-Processing-survey.

[Arxiv](https://arxiv.org/abs/2504.21682)