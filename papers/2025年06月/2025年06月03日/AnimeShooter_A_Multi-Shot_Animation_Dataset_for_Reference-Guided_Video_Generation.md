# **AnimeShooter：参考引导视频生成的多镜头动画数据集**  
本数据集专为基于参考的视频生成任务设计，包含多个参考帧，适用于生成对抗网络（GANs）等模型。

发布时间：2025年06月03日

`LLM应用

理由：这篇论文探讨了如何利用多模态大型语言模型（MLLMs）和视频扩散模型来生成连贯的多镜头动画视频。虽然它涉及了数据集的构建和方法的开发，但核心在于将LLM应用于动画制作这一具体领域，属于LLM的应用层面。` `动画制作` `生成模型`

> AnimeShooter: A Multi-Shot Animation Dataset for Reference-Guided Video Generation

# 摘要

> AI生成内容（AIGC）的最新进展为动画制作带来了巨大变革。要创作出引人入胜的动画作品，生成连贯的多镜头视频片段至关重要，这需要结合叙事脚本和角色参考。然而，现有的公共数据集大多专注于真实场景的全局描述，缺乏用于角色一致性指导的参考图像。为解决这一难题，我们推出了AnimeShooter——一个基于参考的多镜头动画数据集。通过自动化流程，AnimeShooter实现了全面的层次化标注，并确保了镜头间视觉的一致性。在故事层面，标注涵盖了故事情节、关键场景以及主要角色档案，并附带参考图像；在镜头层面，标注将故事分解为连续的镜头，每个镜头都标注了场景、角色以及叙事性和描述性的视觉说明。此外，AnimeShooter-audio子集为每个镜头提供了同步音频、音频描述和音源信息。为了验证AnimeShooter的价值并为基于参考的多镜头视频生成任务建立基准，我们推出了AnimeShooterGen，该方法结合了多模态大型语言模型（MLLMs）和视频扩散模型。具体而言，参考图像和已生成镜头通过MLLM处理，生成同时感知参考和上下文的表示，随后作为条件输入扩散模型以解码后续镜头。实验结果表明，在AnimeShooter上训练的模型在跨镜头视觉一致性和对参考指导的遵循方面表现出色，充分证明了我们的数据集在连贯动画视频生成中的重要价值。

> Recent advances in AI-generated content (AIGC) have significantly accelerated animation production. To produce engaging animations, it is essential to generate coherent multi-shot video clips with narrative scripts and character references. However, existing public datasets primarily focus on real-world scenarios with global descriptions, and lack reference images for consistent character guidance. To bridge this gap, we present AnimeShooter, a reference-guided multi-shot animation dataset. AnimeShooter features comprehensive hierarchical annotations and strong visual consistency across shots through an automated pipeline. Story-level annotations provide an overview of the narrative, including the storyline, key scenes, and main character profiles with reference images, while shot-level annotations decompose the story into consecutive shots, each annotated with scene, characters, and both narrative and descriptive visual captions. Additionally, a dedicated subset, AnimeShooter-audio, offers synchronized audio tracks for each shot, along with audio descriptions and sound sources. To demonstrate the effectiveness of AnimeShooter and establish a baseline for the reference-guided multi-shot video generation task, we introduce AnimeShooterGen, which leverages Multimodal Large Language Models (MLLMs) and video diffusion models. The reference image and previously generated shots are first processed by MLLM to produce representations aware of both reference and context, which are then used as the condition for the diffusion model to decode the subsequent shot. Experimental results show that the model trained on AnimeShooter achieves superior cross-shot visual consistency and adherence to reference visual guidance, which highlight the value of our dataset for coherent animated video generation.

[Arxiv](https://arxiv.org/abs/2506.03126)