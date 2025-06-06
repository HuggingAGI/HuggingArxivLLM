# # 感知一切
识别、解释、描述与分割图像与视频中的任何内容

发布时间：2025年06月05日

`LLM应用` `计算机视觉`

> Perceive Anything: Recognize, Explain, Caption, and Segment Anything in Images and Videos

# 摘要

> 我们提出了“全知感知模型”（Perceive Anything Model, PAM），一个简单高效且全面的图像和视频区域级视觉理解框架。PAM通过整合大型语言模型（LLMs）对SAM 2进行了扩展，实现了目标分割的同时生成多样化的区域特定语义输出，包括类别、标签定义、功能解释及详细描述。为提升多粒度理解能力，我们开发了专用数据精炼和增强流水线，构建了包含150万图像和60万视频区域-语义标注的高质量数据集。PAM设计轻量化，运行效率比现有方法提升1.2-2.4倍，为实际应用提供了高效解决方案。我们相信，PAM将为区域级视觉理解研究树立强大基线。

> We present Perceive Anything Model (PAM), a conceptually straightforward and efficient framework for comprehensive region-level visual understanding in images and videos. Our approach extends the powerful segmentation model SAM 2 by integrating Large Language Models (LLMs), enabling simultaneous object segmentation with the generation of diverse, region-specific semantic outputs, including categories, label definition, functional explanations, and detailed captions. A key component, Semantic Perceiver, is introduced to efficiently transform SAM 2's rich visual features, which inherently carry general vision, localization, and semantic priors into multi-modal tokens for LLM comprehension. To support robust multi-granularity understanding, we also develop a dedicated data refinement and augmentation pipeline, yielding a high-quality dataset of 1.5M image and 0.6M video region-semantic annotations, including novel region-level streaming video caption data. PAM is designed for lightweightness and efficiency, while also demonstrates strong performance across a diverse range of region understanding tasks. It runs 1.2-2.4x faster and consumes less GPU memory than prior approaches, offering a practical solution for real-world applications. We believe that our effective approach will serve as a strong baseline for future research in region-level visual understanding.

[Arxiv](https://arxiv.org/abs/2506.05302)