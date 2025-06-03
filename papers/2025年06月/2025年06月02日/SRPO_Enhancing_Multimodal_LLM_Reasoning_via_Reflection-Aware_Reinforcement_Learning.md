# SRPO：通过反思感知强化学习提升多模态大型语言模型推理能力

发布时间：2025年06月02日

`LLM应用` `多模态`

> SRPO: Enhancing Multimodal LLM Reasoning via Reflection-Aware Reinforcement Learning

# 摘要

> 多模态大型语言模型在推理任务中展现出令人瞩目的能力，但面对需要明确自我反思与自我纠错的复杂问题时，它们的表现仍显不足，尤其是在与单一模态的文本基础模型相比时。现有的反思方法较为简单，难以生成有意义且具有指导性的反馈，因为预训练模型的推理能力和知识限制在初始训练时已基本固定。为克服这些挑战，我们提出了一种基于组相对策略优化（SRPO）的多模态自我反思增强推理方法，这是一套专门设计的两阶段反思感知强化学习（RL）框架，旨在提升多模态LLM的推理能力。

在第一阶段，我们借助先进的MLLM指导，构建了一个高质量、以反思为核心的训练数据集。该模型会根据初始回答生成反思，帮助策略模型同时学习推理与自我反思。在第二阶段，我们在GRPO框架中引入了一种新颖的奖励机制，旨在鼓励简洁且具有认知价值的反思，同时避免冗余。

通过在MathVista、MathVision、MathVerse和MMMU-Pro等多个多模态推理基准测试中使用Qwen-2.5-VL-7B和Qwen-2.5-VL-32B进行的大量实验表明，SRPO显著超越了现有最优模型，在推理准确性和反思质量方面均实现了显著提升。

> Multimodal large language models (MLLMs) have shown promising capabilities in reasoning tasks, yet still struggle with complex problems requiring explicit self-reflection and self-correction, especially compared to their unimodal text-based counterparts. Existing reflection methods are simplistic and struggle to generate meaningful and instructive feedback, as the reasoning ability and knowledge limits of pre-trained models are largely fixed during initial training. To overcome these challenges, we propose Multimodal Self-Reflection enhanced reasoning with Group Relative Policy Optimization (SRPO), a two-stage reflection-aware reinforcement learning (RL) framework explicitly designed to enhance multimodal LLM reasoning. In the first stage, we construct a high-quality, reflection-focused dataset under the guidance of an advanced MLLM, which generates reflections based on initial responses to help the policy model learn both reasoning and self-reflection. In the second stage, we introduce a novel reward mechanism within the GRPO framework that encourages concise and cognitively meaningful reflection while avoiding redundancy. Extensive experiments across multiple multimodal reasoning benchmarks, including MathVista, MathVision, MathVerse, and MMMU-Pro, using Qwen-2.5-VL-7B and Qwen-2.5-VL-32B demonstrate that SRPO significantly outperforms state-of-the-art models, achieving notable improvements in both reasoning accuracy and reflection quality.

[Arxiv](https://arxiv.org/abs/2506.01713)