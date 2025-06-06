# # 摘要  
迈向全面的AI生成视频视觉质量评估：一种基于LLM的多维度评估模型

发布时间：2025年06月05日

`其他` `视频生成` `质量评估`

> Towards Holistic Visual Quality Assessment of AI-Generated Videos: A LLM-Based Multi-Dimensional Evaluation Model

# 摘要

> 近年来，AI生成视频（AIGV）技术发展迅猛，彻底改变了视频内容生产的范式。然而，AIGV视频仍存在噪声、模糊、帧抖动和动态范围不足等明显缺陷，严重影响用户体验。因此，建立有效的自动视觉质量评估体系，对AIGV内容监管和生成模型优化具有重要意义。本研究将AIGV的视觉质量细分为技术质量、运动质量和视频语义三个维度，并为每个维度设计了专门的编码器以实现特征的有效表达。此外，鉴于大型语言模型（LLMs）在视觉与语言任务中的出色表现，我们将其引入作为质量回归模块。为帮助LLM更好地理解多维特征与视觉质量之间的关联，我们开发了一种多模态提示工程框架。同时，我们在训练过程中引入了LoRA微调技术，以提升模型对特定任务的适应能力。我们的方法在2025年NTIRE AI生成内容质量评估挑战赛（Track 2：AI生成视频）中荣获	extbf{第二名}，充分证明了其有效性。代码可在https://github.com/QiZelu/AIGVEval获取。

> The development of AI-Generated Video (AIGV) technology has been remarkable in recent years, significantly transforming the paradigm of video content production. However, AIGVs still suffer from noticeable visual quality defects, such as noise, blurriness, frame jitter and low dynamic degree, which severely impact the user's viewing experience. Therefore, an effective automatic visual quality assessment is of great importance for AIGV content regulation and generative model improvement. In this work, we decompose the visual quality of AIGVs into three dimensions: technical quality, motion quality, and video semantics. For each dimension, we design corresponding encoder to achieve effective feature representation. Moreover, considering the outstanding performance of large language models (LLMs) in various vision and language tasks, we introduce a LLM as the quality regression module. To better enable the LLM to establish reasoning associations between multi-dimensional features and visual quality, we propose a specially designed multi-modal prompt engineering framework. Additionally, we incorporate LoRA fine-tuning technology during the training phase, allowing the LLM to better adapt to specific tasks. Our proposed method achieved \textbf{second place} in the NTIRE 2025 Quality Assessment of AI-Generated Content Challenge: Track 2 AI Generated video, demonstrating its effectiveness. Codes can be obtained at https://github.com/QiZelu/AIGVEval.

[Arxiv](https://arxiv.org/abs/2506.04715)