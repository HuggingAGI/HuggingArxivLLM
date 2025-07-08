# 差异化的注意力机制在多模态危机事件分析中的应用

发布时间：2025年07月07日

`LLM应用` `危机管理` `社交媒体`

> Differential Attention for Multimodal Crisis Event Analysis

# 摘要

> 社交媒体在危机事件中是信息的重要来源。用户发布的多模态数据流对实时人道主义响应至关重要，但如何高效提取关键信息并整合异构数据仍是巨大挑战。本研究通过探索视觉语言模型（VLMs）和融合策略，提升三个任务中的危机数据分类能力。我们利用LLaVA生成文本优化文本-图像对齐，并采用CLIP的视觉和文本嵌入，在无需微调的情况下超越传统模型。为优化多模态融合，我们结合引导交叉注意力（Guided CA）和差分注意力机制，通过强调关键信息并过滤无关内容，增强特征对齐效果。实验表明，差分注意力提升分类性能，而引导交叉注意力在多模态特征对齐方面表现优异。在CrisisMMD基准数据集上，预训练VLMs、增强文本描述和自适应融合策略的组合，在分类准确性上超越现有模型，为灾害响应提供更可靠和可解释的支持。代码已开源，欢迎访问https://github.com/Munia03/Multimodal_Crisis_Event。

> Social networks can be a valuable source of information during crisis events. In particular, users can post a stream of multimodal data that can be critical for real-time humanitarian response. However, effectively extracting meaningful information from this large and noisy data stream and effectively integrating heterogeneous data remains a formidable challenge. In this work, we explore vision language models (VLMs) and advanced fusion strategies to enhance the classification of crisis data in three different tasks. We incorporate LLaVA-generated text to improve text-image alignment. Additionally, we leverage Contrastive Language-Image Pretraining (CLIP)-based vision and text embeddings, which, without task-specific fine-tuning, outperform traditional models. To further refine multimodal fusion, we employ Guided Cross Attention (Guided CA) and combine it with the Differential Attention mechanism to enhance feature alignment by emphasizing critical information while filtering out irrelevant content. Our results show that while Differential Attention improves classification performance, Guided CA remains highly effective in aligning multimodal features. Extensive experiments on the CrisisMMD benchmark data set demonstrate that the combination of pretrained VLMs, enriched textual descriptions, and adaptive fusion strategies consistently outperforms state-of-the-art models in classification accuracy, contributing to more reliable and interpretable models for three different tasks that are crucial for disaster response. Our code is available at https://github.com/Munia03/Multimodal_Crisis_Event.

[Arxiv](https://arxiv.org/abs/2507.05165)