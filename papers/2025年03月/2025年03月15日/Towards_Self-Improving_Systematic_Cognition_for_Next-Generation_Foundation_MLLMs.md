# 为下一代基础多语言模型构建自我改进的系统性认知之路

发布时间：2025年03月15日

`LLM应用` `多模态`

> Towards Self-Improving Systematic Cognition for Next-Generation Foundation MLLMs

# 摘要

> 尽管多模态大型语言模型（MLLMs）展现出强大的能力，但在细粒度感知和复杂推理方面仍面临挑战。当前主流的预训练方法主要通过训练高质量图像描述来提升感知能力，而收集用于改进推理的思维链（CoT）数据成本极高。虽然利用先进的MLLMs生成描述提升了扩展性，但输出常缺乏全面性和准确性。本文提出Self-Improving Cognition（SIcog），一个自我学习框架，旨在通过多模态预训练与自生成数据，构建下一代基础MLLMs，提升其系统性认知能力。具体而言，我们提出了链式描述方法，通过逐步视觉理解，增强MLLM的系统性感知，确保更全面和准确。此外，我们采用结构化的CoT推理技术，使MLLM能够整合深度多模态推理。为了构建具有自我改进认知能力的下一代基础MLLM，SIcog首先利用少量外部标注，赋予MLLM系统性的感知和推理能力。增强后的模型生成详细描述和CoT推理数据，并通过自我一致性进一步整理。最终，这些整理后的数据用于多模态预训练中精调MLLM，助力下一代基础MLLM的构建。在多种基准测试中，对低分辨率和高分辨率MLLM的广泛实验表明，仅使用21.3万个自生成预训练样本，SIcog就能生成认知显著提升的下一代基础MLLM，与主流预训练方法相比，取得了领先的性能。


> Despite their impressive capabilities, Multimodal Large Language Models (MLLMs) face challenges with fine-grained perception and complex reasoning. Prevalent pre-training approaches focus on enhancing perception by training on high-quality image captions due to the extremely high cost of collecting chain-of-thought (CoT) reasoning data for improving reasoning. While leveraging advanced MLLMs for caption generation enhances scalability, the outputs often lack comprehensiveness and accuracy. In this paper, we introduce Self-Improving Cognition (SIcog), a self-learning framework designed to construct next-generation foundation MLLMs by enhancing their systematic cognitive capabilities through multimodal pre-training with self-generated data. Specifically, we propose chain-of-description, an approach that improves an MLLM's systematic perception by enabling step-by-step visual understanding, ensuring greater comprehensiveness and accuracy. Additionally, we adopt a structured CoT reasoning technique to enable MLLMs to integrate in-depth multimodal reasoning. To construct a next-generation foundation MLLM with self-improved cognition, SIcog first equips an MLLM with systematic perception and reasoning abilities using minimal external annotations. The enhanced models then generate detailed captions and CoT reasoning data, which are further curated through self-consistency. This curated data is ultimately used to refine the MLLM during multimodal pre-training, facilitating next-generation foundation MLLM construction. Extensive experiments on both low- and high-resolution MLLMs across diverse benchmarks demonstrate that, with merely 213K self-generated pre-training samples, SIcog produces next-generation foundation MLLMs with significantly improved cognition, achieving benchmark-leading performance compared to prevalent pre-training approaches.

[Arxiv](https://arxiv.org/abs/2503.12303)