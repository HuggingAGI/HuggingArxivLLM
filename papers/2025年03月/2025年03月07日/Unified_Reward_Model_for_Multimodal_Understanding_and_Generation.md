# 统一奖励模型实现多模态理解和生成

发布时间：2025年03月07日

`LLM应用` `视觉模型` `多模态`

> Unified Reward Model for Multimodal Understanding and Generation

# 摘要

> 近期在人类偏好对齐领域的突破显著提升了多模态生成与理解能力。通过训练奖励模型来引导偏好优化是关键方法。然而，现有模型通常局限于特定任务，限制了其在多样化视觉应用中的适应性。我们提出，同时学习评估多个任务可产生协同效应：图像理解的提升会增强图像生成评估，而优化的图像评估则能通过更精准的帧分析提升视频评估。为此，本文推出了首个用于多模态理解和生成评估的统一奖励模型——UnifiedReward，支持成对排序和单点评分，适用于视觉模型的偏好对齐。具体而言，(1) 我们在构建的大规模人类偏好数据集上开发了UnifiedReward，涵盖图像和视频生成/理解任务。(2) 接着，它被用于基于视觉模型自动构建高质量偏好对数据，通过成对排序和单点筛选逐步优化输出。(3) 最后，这些数据通过直接偏好优化（DPO）实现偏好对齐。实验结果表明，联合学习评估多样化视觉任务可带来显著的相互提升。我们将该方法应用于图像和视频理解和生成任务，显著提升了各领域的性能表现。

> Recent advances in human preference alignment have significantly enhanced multimodal generation and understanding. A key approach is training reward models to guide preference optimization. However, existing models are often task-specific, limiting their adaptability across diverse visual applications. We also argue that jointly learning to assess multiple tasks may foster a synergistic effect, where improved image understanding enhances image generation assessment, and refined image evaluation benefits video assessment through better frame analysis. To this end, this paper proposes UnifiedReward, the first unified reward model for multimodal understanding and generation assessment, enabling both pairwise ranking and pointwise scoring, which can be employed for vision model preference alignment. Specifically, (1) we first develop UnifiedReward on our constructed large-scale human preference dataset, including both image and video generation/understanding tasks. (2) Then, it is utilized to automatically construct high-quality preference pair data based on the vision models, fine-gradually filtering their outputs through pair ranking and point sifting. (3) Finally, these data are used for their preference alignment through Direct Preference Optimization (DPO). Experimental results demonstrate that joint learning to assess diverse visual tasks can lead to substantial mutual benefits and we apply our pipeline to both image and video understanding/generation tasks, significantly improving the performance in each domain.

[Arxiv](https://arxiv.org/abs/2503.05236)