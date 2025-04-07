# 噪声增强微调：一种缓解大型语言模型幻觉现象的方法

发布时间：2025年04月04日

`LLM理论` `人工智能`

> Noise Augmented Fine Tuning for Mitigating Hallucinations in Large Language Models

# 摘要

> 大型语言模型（LLMs）常产生不准确或误导性内容。为解决这一问题，我们提出Noise-Augmented Fine-Tuning（NoiseFiT），一种基于信号噪声比（SNR）的自适应噪声注入框架，旨在提升模型稳健性。NoiseFiT通过动态缩放的高斯噪声，针对性地扰动高SNR（更稳健）或低SNR（可能欠正则化）层。我们还引入了结合标准交叉熵、软交叉熵和一致性正则化的混合损失函数，确保噪声训练下的稳定输出。理论分析表明，自适应噪声注入无偏且保持方差，为收敛提供保证。实验结果表明，NoiseFiT显著降低幻觉率，提升关键任务性能。我们已在W&B、Hugging Face和GitHub公开了实验数据和代码，助力进一步研究与可重复性。

> Large language models (LLMs) often produce inaccurate or misleading content-hallucinations. To address this challenge, we introduce Noise-Augmented Fine-Tuning (NoiseFiT), a novel framework that leverages adaptive noise injection based on the signal-to-noise ratio (SNR) to enhance model robustness. In particular, NoiseFiT selectively perturbs layers identified as either high-SNR (more robust) or low-SNR (potentially under-regularized) using a dynamically scaled Gaussian noise. We further propose a hybrid loss that combines standard cross-entropy, soft cross-entropy, and consistency regularization to ensure stable and accurate outputs under noisy training conditions. Our theoretical analysis shows that adaptive noise injection is both unbiased and variance-preserving, providing strong guarantees for convergence in expectation. Empirical results on multiple test and benchmark datasets demonstrate that NoiseFiT significantly reduces hallucination rates, often improving or matching baseline performance in key tasks. These findings highlight the promise of noise-driven strategies for achieving robust, trustworthy language modeling without incurring prohibitive computational overhead. Given the comprehensive and detailed nature of our experiments, we have publicly released the fine-tuning logs, benchmark evaluation artifacts, and source code online at W&B, Hugging Face, and GitHub, respectively, to foster further research, accessibility and reproducibility.

[Arxiv](https://arxiv.org/abs/2504.03302)