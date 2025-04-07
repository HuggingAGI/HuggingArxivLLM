# VARGPT-v1.1：优化视觉自回归大统一模型的迭代指令微调与强化学习方案

发布时间：2025年04月03日

`Agent` `视觉生成` `人工智能`

> VARGPT-v1.1: Improve Visual Autoregressive Large Unified Model via Iterative Instruction Tuning and Reinforcement Learning

# 摘要

> 我们很高兴推出VARGPT-v1.1——基于VARGPT框架的先进统一视觉自回归模型。该模型延续了视觉理解的下一步预测和图像生成的多尺度生成的双轨范式。具体升级包括：(1) 创新的训练策略，融合迭代视觉指令微调与直接偏好优化（DPO）强化学习，(2) 扩展至830万视觉-生成指令对的训练语料库，(3) 升级至Qwen2架构的语言模型，(4) 高分辨率图像生成能力，以及(5) 无需架构修改的图像编辑功能。这些升级使VARGPT-v1.1在多模态理解与文本到图像生成任务中达到当前最优水平，显著提升了理解和生成性能。特别值得一提的是，通过视觉指令微调，模型在保持架构一致性的同时获得了图像编辑能力，展现了统一视觉理解、生成与编辑的潜力。我们的研究结果表明，精心设计的统一视觉自回归模型能够有效采纳大型语言模型（LLMs）的灵活训练策略，展现出良好的扩展前景。代码库和模型权重已开源，地址为https://github.com/VARGPT-family/VARGPT-v1.1。

> In this work, we present VARGPT-v1.1, an advanced unified visual autoregressive model that builds upon our previous framework VARGPT. The model preserves the dual paradigm of next-token prediction for visual understanding and next-scale generation for image synthesis. Specifically, VARGPT-v1.1 integrates: (1) a novel training strategy combining iterative visual instruction tuning with reinforcement learning through Direct Preference Optimization (DPO), (2) an expanded training corpus containing 8.3M visual-generative instruction pairs, (3) an upgraded language model backbone using Qwen2, (4) enhanced image generation resolution, and (5) emergent image editing capabilities without architectural modifications. These advancements enable VARGPT-v1.1 to achieve state-of-the-art performance in multimodal understanding and text-to-image instruction-following tasks, demonstrating significant improvements in both comprehension and generation metrics. Notably, through visual instruction tuning, the model acquires image editing functionality while maintaining architectural consistency with its predecessor, revealing the potential for unified visual understanding, generation, and editing. Our findings suggest that well-designed unified visual autoregressive models can effectively adopt flexible training strategies from large language models (LLMs), exhibiting promising scalability. The codebase and model weights are publicly available at https://github.com/VARGPT-family/VARGPT-v1.1.

[Arxiv](https://arxiv.org/abs/2504.02949)