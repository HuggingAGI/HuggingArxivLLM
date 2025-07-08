# # 基于跨模态特征图的CT视觉问答

发布时间：2025年07月06日

`LLM应用` `计算机视觉`

> Computed Tomography Visual Question Answering with Cross-modal Feature Graphing

# 摘要

> 医学成像中的视觉问答（VQA）旨在通过自动解析复杂的医学图像数据来辅助临床诊断，这些解析是针对自然语言查询进行的。现有研究通常采用独立的视觉和文本编码器，分别从医学图像和临床问题中提取特征，并结合这些特征生成答案。在计算机断层扫描（CT）中，这些方法类似于传统的医学图像分析方法。然而，这些方法对体积CT数据中的空间连续性和切片间相关性关注较少，导致回答零散且不够准确。本文提出了一种基于大型语言模型（LLM）的新框架，通过显著特征的图表示进行增强。与传统多模态编码策略不同，我们的方法构建了一个融合视觉和文本特征的跨模态图，将单个CT切片和问题令牌视为图中的节点。我们进一步利用注意力图卷积网络在该结构中动态融合信息。最终聚合的图特征作为软提示，引导大型语言模型生成准确答案。在M3D-VQA基准数据集上的大量实验表明，我们的方法在多个评估指标上始终优于基线模型，提供了更强大的推理能力。

> Visual question answering (VQA) in medical imaging aims to support clinical diagnosis by automatically interpreting complex imaging data in response to natural language queries. Existing studies typically rely on distinct visual and textual encoders to independently extract features from medical images and clinical questions, which are subsequently combined to generate answers. Specifically, in computed tomography (CT), such approaches are similar to the conventional practices in medical image analysis. However, these approaches pay less attention to the spatial continuity and inter-slice correlations in the volumetric CT data, leading to fragmented and imprecise responses. In this paper, we propose a novel large language model (LLM)-based framework enhanced by a graph representation of salient features. Different from conventional multimodal encoding strategies, our approach constructs a cross-modal graph integrating both visual and textual features, treating individual CT slices and question tokens as nodes within the graph. We further leverage an attentive graph convolutional network to dynamically fuse information within this structure. The resulting aggregated graph features then serve as a soft prompt to guide a large language model in generating accurate answers. Extensive experiments on the M3D-VQA benchmark demonstrate that our approach consistently outperforms baselines across multiple evaluation metrics, offering more robust reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2507.04333)