# TAMMs：时间感知多模态模型，应用于卫星图像变化理解与预测

发布时间：2025年06月23日

`LLM应用` `时空分析`

> TAMMs: Temporal-Aware Multimodal Model for Satellite Image Change Understanding and Forecasting

# 摘要

> 卫星图像时间序列分析需要细致的时空推理能力，这仍然是现有 multimodal 大语言模型 (MLLMs) 的挑战。本研究探讨了 MLLMs 在时间变化理解与未来场景生成任务上的能力，旨在评估其在复杂多模态时序动态建模方面的潜力。我们提出了 TAMMs，一种用于卫星图像变化理解和预测的时序感知多模态模型。通过轻量级时序模块增强冻结的 MLLMs，实现结构化序列编码和上下文提示。TAMMs 引入了语义融合控制注入 (SFCI) 机制，在增强的 ControlNet 中自适应地结合高层次语义推理和结构先验，实现双路径条件下的时间一致且语义有依据的图像合成。实验表明，TAMMs 在时间变化理解和未来图像预测任务上均超越了强大的 MLLM 基线模型，突显了精心设计的时序推理和语义融合如何能够充分释放 MLLMs 在时空理解方面的潜力。

> Satellite image time-series analysis demands fine-grained spatial-temporal reasoning, which remains a challenge for existing multimodal large language models (MLLMs). In this work, we study the capabilities of MLLMs on a novel task that jointly targets temporal change understanding and future scene generation, aiming to assess their potential for modeling complex multimodal dynamics over time. We propose TAMMs, a Temporal-Aware Multimodal Model for satellite image change understanding and forecasting, which enhances frozen MLLMs with lightweight temporal modules for structured sequence encoding and contextual prompting. To guide future image generation, TAMMs introduces a Semantic-Fused Control Injection (SFCI) mechanism that adaptively combines high-level semantic reasoning and structural priors within an enhanced ControlNet. This dual-path conditioning enables temporally consistent and semantically grounded image synthesis. Experiments demonstrate that TAMMs outperforms strong MLLM baselines in both temporal change understanding and future image forecasting tasks, highlighting how carefully designed temporal reasoning and semantic fusion can unlock the full potential of MLLMs for spatio-temporal understanding.

[Arxiv](https://arxiv.org/abs/2506.18862)