# UniTransfer：基于渐进式空间与时间步分解的视频概念迁移

发布时间：2025年09月25日

`LLM应用` `媒体与娱乐`

> UniTransfer: Video Concept Transfer via Progressive Spatial and Timestep Decomposition

# 摘要

> 我们提出全新架构UniTransfer，通过在渐进式框架中引入空间与扩散时间步分解，实现了精准可控的视频概念迁移。具体来说，在空间分解上，我们将视频拆解为三个核心部分：前景主体、背景及运动流。基于这一分解形式，我们进一步设计了双路转单路的DiT架构，支持对视频各组件的细粒度调控。我们还提出基于随机掩码的自监督预训练策略，提升从大规模无标签视频数据中学习分解表示的效果。受思维链（Chain-of-Thought）推理范式的启发，我们重新审视去噪扩散过程，提出思维链提示（Chain-of-Prompt，CoP）机制以实现时间步分解。我们把去噪过程拆解为三个不同粒度的阶段，借助大型语言模型（LLMs）生成特定阶段指令，渐进式引导生成过程。我们还构建了以动物为主题的视频数据集OpenAnimal，为视频概念迁移研究的推进与基准测试提供支持。大量实验验证，我们的方法能在多样参考图像和场景下实现高质量、可控的视频概念迁移，在视觉保真度和可编辑性上均优于现有基线。网页链接：https://yu-shaonian.github.io/UniTransfer-Web/

> We propose a novel architecture UniTransfer, which introduces both spatial and diffusion timestep decomposition in a progressive paradigm, achieving precise and controllable video concept transfer. Specifically, in terms of spatial decomposition, we decouple videos into three key components: the foreground subject, the background, and the motion flow. Building upon this decomposed formulation, we further introduce a dual-to-single-stream DiT-based architecture for supporting fine-grained control over different components in the videos. We also introduce a self-supervised pretraining strategy based on random masking to enhance the decomposed representation learning from large-scale unlabeled video data. Inspired by the Chain-of-Thought reasoning paradigm, we further revisit the denoising diffusion process and propose a Chain-of-Prompt (CoP) mechanism to achieve the timestep decomposition. We decompose the denoising process into three stages of different granularity and leverage large language models (LLMs) for stage-specific instructions to guide the generation progressively. We also curate an animal-centric video dataset called OpenAnimal to facilitate the advancement and benchmarking of research in video concept transfer. Extensive experiments demonstrate that our method achieves high-quality and controllable video concept transfer across diverse reference images and scenes, surpassing existing baselines in both visual fidelity and editability. Web Page: https://yu-shaonian.github.io/UniTransfer-Web/

[Arxiv](https://arxiv.org/abs/2509.21086)