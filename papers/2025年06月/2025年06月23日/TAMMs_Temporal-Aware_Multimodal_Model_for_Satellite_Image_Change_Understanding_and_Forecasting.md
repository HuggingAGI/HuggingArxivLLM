# TAMMs：时间感知多模态模型，专为卫星图像变化理解与预测而设计

发布时间：2025年06月23日

`LLM应用` `卫星遥感` `多模态模型`

> TAMMs: Temporal-Aware Multimodal Model for Satellite Image Change Understanding and Forecasting

# 摘要

> 卫星图像时间序列分析需要精细的空间-时间推理能力，这对现有的多模态大语言模型（MLLMs）仍是一个挑战。本研究探讨了MLLMs在一项新型任务中的能力，该任务旨在同时理解时间变化并生成未来场景，目标是评估其在建模复杂多模态动态过程中的潜力。我们提出了一种时间感知多模态模型TAMMs，专门用于卫星图像变化理解和预测。TAMMs通过轻量级时间模块增强了冻结的MLLMs，以实现结构化序列编码和上下文提示。为了引导未来的图像生成，TAMMs引入了一种语义融合控制注入（SFCI）机制，该机制在增强的ControlNet中自适应地结合了高级语义推理和结构先验。这种双路径条件设置使图像合成在时间上一致且语义上有依据。实验表明，TAMMs在时间变化理解和未来图像预测任务中均优于强大的MLLM基线模型，突显了精心设计的时间推理和语义融合如何能够充分发挥MLLMs在时空理解方面的潜力。

> Satellite image time-series analysis demands fine-grained spatial-temporal reasoning, which remains a challenge for existing multimodal large language models (MLLMs). In this work, we study the capabilities of MLLMs on a novel task that jointly targets temporal change understanding and future scene generation, aiming to assess their potential for modeling complex multimodal dynamics over time. We propose TAMMs, a Temporal-Aware Multimodal Model for satellite image change understanding and forecasting, which enhances frozen MLLMs with lightweight temporal modules for structured sequence encoding and contextual prompting. To guide future image generation, TAMMs introduces a Semantic-Fused Control Injection (SFCI) mechanism that adaptively combines high-level semantic reasoning and structural priors within an enhanced ControlNet. This dual-path conditioning enables temporally consistent and semantically grounded image synthesis. Experiments demonstrate that TAMMs outperforms strong MLLM baselines in both temporal change understanding and future image forecasting tasks, highlighting how carefully designed temporal reasoning and semantic fusion can unlock the full potential of MLLMs for spatio-temporal understanding.

[Arxiv](https://arxiv.org/abs/2506.18862)