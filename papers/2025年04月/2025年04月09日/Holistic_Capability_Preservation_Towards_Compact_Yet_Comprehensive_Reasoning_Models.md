# 全能力保留：探索紧凑而全面的推理模型

发布时间：2025年04月09日

`LLM应用` `人工智能`

> Holistic Capability Preservation: Towards Compact Yet Comprehensive Reasoning Models

# 摘要

> 本技术报告介绍 Ring-Lite-Distill，一款从开源专家混合模型（MoE）大型语言模型 Ling-Lite 衍生而来的轻量级推理模型。研究证明，通过精心整理的高质量数据和巧妙的训练范式，这款紧凑的 MoE 模型 Ling-Lite 可进一步训练，实现卓越推理能力，同时保持仅 2.75 亿激活参数的参数高效架构，打造高效轻量级推理架构。值得注意的是，在构建此模型时，我们不仅专注于提升高级推理能力（如解决高难度数学问题），更致力于开发能力覆盖更全面的推理模型。我们的方法确保在覆盖不同难度级别的推理任务的同时，保留通用能力，包括指令遵循、工具使用和知识保留。测试结果显示，Ring-Lite-Distill 的推理能力与 DeepSeek-R1-Distill-Qwen-7B 相当，而其通用能力则显著超越后者。模型已开源，可在 https://huggingface.co/inclusionAI 获取。

> This technical report presents Ring-Lite-Distill, a lightweight reasoning model derived from our open-source Mixture-of-Experts (MoE) Large Language Models (LLMs) Ling-Lite. This study demonstrates that through meticulous high-quality data curation and ingenious training paradigms, the compact MoE model Ling-Lite can be further trained to achieve exceptional reasoning capabilities, while maintaining its parameter-efficient architecture with only 2.75 billion activated parameters, establishing an efficient lightweight reasoning architecture. In particular, in constructing this model, we have not merely focused on enhancing advanced reasoning capabilities, exemplified by high-difficulty mathematical problem solving, but rather aimed to develop a reasoning model with more comprehensive competency coverage. Our approach ensures coverage across reasoning tasks of varying difficulty levels while preserving generic capabilities, such as instruction following, tool use, and knowledge retention. We show that, Ring-Lite-Distill's reasoning ability reaches a level comparable to DeepSeek-R1-Distill-Qwen-7B, while its general capabilities significantly surpass those of DeepSeek-R1-Distill-Qwen-7B. The models are accessible at https://huggingface.co/inclusionAI

[Arxiv](https://arxiv.org/abs/2504.07158)