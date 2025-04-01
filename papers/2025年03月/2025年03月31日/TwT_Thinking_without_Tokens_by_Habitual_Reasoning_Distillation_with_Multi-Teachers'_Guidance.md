# TwT：无token思考，通过多教师指导下的习惯性推理蒸馏实现

发布时间：2025年03月31日

`LLM应用` `人工智能`

> TwT: Thinking without Tokens by Habitual Reasoning Distillation with Multi-Teachers' Guidance

# 摘要

> 大型语言模型（LLMs）在整合推理过程后，问题解决能力显著提升。然而，增强的推理能力导致推理过程中的输出标记数量显著增加，进而提高了计算成本。为应对这一挑战，我们提出了TwT（无标记思考）方法，通过多教师指导的习惯性推理蒸馏，在保持高性能的同时有效降低推理时间成本。我们的方法引入了一种习惯性推理蒸馏技术，借助受人类认知启发的教师指导压缩策略，将显式的推理过程内化为模型的习惯行为。此外，我们还提出了双准则拒绝采样（DCRS）技术，通过多教师模型生成高质量且多样化的蒸馏数据集，使该方法适用于无监督场景。实验结果表明，TwT在减少推理成本的同时保持了卓越性能，与其它蒸馏方法相比，在输出标记更少的情况下，准确率提升了13.6%，为实现高效LLM部署提供了极具实用价值的解决方案。

> Large Language Models (LLMs) have made significant strides in problem-solving by incorporating reasoning processes. However, this enhanced reasoning capability results in an increased number of output tokens during inference, leading to higher computational costs. To address this challenge, we propose TwT (Thinking without Tokens), a method that reduces inference-time costs through habitual reasoning distillation with multi-teachers' guidance, while maintaining high performance. Our approach introduces a Habitual Reasoning Distillation method, which internalizes explicit reasoning into the model's habitual behavior through a Teacher-Guided compression strategy inspired by human cognition. Additionally, we propose Dual-Criteria Rejection Sampling (DCRS), a technique that generates a high-quality and diverse distillation dataset using multiple teacher models, making our method suitable for unsupervised scenarios. Experimental results demonstrate that TwT effectively reduces inference costs while preserving superior performance, achieving up to a 13.6% improvement in accuracy with fewer output tokens compared to other distillation methods, offering a highly practical solution for efficient LLM deployment.

[Arxiv](https://arxiv.org/abs/2503.24198)