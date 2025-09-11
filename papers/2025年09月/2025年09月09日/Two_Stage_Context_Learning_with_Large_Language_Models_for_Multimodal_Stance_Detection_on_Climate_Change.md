# # 两阶段上下文学习与大语言模型：助力气候变化的多模态立场检测

发布时间：2025年09月09日

`LLM应用` `媒体与娱乐`

> Two Stage Context Learning with Large Language Models for Multimodal Stance Detection on Climate Change

# 摘要

> 数字平台信息爆炸式增长，立场检测已成为社交媒体分析的核心难题。然而现有方法多局限于文本分析，而真实社交内容中图文结合已成常态，亟需先进的多模态技术方案。为此，我们提出一种多模态立场检测框架，采用分层融合策略整合文本与视觉信息。该方法首先利用大型语言模型从源文本提取立场相关摘要，同时借助领域感知图像标题生成器，结合目标主题解读视觉内容。随后，这些模态与回复文本通过专用Transformer模块联合建模，以捕捉文本与图像间的交互关系。此模态融合框架通过整合多模态信息，实现了稳健的立场分类。我们在MultiClimate数据集（气候变化立场检测基准数据集，含对齐视频帧与转录文本）上进行了实验评估，结果显示模型准确率达76.2%、精确率76.3%、召回率76.2%、F1分数76.2%，性能优于当前最先进方法。

> With the rapid proliferation of information across digital platforms, stance detection has emerged as a pivotal challenge in social media analysis. While most of the existing approaches focus solely on textual data, real-world social media content increasingly combines text with visual elements creating a need for advanced multimodal methods. To address this gap, we propose a multimodal stance detection framework that integrates textual and visual information through a hierarchical fusion approach. Our method first employs a Large Language Model to retrieve stance-relevant summaries from source text, while a domain-aware image caption generator interprets visual content in the context of the target topic. These modalities are then jointly modeled along with the reply text, through a specialized transformer module that captures interactions between the texts and images. The proposed modality fusion framework integrates diverse modalities to facilitate robust stance classification. We evaluate our approach on the MultiClimate dataset, a benchmark for climate change-related stance detection containing aligned video frames and transcripts. We achieve accuracy of 76.2%, precision of 76.3%, recall of 76.2% and F1-score of 76.2%, respectively, outperforming existing state-of-the-art approaches.

[Arxiv](https://arxiv.org/abs/2509.08024)