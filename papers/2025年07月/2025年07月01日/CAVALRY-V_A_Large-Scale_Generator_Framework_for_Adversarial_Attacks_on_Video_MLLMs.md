# CAVALRY-V：专为视频多模态大语言模型设计的大规模对抗攻击生成框架

发布时间：2025年07月01日

`LLM应用` `视频处理` `对抗攻击`

> CAVALRY-V: A Large-Scale Generator Framework for Adversarial Attacks on Video MLLMs

# 摘要

> 视频多模态大语言模型（V-MLLMs）在时间推理和跨模态理解方面表现卓越，但其在对抗攻击中的脆弱性仍未被充分探索，主要由于复杂的跨模态推理机制、时间依赖性和计算限制等挑战。我们提出了一种名为CAVALRY-V（跨模态语言-视觉对抗生成框架）的全新框架，专注于针对V-MLLMs中视觉感知与语言生成的关键接口。该框架的两大创新点包括：(1) 一种双目标语义-视觉损失函数，通过同时干扰模型的文本生成逻辑和视觉表征，破坏跨模态整合；(2) 一个计算高效的两阶段生成器框架，结合大规模预训练实现跨模型迁移性，并通过专门的微调增强时空一致性。在全面的视频理解基准测试中，CAVALRY-V的表现显著优于现有攻击方法，在商业系统（GPT-4.1、Gemini 2.0）和开源模型（QwenVL-2.5、InternVL-2.5、Llava-Video、Aria、MiniCPM-o-2.6）上，平均性能提升达22.8%。该框架通过隐式建模时间一致性而非显式正则化，实现了高度灵活性，即使在图像理解方面也带来了显著提升（平均增益34.4%）。这一能力凸显了CAVALRY-V作为跨模态系统对抗研究基础方法的潜力。

> Video Multimodal Large Language Models (V-MLLMs) have shown impressive capabilities in temporal reasoning and cross-modal understanding, yet their vulnerability to adversarial attacks remains underexplored due to unique challenges: complex cross-modal reasoning mechanisms, temporal dependencies, and computational constraints. We present CAVALRY-V (Cross-modal Language-Vision Adversarial Yielding for Videos), a novel framework that directly targets the critical interface between visual perception and language generation in V-MLLMs. Our approach introduces two key innovations: (1) a dual-objective semantic-visual loss function that simultaneously disrupts the model's text generation logits and visual representations to undermine cross-modal integration, and (2) a computationally efficient two-stage generator framework that combines large-scale pre-training for cross-model transferability with specialized fine-tuning for spatiotemporal coherence. Empirical evaluation on comprehensive video understanding benchmarks demonstrates that CAVALRY-V significantly outperforms existing attack methods, achieving 22.8% average improvement over the best baseline attacks on both commercial systems (GPT-4.1, Gemini 2.0) and open-source models (QwenVL-2.5, InternVL-2.5, Llava-Video, Aria, MiniCPM-o-2.6). Our framework achieves flexibility through implicit temporal coherence modeling rather than explicit regularization, enabling significant performance improvements even on image understanding (34.4% average gain). This capability demonstrates CAVALRY-V's potential as a foundational approach for adversarial research across multimodal systems.

[Arxiv](https://arxiv.org/abs/2507.00817)