# 超越Logit Lens：助力视觉语言模型 (VLMs) 实现稳健幻觉检测与定位的上下文嵌入方法

发布时间：2025年02月19日

`LLM应用` `人工智能` `计算机视觉`

> Beyond Logit Lens: Contextual Embeddings for Robust Hallucination Detection & Grounding in VLMs

# 摘要

> 大型多模态模型（LMMs）的迅猛发展显著推动了多模态理解的进步，通过整合大型语言模型（LLMs）的语言能力与特定模态的编码器。然而，LMMs始终面临幻觉问题的困扰，这严重制约了其可靠性和应用范围。传统方法通常依赖昂贵的训练或外部模型来检测和缓解幻觉，而近期基于内部模型特征的方法则提供了一个更具潜力的解决方案。本文深入评估了当前最先进的无训练技术——logit lens——在处理泛化视觉幻觉时的局限性。我们提出了改进的ContextualLens方法，该方法利用LMMs中间层的上下文令牌嵌入，显著提升了幻觉检测和定位的性能，涵盖动作、OCR等多种类别。同时，该方法在空间关系和属性比较等需要上下文理解的任务中也表现出色。我们的新型定位技术生成了高度精确的边界框，成功实现了从零样本目标分割到基于定位的视觉问答的转变。我们的研究为构建更可靠、更可解释的多模态模型奠定了坚实基础。

> The rapid development of Large Multimodal Models (LMMs) has significantly advanced multimodal understanding by harnessing the language abilities of Large Language Models (LLMs) and integrating modality-specific encoders. However, LMMs are plagued by hallucinations that limit their reliability and adoption. While traditional methods to detect and mitigate these hallucinations often involve costly training or rely heavily on external models, recent approaches utilizing internal model features present a promising alternative. In this paper, we critically assess the limitations of the state-of-the-art training-free technique, the logit lens, in handling generalized visual hallucinations. We introduce ContextualLens, a refined method that leverages contextual token embeddings from middle layers of LMMs. This approach significantly improves hallucination detection and grounding across diverse categories, including actions and OCR, while also excelling in tasks requiring contextual understanding, such as spatial relations and attribute comparison. Our novel grounding technique yields highly precise bounding boxes, facilitating a transition from Zero-Shot Object Segmentation to Grounded Visual Question Answering. Our contributions pave the way for more reliable and interpretable multimodal models.

[Arxiv](https://arxiv.org/abs/2411.19187)