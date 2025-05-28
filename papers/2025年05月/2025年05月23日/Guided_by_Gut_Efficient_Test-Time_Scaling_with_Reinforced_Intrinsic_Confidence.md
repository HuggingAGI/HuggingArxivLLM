# # 直觉指引：强化内在信心实现高效测试时间缩放

发布时间：2025年05月23日

`LLM应用` `人工智能`

> Guided by Gut: Efficient Test-Time Scaling with Reinforced Intrinsic Confidence

# 摘要

> 提升大型语言模型（LLM）推理能力的测试时缩放（TTS）方法通常伴随着显著的计算开销，主要源于对外部过程奖励模型（PRMs）或最佳-of-N（BoN）等采样方法的重度依赖。本文提出了一种名为Guided by Gut（GG）的高效自引导TTS框架，无需昂贵的外部验证器模型即可达到PRM级别的性能。我们的方法采用仅基于LLM内部信号（包括token级别置信度和步骤新颖性）引导的轻量级树搜索。一项关键创新是通过针对性的强化学习微调阶段，显著提升了内部置信度估计的可靠性。在具有挑战性的数学推理基准测试中，GG使较小规模模型（如1.5B参数）能够达到或超越显著更大规模模型（如32B-70B参数）的准确性，同时将GPU内存使用量降低多达10倍。与基于PRM的方法相比，GG实现了相当的准确性，推理速度提升了8倍，内存使用量降低了4-5倍。此外，GG相较于BoN策略，将KV缓存内存使用量减少了约50%，从而促进了TTS技术更加高效和实用的部署。

> Test-Time Scaling (TTS) methods for enhancing Large Language Model (LLM) reasoning often incur substantial computational costs, primarily due to extensive reliance on external Process Reward Models (PRMs) or sampling methods like Best-of-N (BoN). This paper introduces Guided by Gut (GG), an efficient self-guided TTS framework that achieves PRM-level performance without costly external verifier models. Our method employs a lightweight tree search guided solely by intrinsic LLM signals, token-level confidence and step novelty. One critical innovation is improving the reliability of internal confidence estimates via a targeted reinforcement learning fine-tuning phase. Empirical evaluations on challenging mathematical reasoning benchmarks demonstrate that GG enables smaller models (e.g., 1.5B parameters) to achieve accuracy matching or surpassing significantly larger models (e.g., 32B-70B parameters), while reducing GPU memory usage by up to 10x. Compared to PRM-based methods, GG achieves comparable accuracy with 8x faster inference speeds and 4-5x lower memory usage. Additionally, GG reduces KV cache memory usage by approximately 50% compared to the BoN strategy, facilitating more efficient and practical deployment of TTS techniques.

[Arxiv](https://arxiv.org/abs/2505.20325)