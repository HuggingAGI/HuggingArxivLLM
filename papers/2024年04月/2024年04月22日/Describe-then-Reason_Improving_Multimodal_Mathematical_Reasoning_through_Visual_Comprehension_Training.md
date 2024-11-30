# 通过视觉理解训练提升多模态数学推理：先描述，再推理

发布时间：2024年04月22日

`LLM应用` `教育技术` `人工智能`

> Describe-then-Reason: Improving Multimodal Mathematical Reasoning through Visual Comprehension Training

# 摘要

> 开源的多模态大型语言模型（MLLMs）在处理文本和视觉输入的任务上表现优异，但面对复杂的多模态数学推理挑战时，相较于 GPT-4V(ision) 和 Gemini-Pro 等专有模型，仍显不足。尽管通过细化中间步骤（理由）的微调能够提升一定的数学推理能力，但现有模型在视觉理解上仍有欠缺，主要是由于缺乏针对视觉的充分指导，这导致了对数学图形的错误解读。为应对这一挑战，我们设计了一个名为 VCAR 的两阶段训练流程，它在数学推理学习的基础上，特别强化了视觉理解的训练。该流程首先通过视觉描述生成任务增强 MLLMs 的视觉理解力，然后借助描述信息进行理由生成的进一步训练。在两大广泛认可的基准测试中，VCAR 的表现显著超越了仅依赖理由指导的基线方法，尤其是在视觉要求较高的问题上。

> Open-source multimodal large language models (MLLMs) excel in various tasks involving textual and visual inputs but still struggle with complex multimodal mathematical reasoning, lagging behind proprietary models like GPT-4V(ision) and Gemini-Pro. Although fine-tuning with intermediate steps (i.e., rationales) elicits some mathematical reasoning skills, the resulting models still fall short in visual comprehension due to inadequate visual-centric supervision, which leads to inaccurate interpretation of math figures. To address this issue, we propose a two-step training pipeline VCAR, which emphasizes the Visual Comprehension training in Addition to mathematical Reasoning learning. It first improves the visual comprehension ability of MLLMs through the visual description generation task, followed by another training step on generating rationales with the assistance of descriptions. Experimental results on two popular benchmarks demonstrate that VCAR substantially outperforms baseline methods solely relying on rationale supervision, especially on problems with high visual demands.

[Arxiv](https://arxiv.org/abs/2404.14604)