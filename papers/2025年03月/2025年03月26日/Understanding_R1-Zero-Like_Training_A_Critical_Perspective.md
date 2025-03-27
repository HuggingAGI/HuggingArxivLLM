# 解构 R1-Zero-Like 训练：批判性分析

发布时间：2025年03月26日

`LLM应用` `模型训练`

> Understanding R1-Zero-Like Training: A Critical Perspective

# 摘要

> 深度求索-R1-Zero 已经证明，大规模强化学习 (RL) 可以直接提升大型语言模型 (LLM) 的推理能力，而无需监督微调。在此工作中，我们深入探讨了类似 R1-Zero 的训练方法，重点关注其两大核心组件：基础模型与强化学习。通过研究包括深度求索-V3-Base 在内的多种基础模型，我们发现预训练特性对强化学习的表现有着重要影响。深度求索-V3-Base 已经展现出“顿悟时刻”，而 Qwen2.5 的基础模型即使没有提示模板也能表现出强大的推理能力，这可能暗示了预训练中存在某种偏好。此外，我们在组相对策略优化 (GRPO) 中发现了一种优化偏好，这种偏好在训练过程中人为增加了响应长度（尤其是对错误输出）。为解决这一问题，我们引入了无偏优化方法 Dr. GRPO，在保持推理性能的同时提升了令牌效率。借助这些洞察，我们提出了一种极简版的 R1-Zero 训练方案，使用 7B 基础模型在 AIME 2024 上实现了 43.3% 的准确率，树立了新的行业标杆。我们的代码可在 https://github.com/sail-sg/understand-r1-zero 获取。

> DeepSeek-R1-Zero has shown that reinforcement learning (RL) at scale can directly enhance the reasoning capabilities of LLMs without supervised fine-tuning. In this work, we critically examine R1-Zero-like training by analyzing its two core components: base models and RL. We investigate a wide range of base models, including DeepSeek-V3-Base, to understand how pretraining characteristics influence RL performance. Our analysis reveals that DeepSeek-V3-Base already exhibit ''Aha moment'', while Qwen2.5 base models demonstrate strong reasoning capabilities even without prompt templates, suggesting potential pretraining biases. Additionally, we identify an optimization bias in Group Relative Policy Optimization (GRPO), which artificially increases response length (especially for incorrect outputs) during training. To address this, we introduce Dr. GRPO, an unbiased optimization method that improves token efficiency while maintaining reasoning performance. Leveraging these insights, we present a minimalist R1-Zero recipe that achieves 43.3% accuracy on AIME 2024 with a 7B base model, establishing a new state-of-the-art. Our code is available at https://github.com/sail-sg/understand-r1-zero.

[Arxiv](https://arxiv.org/abs/2503.20783)