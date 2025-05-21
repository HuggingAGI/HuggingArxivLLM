# UniGen：提升统一多模态理解与生成的训练及测试策略

发布时间：2025年05月20日

`LLM应用

摘要讨论了UniGen的开发和应用，特别是其在图像生成方面的应用，属于大型语言模型的应用领域。` `人工智能` `计算机视觉`

> UniGen: Enhanced Training & Test-Time Strategies for Unified Multimodal Understanding and Generation

# 摘要

> 我们推出了UniGen，一款统一的多模态大型语言模型（MLLM），具备图像理解和生成能力。从数据为中心的视角出发，我们全面研究了UniGen的完整训练流程，包括多阶段预训练、监督微调以及直接偏好优化。更重要的是，我们提出了一种创新的链式思维验证（CoT-V）策略，用于测试时的扩展。通过采用简单的Best-of-N测试策略，该策略显著提升了UniGen的图像生成质量。具体而言，CoT-V使UniGen在测试时能够同时担任图像生成器和验证器的角色，通过逐步的链式思维方式，评估文本提示与其生成图像之间的语义对齐。UniGen在所有训练阶段均基于开源数据集进行训练，在多种图像理解和生成基准测试中达到了当前最优水平，最终在GenEval上取得了0.78分，在DPG-Bench上获得了85.19分。通过广泛的消融研究，我们的工作不仅提供了可操作的见解，还解决了构建统一MLLM全生命周期中的关键挑战，为未来的研究指明了有意义的方向。

> We introduce UniGen, a unified multimodal large language model (MLLM) capable of image understanding and generation. We study the full training pipeline of UniGen from a data-centric perspective, including multi-stage pre-training, supervised fine-tuning, and direct preference optimization. More importantly, we propose a new Chain-of-Thought Verification (CoT-V) strategy for test-time scaling, which significantly boosts UniGen's image generation quality using a simple Best-of-N test-time strategy. Specifically, CoT-V enables UniGen to act as both image generator and verifier at test time, assessing the semantic alignment between a text prompt and its generated image in a step-by-step CoT manner. Trained entirely on open-source datasets across all stages, UniGen achieves state-of-the-art performance on a range of image understanding and generation benchmarks, with a final score of 0.78 on GenEval and 85.19 on DPG-Bench. Through extensive ablation studies, our work provides actionable insights and addresses key challenges in the full life cycle of building unified MLLMs, contributing meaningful directions to the future research.

[Arxiv](https://arxiv.org/abs/2505.14682)