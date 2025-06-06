# # 大型语言模型作为数学问题求解器的自动鲁棒性压力测试

发布时间：2025年06月05日

`LLM应用

论文摘要：大型语言模型（LLMs）在各类推理密集型任务中表现卓越。然而，这些模型在某些简单的推理任务中仍可能遭遇稳健性问题，导致意外失败。以往研究主要依赖手工制作的模板或有限的扰动规则来评估LLMs的稳健性，这可能暗示着预训练或微调数据中存在污染。本研究受软件工程中的压力测试启发，提出了一种全新的框架——自动稳健性检查器（AR-Checker），用于生成与原问题语义一致但可能使LLMs失效的数学问题变体。该框架通过多轮并行流的LLM基改写和验证生成数学问题变体。我们的框架能够为每个LLM动态生成基准变体，从而最大限度地降低数据污染风险。实验结果表明，在GSM8K和MATH-500数据集上，AR-Checker在数学任务中表现出色。我们还对数学以外的基准进行了评估，包括MMLU、MMLU-Pro和CommonsenseQA，结果同样表现出色，进一步验证了AR-Checker的有效性。

LLM应用` `常识推理`

> Automatic Robustness Stress Testing of LLMs as Mathematical Problem Solvers

# 摘要

> 大型语言模型（LLMs）在各类推理密集型任务中表现卓越。然而，这些模型在某些简单的推理任务中仍可能遭遇稳健性问题，导致意外失败。以往研究主要依赖手工制作的模板或有限的扰动规则来评估LLMs的稳健性，这可能暗示着预训练或微调数据中存在污染。本研究受软件工程中的压力测试启发，提出了一种全新的框架——自动稳健性检查器（AR-Checker），用于生成与原问题语义一致但可能使LLMs失效的数学问题变体。该框架通过多轮并行流的LLM基改写和验证生成数学问题变体。我们的框架能够为每个LLM动态生成基准变体，从而最大限度地降低数据污染风险。实验结果表明，在GSM8K和MATH-500数据集上，AR-Checker在数学任务中表现出色。我们还对数学以外的基准进行了评估，包括MMLU、MMLU-Pro和CommonsenseQA，结果同样表现出色，进一步验证了AR-Checker的有效性。

> Large language models (LLMs) have achieved distinguished performance on various reasoning-intensive tasks. However, LLMs might still face the challenges of robustness issues and fail unexpectedly in some simple reasoning tasks. Previous works evaluate the LLM robustness with hand-crafted templates or a limited set of perturbation rules, indicating potential data contamination in pre-training or fine-tuning datasets. In this work, inspired by stress testing in software engineering, we propose a novel framework, Automatic Robustness Checker (AR-Checker), to generate mathematical problem variants that maintain the semantic meanings of the original one but might fail the LLMs. The AR-Checker framework generates mathematical problem variants through multi-round parallel streams of LLM-based rewriting and verification. Our framework can generate benchmark variants dynamically for each LLM, thus minimizing the risk of data contamination. Experiments on GSM8K and MATH-500 demonstrate the strong performance of AR-Checker on mathematical tasks. We also evaluate AR-Checker on benchmarks beyond mathematics, including MMLU, MMLU-Pro, and CommonsenseQA, where it also achieves strong performance, further proving the effectiveness of AR-Checker.

[Arxiv](https://arxiv.org/abs/2506.05038)