# Q2E：零样本多语言文本到视频检索的查询到事件分解方法

发布时间：2025年06月11日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）和视觉语言模型（VLMs）进行多模态知识提取和应用，特别是在视频检索方面的应用。研究提出了一种名为Q2E的查询到事件分解方法，并展示了其在多语言、多模态场景中的有效性。因此，这篇论文属于LLM应用类别。` `视频检索` `多模态`

> Q2E: Query-to-Event Decomposition for Zero-Shot Multilingual Text-to-Video Retrieval

# 摘要

> 近期研究在从大型语言模型（LLMs）和视觉语言模型（VLMs）中提取和利用参数化知识方面表现出色。本研究探讨如何通过自动提取复杂现实事件的潜在参数化知识，提升相关视频的识别与检索效果。我们提出了一种名为Q2E的查询到事件分解方法，适用于零样本多语言文本到视频检索，且在不同数据集、领域、LLMs或VLMs间具有良好的适应性。通过利用LLMs和VLMs中的嵌入知识对查询进行分解，我们能够提升对原本过于简化的用户查询的理解。此外，我们展示了该方法在视觉和语音输入中的应用。为了整合多样的多模态知识，我们采用了基于熵的融合评分方法进行零样本融合。通过在两个多样化数据集和多个检索指标上的评估，Q2E在多个最先进的基线方法中表现优异。我们的研究还表明，整合音频信息可显著提升文本到视频的检索性能。我们已发布代码和数据，以支持未来研究。

> Recent approaches have shown impressive proficiency in extracting and leveraging parametric knowledge from Large-Language Models (LLMs) and Vision-Language Models (VLMs). In this work, we consider how we can improve the identification and retrieval of videos related to complex real-world events by automatically extracting latent parametric knowledge about those events. We present Q2E: a Query-to-Event decomposition method for zero-shot multilingual text-to-video retrieval, adaptable across datasets, domains, LLMs, or VLMs. Our approach demonstrates that we can enhance the understanding of otherwise overly simplified human queries by decomposing the query using the knowledge embedded in LLMs and VLMs. We additionally show how to apply our approach to both visual and speech-based inputs. To combine this varied multimodal knowledge, we adopt entropy-based fusion scoring for zero-shot fusion. Through evaluations on two diverse datasets and multiple retrieval metrics, we demonstrate that Q2E outperforms several state-of-the-art baselines. Our evaluation also shows that integrating audio information can significantly improve text-to-video retrieval. We have released code and data for future research.

[Arxiv](https://arxiv.org/abs/2506.10202)