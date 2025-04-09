# PaMi-VDPO：基于提示感知的多实例视频偏好学习，有效缓解视频幻觉问题。

发布时间：2025年04月08日

`LLM应用` `多模态`

> PaMi-VDPO: Mitigating Video Hallucinations by Prompt-Aware Multi-Instance Video Preference Learning

# 摘要

> 直接偏好优化 (DPO) 虽然有助于减少视频多模态大型语言模型 (VLLMs) 中的幻觉现象，但其依赖离线偏好数据的特性限制了适应性，难以捕捉真实的视频与响应对齐偏差。为此，我们提出了视频直接偏好优化 (VDPO)，这是一种创新的在线偏好学习框架。VDPO 利用视频增强生成被拒绝样本，同时保持响应固定，从而避免了对偏好标注的依赖。

然而，在选择有效的增强时面临挑战，因为某些片段在特定提示下可能与原始片段在语义上相同，导致错误拒绝并破坏对齐。为了解决这一问题，我们引入了基于提示感知的多实例学习 VDPO (PaMi-VDPO)，它根据提示上下文智能选择增强。

PaMi-VDPO 不再采用单一的拒绝方式，而是构建一个增强片段的候选集，并采用从近到远的筛选策略。首先确保所有片段在语义上相关，然后再优先选择最符合提示且具有明显差异的片段。这使模型能够更好地捕捉有意义的视觉差异，从而减少幻觉，同时避免错误拒绝，显著提高对齐效果。

PaMi-VDPO 可无缝集成到现有的 VLLMs 中，无需额外参数或 GPT-4/人类监督。仅使用 10k SFT 数据，它在 VideoHallucer 上将基线模型提升了 5.3%，超越了 GPT-4o，同时在通用视频基准测试中保持稳定性能。这一方法为提升视频多模态模型的性能提供了新的思路。

> Direct Preference Optimization (DPO) helps reduce hallucinations in Video Multimodal Large Language Models (VLLMs), but its reliance on offline preference data limits adaptability and fails to capture true video-response misalignment. We propose Video Direct Preference Optimization (VDPO), an online preference learning framework that eliminates the need for preference annotation by leveraging video augmentations to generate rejected samples while keeping responses fixed. However, selecting effective augmentations is non-trivial, as some clips may be semantically identical to the original under specific prompts, leading to false rejections and disrupting alignment. To address this, we introduce Prompt-aware Multi-instance Learning VDPO (PaMi-VDPO), which selects augmentations based on prompt context. Instead of a single rejection, we construct a candidate set of augmented clips and apply a close-to-far selection strategy, initially ensuring all clips are semantically relevant while then prioritizing the most prompt-aware distinct clip. This allows the model to better capture meaningful visual differences, mitigating hallucinations, while avoiding false rejections, and improving alignment. PaMi-VDPOseamlessly integrates into existing VLLMs without additional parameters, GPT-4/human supervision. With only 10k SFT data, it improves the base model by 5.3% on VideoHallucer, surpassing GPT-4o, while maintaining stable performance on general video benchmarks.

[Arxiv](https://arxiv.org/abs/2504.05810)