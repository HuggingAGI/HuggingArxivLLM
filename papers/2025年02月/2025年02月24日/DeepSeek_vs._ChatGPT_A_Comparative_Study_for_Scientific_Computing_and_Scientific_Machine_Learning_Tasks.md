# DeepSeek 与 ChatGPT 对比研究：在科学计算与科学机器学习任务中的表现分析

发布时间：2025年02月24日

`LLM应用` `科学计算` `数学建模`

> DeepSeek vs. ChatGPT: A Comparative Study for Scientific Computing and Scientific Machine Learning Tasks

# 摘要

> 大型语言模型（LLMs）已在科学计算领域大放异彩，尤其在解决偏微分方程（PDEs）方面表现突出。然而，不同模型各有所长，性能表现因而各有千秋。本文对比了当前最先进的 LLMs——ChatGPT 和 DeepSeek，及其经过推理优化的版本，在计算任务中的表现。我们不仅考察了它们在传统科学计算中的数值问题解决能力，还评估了它们运用科学机器学习技术处理基于 PDE 的问题的水平。实验设计中，我们特别关注需要做出关键决策的场景，例如在神经算子学习中如何定义合适的输入函数空间。研究发现，最新版本 ChatGPT o3-mini-high 通常能提供最精准的结果，同时其响应速度也远超其推理版本 DeepSeek R1。这一速度与精度的双重优势，使其成为当前处理各类计算任务的理想选择。


> Large Language Models (LLMs) have emerged as powerful tools for tackling a wide range of problems, including those in scientific computing, particularly in solving partial differential equations (PDEs). However, different models exhibit distinct strengths and preferences, resulting in varying levels of performance. In this paper, we compare the capabilities of the most advanced LLMs--ChatGPT and DeepSeek--along with their reasoning-optimized versions in addressing computational challenges. Specifically, we evaluate their proficiency in solving traditional numerical problems in scientific computing as well as leveraging scientific machine learning techniques for PDE-based problems. We designed all our experiments so that a non-trivial decision is required, e.g. defining the proper space of input functions for neural operator learning. Our findings reveal that the latest model, ChatGPT o3-mini-high, usually delivers the most accurate results while also responding significantly faster than its reasoning counterpart, DeepSeek R1. This enhanced speed and accuracy make ChatGPT o3-mini-high a more practical and efficient choice for diverse computational tasks at this juncture.

[Arxiv](https://arxiv.org/abs/2502.17764)