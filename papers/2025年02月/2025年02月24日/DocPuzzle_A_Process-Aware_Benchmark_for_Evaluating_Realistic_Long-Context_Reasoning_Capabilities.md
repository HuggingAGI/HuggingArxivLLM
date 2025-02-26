# # DocPuzzle：一个评估现实长上下文推理能力的过程感知基准

发布时间：2025年02月24日

`LLM应用` `人工智能`

> DocPuzzle: A Process-Aware Benchmark for Evaluating Realistic Long-Context Reasoning Capabilities

# 摘要

> 我们提出 DocPuzzle，一个严格构建的基准测试，用于评估大型语言模型 (LLMs) 的长上下文推理能力。该基准包含 100 个专家级别的问答问题，要求在长篇真实文档中进行多步推理。为确保任务质量和复杂性，我们采用了人机协作的注释验证流水线。DocPuzzle 引入了一个创新的评估框架，通过清单引导的过程分析来缓解猜测偏差，为评估 LLM 的推理能力设立了新标准。评估结果显示：1) 高级慢思考推理模型如 o1-preview（69.7%）和 DeepSeek-R1（66.3%）显著优于最佳通用指令模型如 Claude 3.5 Sonnet（57.7%）；2) 蒸馏推理模型如 DeepSeek-R1-Distill-Qwen-32B（41.3%）远落后于教师模型，表明仅依赖蒸馏难以保持推理能力的泛化性。

> We present DocPuzzle, a rigorously constructed benchmark for evaluating long-context reasoning capabilities in large language models (LLMs). This benchmark comprises 100 expert-level QA problems requiring multi-step reasoning over long real-world documents. To ensure the task quality and complexity, we implement a human-AI collaborative annotation-validation pipeline. DocPuzzle introduces an innovative evaluation framework that mitigates guessing bias through checklist-guided process analysis, establishing new standards for assessing reasoning capacities in LLMs. Our evaluation results show that: 1)Advanced slow-thinking reasoning models like o1-preview(69.7%) and DeepSeek-R1(66.3%) significantly outperform best general instruct models like Claude 3.5 Sonnet(57.7%); 2)Distilled reasoning models like DeepSeek-R1-Distill-Qwen-32B(41.3%) falls far behind the teacher model, suggesting challenges to maintain the generalization of reasoning capabilities relying solely on distillation.

[Arxiv](https://arxiv.org/abs/2502.17807)