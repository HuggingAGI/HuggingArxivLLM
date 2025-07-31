# 文本到图像模型的测试时提示优化

发布时间：2025年07月22日

`LLM应用

LLM应用` `人工智能`

> Test-time Prompt Refinement for Text-to-Image Models

# 摘要

> 文本到图像（T2I）生成模型虽已取得显著进展，但提示敏感性问题仍困扰着它们：细微的提示文本变化可能导致输出不一致或失准。为应对这一挑战，我们提出了一种无需额外训练底层T2I模型的闭环测试时提示优化框架——TIR。在我们的方法中，每一轮生成后都会进行一次优化：预训练的多模态大型语言模型（MLLM）会对输出图像和用户提示进行分析，检测不一致（如缺少物体、属性错误等），并生成更精确且物理合理的提示用于下一轮图像生成。通过迭代优化提示并验证提示与图像的一致性，TIR能够逐步纠正错误，这一过程类似于人类艺术家的迭代完善。我们在多个基准数据集上证明，这种闭环策略能有效提升一致性和视觉连贯性，同时保持与黑盒T2I模型的即插即用兼容性。

> Text-to-image (T2I) generation models have made significant strides but still struggle with prompt sensitivity: even minor changes in prompt wording can yield inconsistent or inaccurate outputs. To address this challenge, we introduce a closed-loop, test-time prompt refinement framework that requires no additional training of the underlying T2I model, termed TIR. In our approach, each generation step is followed by a refinement step, where a pretrained multimodal large language model (MLLM) analyzes the output image and the user's prompt. The MLLM detects misalignments (e.g., missing objects, incorrect attributes) and produces a refined and physically grounded prompt for the next round of image generation. By iteratively refining the prompt and verifying alignment between the prompt and the image, TIR corrects errors, mirroring the iterative refinement process of human artists. We demonstrate that this closed-loop strategy improves alignment and visual coherence across multiple benchmark datasets, all while maintaining plug-and-play integration with black-box T2I models.

[Arxiv](https://arxiv.org/abs/2507.22076)