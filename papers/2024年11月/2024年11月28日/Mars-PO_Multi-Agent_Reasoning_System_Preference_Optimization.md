# Mars-PO：多智能体推理系统的偏好优化

发布时间：2024年11月28日

`Agent` `人工智能`

> Mars-PO: Multi-Agent Reasoning System Preference Optimization

# 摘要

> 数学推理对于大型语言模型（LLMs）而言是一项基础能力，然而在这一领域取得高性能依旧是重大挑战。自回归生成过程常导致LLMs易出现错误、幻觉和不一致的情况，在多步推理时尤为明显。本文中，我们提出了Mars-PO，这是一个借助多智能体系统提升LLMs数学推理能力的新框架。它把多个智能体的高质量输出整合为一个混合正样本集，并与智能体特定的负样本配对，构建出强大的训练偏好对。通过让智能体与共享正样本对齐，同时解决个体的薄弱之处，Mars-PO在数学推理基准测试中实现了显著的性能提升。比如，它将最先进的指令调整型LLM Llama3.1-8B-Instruct在MATH基准测试中的准确率从50.38%提升至57.82%。实验结果进一步证明，我们的方法始终优于其他基线，如监督微调、普通DPO及其增强版本，凸显了我们方法的有效性。

> Mathematical reasoning is a fundamental capability for large language models (LLMs), yet achieving high performance in this domain remains a significant challenge. The auto-regressive generation process often makes LLMs susceptible to errors, hallucinations, and inconsistencies, particularly during multi-step reasoning. In this paper, we propose Mars-PO, a novel framework to improve the mathematical reasoning capabilities of LLMs through a multi-agent system. It combines high-quality outputs from multiple agents into a hybrid positive sample set and pairs them with agent-specific negative samples to construct robust preference pairs for training. By aligning agents with shared positive samples while addressing individual weaknesses, Mars-PO achieves substantial performance improvements on mathematical reasoning benchmarks. For example, it increases the accuracy on the MATH benchmark of the state-of-the-art instruction-tuned LLM, Llama3.1-8B-Instruct, from 50.38% to 57.82%. Experimental results further demonstrate that our method consistently outperforms other baselines, such as supervised fine-tuning, vanilla DPO, and its enhanced versions, highlighting the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2411.19039)