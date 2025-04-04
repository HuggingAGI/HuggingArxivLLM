# 推理与压缩的碰撞：压缩大型推理模型在复杂推理任务上的基准测试

发布时间：2025年04月02日

`LLM应用` `模型压缩`

> When Reasoning Meets Compression: Benchmarking Compressed Large Reasoning Models on Complex Reasoning Tasks

# 摘要

> 开源大型推理模型（LRMs）在复杂推理任务中表现出色，但其庞大的参数量使个人难以负担。大型语言模型（LLMs）的压缩技术为降低计算成本提供了有效解决方案。然而，关于压缩后LLMs在复杂推理任务中的性能，尤其是对LRMs的系统性研究仍存在空白。现有量化和剪枝研究主要关注语言建模性能的保持，而蒸馏研究尚未全面基于推理难度或压缩对知识和推理的影响来评估学生模型。本文使用量化、蒸馏和剪枝方法，在涵盖从数学推理到多跳推理的四个数据集（AIME 2024、FOLIO、Temporal Sequences of BIG-Bench Hard 和 MuSiQue）上对压缩后的DeepSeek-R1模型进行了基准测试。我们对采用动态量化的2.51位、1.73位和1.58位R1模型进行了评估，并对基于LLaMA或Qwen的蒸馏R1模型进行了测试，运行SparseGPT以获得不同稀疏度水平。通过研究压缩后LRMs的性能和行为，我们报告了其性能得分和推理时计算量（每个问题消耗的token数量）。值得注意的是，通过MuSiQue，我们发现参数数量对LRMs的知识记忆能力的影响远大于对其推理能力的影响，这为压缩技术的选择提供了参考。通过实证分析推理时计算量，我们发现与R1及其压缩变体在多个基准测试中，较短的模型输出通常比较长的输出表现更好，这凸显了更简洁的推理链路的重要性。

> Recent open-source large reasoning models (LRMs) exhibit strong performance on complex reasoning tasks, but their large parameter count makes them prohibitively expensive for individuals. The compression of large language models (LLMs) offers an effective solution to reduce cost of computational resources. However, systematic studies on the performance of compressed LLMs in complex reasoning tasks, especially for LRMs, are lacking. Most works on quantization and pruning focus on preserving language modeling performance, while existing distillation works do not comprehensively benchmark student models based on reasoning difficulty or compression impact on knowledge and reasoning. In this paper, we benchmark compressed DeepSeek-R1 models on four different reasoning datasets (AIME 2024, FOLIO, Temporal Sequences of BIG-Bench Hard, and MuSiQue), ranging from mathematical to multihop reasoning, using quantization, distillation, and pruning methods. We benchmark 2.51-, 1.73-, and 1.58-bit R1 models that adopt dynamic quantization. We also benchmark distilled R1 models that are based on LLaMA or Qwen and run SparseGPT on them to obtain various sparsity levels. Studying the performance and behavior of compressed LRMs, we report their performance scores and test-time compute (number of tokens spent on each question). Notably, using MuSiQue, we find that parameter count has a much greater impact on LRMs' knowledge memorization than on their reasoning capability, which can inform the choice of compression techniques. Through our empirical analysis of test-time compute, we find that shorter model outputs generally achieve better performance than longer ones across several benchmarks for both R1 and its compressed variants, highlighting the need for more concise reasoning chains.

[Arxiv](https://arxiv.org/abs/2504.02010)