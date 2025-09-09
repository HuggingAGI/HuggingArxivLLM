# 革新面向扩散大型语言模型的强化学习框架

发布时间：2025年09月08日

`强化学习` `基础理论`

> Revolutionizing Reinforcement Learning Framework for Diffusion Large Language Models

# 摘要

> 我们提出了TraceRL——一个轨迹感知的强化学习框架，专为扩散语言模型（DLMs）设计，能将偏好推理轨迹融入训练后阶段，且适用于不同架构。该框架配备基于扩散的价值模型以增强训练稳定性，在复杂数学和编码任务上展现出更优的推理性能。此外，它还能将特定块模型适配到更大的块，从而提升采样灵活性。借助TraceRL，我们开发出一系列最先进的扩散语言模型TraDo。尽管TraDo-4B-Instruct规模小于70亿参数的自回归模型，但其在复杂数学推理任务上仍持续优于这些模型。在数学推理基准测试中，TraDo-8B-Instruct相比Qwen2.5-7B-Instruct准确率相对提升6.1%，较Llama3.1-8B-Instruct更是提升51.3%。通过课程学习，我们还研发出首个长思维链（long-CoT）扩散语言模型，在MATH500数据集上以18.1%的相对准确率优势超越Qwen2.5-7B-Instruct。为推动可复现研究与实际应用，我们发布了一套全面的开源框架，支持跨不同架构构建、训练和部署扩散大型语言模型。该框架集成了用于推理和强化学习的加速KV缓存技术与推理引擎，并包含数学、编码及通用任务的多种监督微调与强化学习方法实现。代码和模型：https://github.com/Gen-Verse/dLLM-RL

> We propose TraceRL, a trajectory-aware reinforcement learning framework for diffusion language models (DLMs) that incorporates preferred inference trajectory into post-training, and is applicable across different architectures. Equipped with a diffusion-based value model that enhances training stability, we demonstrate improved reasoning performance on complex math and coding tasks. Besides, it can also be applied to adapt block-specific models to larger blocks, which improves sampling flexibility. Employing TraceRL, we derive a series of state-of-the-art diffusion language models, namely TraDo. Although smaller than 7B-scale AR models, TraDo-4B-Instruct still consistently outperforms them across complex math reasoning tasks. TraDo-8B-Instruct achieves relative accuracy improvements of 6.1% over Qwen2.5-7B-Instruct and 51.3% over Llama3.1-8B-Instruct on mathematical reasoning benchmarks. Through curriculum learning, we also derive the first long-CoT DLM, outperforming Qwen2.5-7B-Instruct on MATH500 with an 18.1% relative accuracy gain. To facilitate reproducible research and practical applications, we release a comprehensive open-source framework for building, training, and deploying diffusion LLMs across diverse architectures. The framework integrates accelerated KV-cache techniques and inference engines for both inference and reinforcement learning, and includes implementations of various supervised fine-tuning and RL methods for mathematics, coding, and general tasks. Code and Models: https://github.com/Gen-Verse/dLLM-RL

[Arxiv](https://arxiv.org/abs/2509.06949)