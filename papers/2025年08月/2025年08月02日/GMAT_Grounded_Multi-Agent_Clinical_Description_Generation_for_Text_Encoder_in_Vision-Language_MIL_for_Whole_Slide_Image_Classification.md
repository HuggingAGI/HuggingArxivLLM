# # **GMAT**: 基于多智能体的临床描述生成方法，用于视觉-语言多实例学习中的文本编码器在全切片图像分类中的应用

发布时间：2025年08月02日

`Agent` `病理学`

> GMAT: Grounded Multi-Agent Clinical Description Generation for Text Encoder in Vision-Language MIL for Whole Slide Image Classification

# 摘要

> 多示例学习 (MIL) 是全幻灯片图像 (WSI) 分类的领先方法，能够高效分析数十亿像素的病理切片。近期研究将视觉语言模型（VLMs）引入 MIL 流程，通过基于文本的类别描述而非简单的类别名称来整合医学知识。然而，当这些方法依赖大型语言模型（LLMs）生成临床描述，或使用固定长度的提示来表示复杂的病理概念时，VLMs 的有限令牌容量往往限制了编码类别信息的表达力和丰富性。此外，仅由 LLM 生成的描述可能缺乏领域基础和精细的医学特异性，导致与视觉特征的对齐效果欠佳。为了解决这些挑战，我们提出了一种视觉语言 MIL 框架，具有两个关键贡献：(1) 一种基于精选病理教科书和智能体专业化的接地多智能体描述生成系统，能够生成准确且多样的临床描述；(2) 一种基于描述列表而非单一提示的文本编码策略，能够捕获精细且互补的临床信号，以更好地与视觉特征对齐。将其集成到 VLM-MIL 流程中，我们的方法在肾癌和肺癌数据集上的表现优于单一提示的类别基线，并达到了与最新模型相当的性能水平。

> Multiple Instance Learning (MIL) is the leading approach for whole slide image (WSI) classification, enabling efficient analysis of gigapixel pathology slides. Recent work has introduced vision-language models (VLMs) into MIL pipelines to incorporate medical knowledge through text-based class descriptions rather than simple class names. However, when these methods rely on large language models (LLMs) to generate clinical descriptions or use fixed-length prompts to represent complex pathology concepts, the limited token capacity of VLMs often constrains the expressiveness and richness of the encoded class information. Additionally, descriptions generated solely by LLMs may lack domain grounding and fine-grained medical specificity, leading to suboptimal alignment with visual features. To address these challenges, we propose a vision-language MIL framework with two key contributions: (1) A grounded multi-agent description generation system that leverages curated pathology textbooks and agent specialization (e.g., morphology, spatial context) to produce accurate and diverse clinical descriptions; (2) A text encoding strategy using a list of descriptions rather than a single prompt, capturing fine-grained and complementary clinical signals for better alignment with visual features. Integrated into a VLM-MIL pipeline, our approach shows improved performance over single-prompt class baselines and achieves results comparable to state-of-the-art models, as demonstrated on renal and lung cancer datasets.

[Arxiv](https://arxiv.org/abs/2508.01293)