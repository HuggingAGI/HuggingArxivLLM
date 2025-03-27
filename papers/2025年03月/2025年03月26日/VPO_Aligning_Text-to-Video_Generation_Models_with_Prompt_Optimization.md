# VPO: 基于提示优化的文本到视频生成模型对齐方法

发布时间：2025年03月26日

`LLM应用

分类理由：这篇论文探讨了如何通过优化提示来提升视频生成模型的效果，属于大型语言模型在视频生成任务中的应用研究。` `视频生成`

> VPO: Aligning Text-to-Video Generation Models with Prompt Optimization

# 摘要

> 视频生成模型在文本到视频的任务中取得了显著进展。然而，实际应用中用户的输入往往简短、模糊或结构不佳，这与模型训练时使用的高度详细描述存在显著差异。为了解决这一问题，我们提出了VPO框架，专注于通过优化提示来提升视频生成效果。该框架基于三个核心原则：无害性、准确性和有用性，能够忠实保留用户意图，同时显著提升生成视频的安全性和质量。VPO采用两阶段优化方法：首先构建并优化监督微调（SFT）数据集，其次引入文本和视频级别的反馈进行偏好学习。实验结果表明，VPO在安全性、对齐性和视频质量方面均显著优于基线方法，并且在视频生成模型上表现出强大的泛化能力。此外，VPO能够与强化学习方法结合使用，进一步提升模型性能。我们的代码和数据已公开发布在https://github.com/thu-coai/VPO。

> Video generation models have achieved remarkable progress in text-to-video tasks. These models are typically trained on text-video pairs with highly detailed and carefully crafted descriptions, while real-world user inputs during inference are often concise, vague, or poorly structured. This gap makes prompt optimization crucial for generating high-quality videos. Current methods often rely on large language models (LLMs) to refine prompts through in-context learning, but suffer from several limitations: they may distort user intent, omit critical details, or introduce safety risks. Moreover, they optimize prompts without considering the impact on the final video quality, which can lead to suboptimal results. To address these issues, we introduce VPO, a principled framework that optimizes prompts based on three core principles: harmlessness, accuracy, and helpfulness. The generated prompts faithfully preserve user intents and, more importantly, enhance the safety and quality of generated videos. To achieve this, VPO employs a two-stage optimization approach. First, we construct and refine a supervised fine-tuning (SFT) dataset based on principles of safety and alignment. Second, we introduce both text-level and video-level feedback to further optimize the SFT model with preference learning. Our extensive experiments demonstrate that VPO significantly improves safety, alignment, and video quality compared to baseline methods. Moreover, VPO shows strong generalization across video generation models. Furthermore, we demonstrate that VPO could outperform and be combined with RLHF methods on video generation models, underscoring the effectiveness of VPO in aligning video generation models. Our code and data are publicly available at https://github.com/thu-coai/VPO.

[Arxiv](https://arxiv.org/abs/2503.20491)