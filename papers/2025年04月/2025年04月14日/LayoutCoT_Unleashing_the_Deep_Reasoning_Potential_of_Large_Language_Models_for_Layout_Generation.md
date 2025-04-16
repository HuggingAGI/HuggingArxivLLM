# # LayoutCoT: 用于布局生成，释放大型语言模型的深度推理潜力

发布时间：2025年04月14日

`LLM应用` `人工智能`

> LayoutCoT: Unleashing the Deep Reasoning Potential of Large Language Models for Layout Generation

# 摘要

> 条件布局生成的目标是从用户定义的约束条件中自动生成视觉美观且语义连贯的布局。尽管基于生成模型的方法已取得显著进展，但这些方法通常依赖大量训练数据或繁琐的微调过程，限制了其通用性和实际应用。近期，一些无需训练的方法开始崭露头角，它们利用大型语言模型（LLMs）的上下文学习能力，但这些方法往往受限于推理能力不足和过于简化的排序机制，难以稳定生成高质量布局。针对这一问题，我们提出了LayoutCoT，一种结合检索增强生成（RAG）与链式思维（CoT）技术的创新方法，旨在充分发挥LLMs的推理潜力。具体而言，LayoutCoT将布局表示转换为适合LLMs处理的标准序列化格式。通过布局感知的RAG技术，我们实现了高效的检索，并由LLMs生成初步布局。随后，将此初步布局与精选示例一同输入至专门设计的CoT推理模块，进行迭代优化，显著提升布局的语义连贯性和视觉效果。我们在涵盖三大条件布局生成任务的五个公开数据集上进行了全面实验。实验结果表明，无需任何训练或微调，LayoutCoT已达到当前最优水平。尤为值得一提的是，我们的CoT推理模块赋予了标准LLMs（即便不具备显式深度推理能力）超越专用深度推理模型（如deepseek-R1）的能力，充分展现了LayoutCoT在释放LLMs深度推理潜力方面的独特价值。

> Conditional layout generation aims to automatically generate visually appealing and semantically coherent layouts from user-defined constraints. While recent methods based on generative models have shown promising results, they typically require substantial amounts of training data or extensive fine-tuning, limiting their versatility and practical applicability. Alternatively, some training-free approaches leveraging in-context learning with Large Language Models (LLMs) have emerged, but they often suffer from limited reasoning capabilities and overly simplistic ranking mechanisms, which restrict their ability to generate consistently high-quality layouts. To this end, we propose LayoutCoT, a novel approach that leverages the reasoning capabilities of LLMs through a combination of Retrieval-Augmented Generation (RAG) and Chain-of-Thought (CoT) techniques. Specifically, LayoutCoT transforms layout representations into a standardized serialized format suitable for processing by LLMs. A Layout-aware RAG is used to facilitate effective retrieval and generate a coarse layout by LLMs. This preliminary layout, together with the selected exemplars, is then fed into a specially designed CoT reasoning module for iterative refinement, significantly enhancing both semantic coherence and visual quality. We conduct extensive experiments on five public datasets spanning three conditional layout generation tasks. Experimental results demonstrate that LayoutCoT achieves state-of-the-art performance without requiring training or fine-tuning. Notably, our CoT reasoning module enables standard LLMs, even those without explicit deep reasoning abilities, to outperform specialized deep-reasoning models such as deepseek-R1, highlighting the potential of our approach in unleashing the deep reasoning capabilities of LLMs for layout generation tasks.

[Arxiv](https://arxiv.org/abs/2504.10829)