# 在 LLMs 中激活分布式视觉区域，以实现高效且有效的视觉语言训练与推理

发布时间：2024年12月17日

`LLM应用` `视觉语言模型` `人工智能`

> Activating Distributed Visual Region within LLMs for Efficient and Effective Vision-Language Training and Inference

# 摘要

> 大型视觉语言模型（LVLMs）通常借助视觉指令调优来习得视觉能力，这会对投影仪及其 LLM 骨干进行更新。受人类大脑中视觉区域这一概念的启发，我们探究了 LLM 中是否存在作为认知核心的类似“视觉区域”，并探索通过选择性层调优来高效训练 LVLMs 的可能性。我们用 Bunny-Llama-3-8B-V 开展详细实验，用 LLaVA-1.5-7B 和 LLaVA-1.5-13B 在一系列视觉和文本任务中进行验证。我们的研究发现，在稀疏且均匀分布的情况下，选择性更新 25％的 LLM 层，能够保留近 99％的视觉性能，同时保持或提升文本任务的结果，还能有效缩短训练时间。基于这种针对性的训练方法，我们进一步提出了一种新颖的基于视觉区域的剪枝范式，去除视觉区域之外的非关键层，从而实现最小的性能损失。本研究通过在 LLM 中激活分层的视觉区域，为 LVLM 的训练和推理提供了一种高效的策略，在不同模型和参数规模下均行之有效。

> Large Vision-Language Models (LVLMs) typically learn visual capacity through visual instruction tuning, involving updates to both a projector and their LLM backbones. Drawing inspiration from the concept of visual region in the human brain, we investigate the existence of an analogous \textit{visual region} within LLMs that functions as a cognitive core, and explore the possibility of efficient training of LVLMs via selective layers tuning. We use Bunny-Llama-3-8B-V for detailed experiments and LLaVA-1.5-7B and LLaVA-1.5-13B for validation across a range of visual and textual tasks. Our findings reveal that selectively updating 25\% of LLMs layers, when sparsely and uniformly distributed, can preserve nearly 99\% of visual performance while maintaining or enhancing textual task results, and also effectively reducing training time. Based on this targeted training approach, we further propose a novel visual region-based pruning paradigm, removing non-critical layers outside the visual region, which can achieve minimal performance loss. This study offers an effective and efficient strategy for LVLM training and inference by activating a layer-wise visual region within LLMs, which is consistently effective across different models and parameter scales.

[Arxiv](https://arxiv.org/abs/2412.12785)