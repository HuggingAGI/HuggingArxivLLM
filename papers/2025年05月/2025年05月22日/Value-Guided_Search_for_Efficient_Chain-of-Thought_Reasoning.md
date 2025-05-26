# # 价值引导的搜索，优化高效链式推理

发布时间：2025年05月22日

`LLM应用`

> Value-Guided Search for Efficient Chain-of-Thought Reasoning

# 摘要

> 本文提出了一种简单高效的方法，用于长上下文推理轨迹的价值模型训练。与现有方法相比，我们无需定义难以界定的“步骤”概念。通过收集250万推理轨迹的数据集，训练了一个15亿参数的token级价值模型，并将其应用于DeepSeek模型，实现计算扩展性能提升。实验表明，结合块式价值引导搜索（VGS）和加权多数投票的方法，在测试时扩展性上优于传统方法。在64次生成预算下，VGS结合DeepSeek-R1-Distill-1.5B在四个竞赛数学基准测试中达到45.7%的平均准确率，与o3-mini-medium持平。此外，VGS大幅降低了实现相同性能所需的推理计算量。我们的数据集、模型和代码库已开源。

> In this paper, we propose a simple and efficient method for value model training on long-context reasoning traces. Compared to existing process reward models (PRMs), our method does not require a fine-grained notion of "step," which is difficult to define for long-context reasoning models. By collecting a dataset of 2.5 million reasoning traces, we train a 1.5B token-level value model and apply it to DeepSeek models for improved performance with test-time compute scaling. We find that block-wise value-guided search (VGS) with a final weighted majority vote achieves better test-time scaling than standard methods such as majority voting or best-of-n. With an inference budget of 64 generations, VGS with DeepSeek-R1-Distill-1.5B achieves an average accuracy of 45.7% across four competition math benchmarks (AIME 2024 & 2025, HMMT Feb 2024 & 2025), reaching parity with o3-mini-medium. Moreover, VGS significantly reduces the inference FLOPs required to achieve the same performance of majority voting. Our dataset, model and codebase are open-sourced.

[Arxiv](https://arxiv.org/abs/2505.17373)