# 链式思维在多模态对齐中的整合研究：针对3D视觉语言学习的探索

发布时间：2025年03月08日

`LLM应用` `计算机视觉` `人工智能`

> Integrating Chain-of-Thought for Multimodal Alignment: A Study on 3D Vision-Language Learning

# 摘要

> Chain-of-Thought (CoT)推理在自然语言任务中表现出显著效果，但在多模态对齐领域尚未得到充分探索。本研究通过将结构化推理融入对齐训练，深入研究其在3D视觉语言学习中的应用。我们推出了3D-CoT基准数据集，该数据集包含层次化的CoT标注，涵盖形状识别、功能推断和因果推理等多个维度。通过一系列控制实验，我们对比了CoT结构化标注与标准文本标注在大型推理模型（LRMs）和大型语言模型（LLMs）中的表现差异。我们的评估体系采用双层框架，全面考察中间推理过程与最终推断质量。实验结果表明，CoT推理显著提升了3D语义接地能力，其中大型推理模型（LRMs）对CoT的利用效果优于大型语言模型（LLMs）。此外，我们发现标注结构对模型性能有着重要影响——显式的推理标记有助于LLMs的推理过程，而无标记的CoT则更符合LRM的推理模式。我们的研究表明，CoT推理对于提升多模态推理能力具有关键作用，其应用价值不仅限于3D任务，更可推广至更广泛的领域。

> Chain-of-Thought (CoT) reasoning has proven effective in natural language tasks but remains underexplored in multimodal alignment. This study investigates its integration into 3D vision-language learning by embedding structured reasoning into alignment training. We introduce the 3D-CoT Benchmark, a dataset with hierarchical CoT annotations covering shape recognition, functional inference, and causal reasoning. Through controlled experiments, we compare CoT-structured and standard textual annotations across large reasoning models (LRMs) and large language models (LLMs). Our evaluation employs a dual-layer framework assessing both intermediate reasoning and final inference quality. Extensive experiments demonstrate that CoT significantly improves 3D semantic grounding, with LRMs leveraging CoT more effectively than LLMs. Furthermore, we highlight that annotation structure influences performance-explicit reasoning markers aid LLMs, while unmarked CoT better aligns with LRM inference patterns. Our analyses suggest that CoT is crucial for enhancing multimodal reasoning, with implications beyond 3D tasks.

[Arxiv](https://arxiv.org/abs/2503.06232)