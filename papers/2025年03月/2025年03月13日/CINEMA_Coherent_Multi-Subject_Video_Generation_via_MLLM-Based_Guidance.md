# CINEMA：通过MLLM引导实现连贯多主题视频生成

发布时间：2025年03月13日

`LLM应用` `媒体技术`

> CINEMA: Coherent Multi-Subject Video Generation via MLLM-Based Guidance

# 摘要

> 视频生成领域随着深度生成模型，尤其是扩散模型的出现，取得了显著进展。尽管现有方法在从文本提示或单张图像生成高质量视频方面表现出色，但多主体个性化视频生成仍是一项极具挑战性的难题。这一任务要求在确保时空一致性的前提下，合成包含多个独立主体的视频，每个主体由不同的参考图像定义。当前方法主要通过将主体图像映射到文本提示中的关键词来实现，这不仅引入了模糊性，还限制了对主体关系的有效建模。

在本文中，我们提出了CINEMA，一个基于多模态大语言模型（MLLM）的全新框架，用于连贯的多主体视频生成。我们的方法无需明确主体图像与文本实体之间的对应关系，从而减少了模糊性并降低了标注工作量。通过利用MLLM解释主体关系，我们的方法实现了高度的可扩展性，支持使用大规模多样化数据集进行训练。此外，我们的框架能够适应不同数量的主体，为个性化内容创作提供了更大的灵活性。

通过广泛的评估，我们证明了CINEMA在主体一致性以及整体视频连贯性方面有显著提升。这一突破为叙事、交互式媒体和个性化视频生成等高级应用奠定了坚实的基础。

> Video generation has witnessed remarkable progress with the advent of deep generative models, particularly diffusion models. While existing methods excel in generating high-quality videos from text prompts or single images, personalized multi-subject video generation remains a largely unexplored challenge. This task involves synthesizing videos that incorporate multiple distinct subjects, each defined by separate reference images, while ensuring temporal and spatial consistency. Current approaches primarily rely on mapping subject images to keywords in text prompts, which introduces ambiguity and limits their ability to model subject relationships effectively. In this paper, we propose CINEMA, a novel framework for coherent multi-subject video generation by leveraging Multimodal Large Language Model (MLLM). Our approach eliminates the need for explicit correspondences between subject images and text entities, mitigating ambiguity and reducing annotation effort. By leveraging MLLM to interpret subject relationships, our method facilitates scalability, enabling the use of large and diverse datasets for training. Furthermore, our framework can be conditioned on varying numbers of subjects, offering greater flexibility in personalized content creation. Through extensive evaluations, we demonstrate that our approach significantly improves subject consistency, and overall video coherence, paving the way for advanced applications in storytelling, interactive media, and personalized video generation.

[Arxiv](https://arxiv.org/abs/2503.10391)