# QHackBench：基于 PennyLane 黑客马拉松挑战的大型语言模型量子代码生成评估基准

发布时间：2025年06月24日

`LLM应用` `量子计算` `代码生成`

> QHackBench: Benchmarking Large Language Models for Quantum Code Generation Using PennyLane Hackathon Challenges

# 摘要

> # 摘要
大型语言模型（LLMs）在代码生成领域展现出强大潜力，但其在量子计算领域的应用仍有待深入探索。本文基于量子黑客马拉松（QHack）中的实际挑战，对基于PennyLane的量子代码生成进行了系统性基准测试。我们推出了QHackBench——一个源自QHack竞赛的新颖数据集，并在标准提示与检索增强生成（RAG）两种模式下评估模型性能。通过结构化的评估框架，我们从功能正确性、语法有效性和执行成功率三个维度，对不同难度的挑战进行了全面分析。实验结果表明，借助增强的PennyLane数据集，RAG增强型模型在复杂量子算法中的表现可与标准提示方法相媲美。此外，我们还开发了一个多智能体评估流水线，通过迭代优化错误方案，进一步提升了执行成功率。为了推动量子编程的AI辅助研究，我们承诺公开发布QHackBench数据集、评估框架及实验结果，助力该领域的持续突破。

> Recent advances in Large Language Models (LLMs) have demonstrated strong potential in code generation, yet their effectiveness in quantum computing remains underexplored. This paper benchmarks LLMs for PennyLane-based quantum code generation using real-world challenges from the Quantum Hackathon (QHack). We introduce QHackBench, a novel benchmark dataset derived from QHack competitions, and evaluate model performance under vanilla prompting and Retrieval-Augmented Generation (RAG). Our structured evaluation framework assesses functional correctness, syntactic validity, and execution success across varying challenge difficulties. Results indicate that RAG-enhanced models, supplemented with an augmented PennyLane dataset, approximately generate similar results as the standard prompting, particularly in complex quantum algorithms. Additionally, we introduce a multi-agent evaluation pipeline that iteratively refines incorrect solutions, further enhancing execution success rates. To foster further research, we commit to publicly releasing QHackBench, along with our evaluation framework and experimental results, enabling continued advancements in AI-assisted quantum programming.

[Arxiv](https://arxiv.org/abs/2506.20008)