# # Omni-Video: Democratizing Unified Video Understanding and Generation  
全视频：推动统一视频理解与生成的普及化

发布时间：2025年07月08日

`LLM应用` `视频处理` `人工智能`

> Omni-Video: Democratizing Unified Video Understanding and Generation

# 摘要

> 尽管在统一理解与生成模型领域取得了显著突破，推动了图像理解、推理、生成与编辑技术的长足进步，但当前主流基础模型主要专注于图像处理，导致在视频理解和生成的统一建模方面存在明显空白。为此，我们提出Omni-Video，一个高效且强大的视频理解、生成以及基于指令的编辑统一框架。我们的核心思路是指导现有的多模态大型语言模型（MLLMs）生成连续的视觉线索，作为扩散解码器的输入，从而生成高质量的视频。为充分发挥系统在统一视频建模方面的潜力，我们进行了两项关键改进：1) 采用轻量级架构设计，在MLLMs顶部附加视觉头，并在扩散解码器输入前添加适配器，前者生成视觉标记供后者使用，后者将这些视觉标记适应到扩散解码器的条件空间；2) 采用高效的多阶段训练方案，在有限资源下快速连接MLLMs与扩散解码器。实验结果表明，我们的模型在视频生成、编辑和理解任务中展现出令人满意的泛化能力。

> Notable breakthroughs in unified understanding and generation modeling have led to remarkable advancements in image understanding, reasoning, production and editing, yet current foundational models predominantly focus on processing images, creating a gap in the development of unified models for video understanding and generation. This report presents Omni-Video, an efficient and effective unified framework for video understanding, generation, as well as instruction-based editing. Our key insight is to teach existing multimodal large language models (MLLMs) to produce continuous visual clues that are used as the input of diffusion decoders, which produce high-quality videos conditioned on these visual clues. To fully unlock the potential of our system for unified video modeling, we integrate several technical improvements: 1) a lightweight architectural design that respectively attaches a vision head on the top of MLLMs and a adapter before the input of diffusion decoders, the former produce visual tokens for the latter, which adapts these visual tokens to the conditional space of diffusion decoders; and 2) an efficient multi-stage training scheme that facilitates a fast connection between MLLMs and diffusion decoders with limited data and computational resources. We empirically demonstrate that our model exhibits satisfactory generalization abilities across video generation, editing and understanding tasks.

[Arxiv](https://arxiv.org/abs/2507.06119)