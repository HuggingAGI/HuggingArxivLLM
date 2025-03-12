# 自我教导的自我修正：小型语言模型的优化研究

发布时间：2025年03月11日

`LLM理论` `问答系统`

> Self-Taught Self-Correction for Small Language Models

# 摘要

> 大型语言模型（LLMs）虽然在多种任务中表现出色，但仍然容易出错。如何让模型自我纠错是一个关键挑战。以往研究多依赖外部工具或大型专有模型，而我们通过迭代微调，仅使用自动生成的数据，在小型语言模型（SLMs）中探索自我纠错的可能性。我们提出的Self-Taught Self-Correction（STaSC）算法融合了多种设计思路。实验结果表明，STaSC在问答任务中显著提升了性能。通过深入分析，我们揭示了自我纠错的内在机制，以及不同设计选择对学习效果和整体表现的影响。为了助力未来研究，我们开源了用户友好的代码库和轻量级模型。

> Although large language models (LLMs) have achieved remarkable performance across various tasks, they remain prone to errors. A key challenge is enabling them to self-correct. While prior research has relied on external tools or large proprietary models, this work explores self-correction in small language models (SLMs) through iterative fine-tuning using solely self-generated data. We introduce the Self-Taught Self-Correction (STaSC) algorithm, which incorporates multiple algorithmic design choices. Experimental results on a question-answering task demonstrate that STaSC effectively learns self-correction, leading to significant performance improvements. Our analysis further provides insights into the mechanisms of self-correction and the impact of different design choices on learning dynamics and overall performance. To support future research, we release our user-friendly codebase and lightweight models.

[Arxiv](https://arxiv.org/abs/2503.08681)