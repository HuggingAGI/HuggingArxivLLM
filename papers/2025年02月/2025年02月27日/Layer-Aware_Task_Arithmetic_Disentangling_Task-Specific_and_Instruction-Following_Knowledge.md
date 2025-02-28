# 层感知任务算术：分离任务特定知识与指令遵循能力

发布时间：2025年02月27日

`LLM理论` `人工智能` `机器学习`

> Layer-Aware Task Arithmetic: Disentangling Task-Specific and Instruction-Following Knowledge

# 摘要

> 大型语言模型（LLMs）通过微调展现出强大的任务特定能力，但合并多个微调模型通常会导致性能下降，这是由于指令遵循组件的重叠所致。任务算术（TA）通过结合微调任务向量实现多任务学习和任务遗忘，但难以分离任务特定知识与通用指令遵循行为。为解决这一问题，我们提出了基于层感知的任务算术（LATA），这是一种新型方法，根据任务向量与指令遵循或任务特定组件的对齐程度，为任务向量分配层特定权重。通过增强任务相关层并减弱指令遵循层，LATA在提升任务学习和遗忘性能的同时，保持了整体模型的实用性。在WikiText-2、GSM8K和HumanEval等多个基准上的实验表明，LATA在多任务学习和选择性任务遗忘方面均优于现有方法，实现了更高的任务准确性和对齐度，同时输出质量的下降幅度最小。我们的研究结果突显了分层分析在分离任务特定知识与通用知识方面的重要性，为高效模型合并和编辑提供了一个稳健的框架。


> Large language models (LLMs) demonstrate strong task-specific capabilities through fine-tuning, but merging multiple fine-tuned models often leads to degraded performance due to overlapping instruction-following components. Task Arithmetic (TA), which combines task vectors derived from fine-tuning, enables multi-task learning and task forgetting but struggles to isolate task-specific knowledge from general instruction-following behavior. To address this, we propose Layer-Aware Task Arithmetic (LATA), a novel approach that assigns layer-specific weights to task vectors based on their alignment with instruction-following or task-specific components. By amplifying task-relevant layers and attenuating instruction-following layers, LATA improves task learning and forgetting performance while preserving overall model utility. Experiments on multiple benchmarks, including WikiText-2, GSM8K, and HumanEval, demonstrate that LATA outperforms existing methods in both multi-task learning and selective task forgetting, achieving higher task accuracy and alignment with minimal degradation in output quality. Our findings highlight the importance of layer-wise analysis in disentangling task-specific and general-purpose knowledge, offering a robust framework for efficient model merging and editing.

[Arxiv](https://arxiv.org/abs/2502.20186)