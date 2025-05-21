# 并非所有正确答案都同等重要：为何蒸馏来源至关重要

发布时间：2025年05月20日

`LLM应用` `人工智能`

> Not All Correct Answers Are Equal: Why Your Distillation Source Matters

# 摘要

> 蒸馏技术作为一种实用且有效的手段，已被证明能够显著提升开源语言模型的推理能力。在本研究中，我们通过收集来自三个先进的教师模型（AM-Thinking-v1、Qwen3-235B-A22B 和 DeepSeek-R1）在189万条共享语料库上的验证输出，开展了一项大规模的经验性推理数据蒸馏研究。我们构建了三个并行数据集，并对其分布进行了分析，发现AM-Thinking-v1蒸馏后的数据在标记长度多样性方面表现更优，且困惑度更低。在AIME2024、AIME2025、MATH500和LiveCodeBench等推理基准测试中，基于AM模型的学生模型始终表现出最佳性能（例如，在AIME2024中达到84.3分，在AIME2025中达到72.2分，在MATH500中达到98.4分，在LiveCodeBench中达到65.9分）。此外，该模型还表现出自适应输出行为，即针对更复杂的任务生成更长的回答，而对简单任务则生成较短的回答。这些发现凸显了高质量、经过验证的推理轨迹的价值。我们发布了AM-Thinking-v1和Qwen3-235B-A22B蒸馏后的数据集，以支持未来对开放性和高性能推理导向语言模型的研究。这些数据集可在Hugging Face上公开获取ootnote{数据集在Hugging Face上可获取：\href{https://huggingface.co/datasets/a-m-team/AM-Thinking-v1-Distilled}{AM-Thinking-v1-Distilled}，\href{https://huggingface.co/datasets/a-m-team/AM-Qwen3-Distilled}{AM-Qwen3-Distilled}}。


> Distillation has emerged as a practical and effective approach to enhance the reasoning capabilities of open-source language models. In this work, we conduct a large-scale empirical study on reasoning data distillation by collecting verified outputs from three state-of-the-art teacher models-AM-Thinking-v1, Qwen3-235B-A22B, and DeepSeek-R1-on a shared corpus of 1.89 million queries. We construct three parallel datasets and analyze their distributions, revealing that AM-Thinking-v1-distilled data exhibits greater token length diversity and lower perplexity. Student models trained on each dataset are evaluated on reasoning benchmarks including AIME2024, AIME2025, MATH500, and LiveCodeBench. The AM-based model consistently achieves the best performance (e.g., 84.3 on AIME2024, 72.2 on AIME2025, 98.4 on MATH500, and 65.9 on LiveCodeBench) and demonstrates adaptive output behavior-producing longer responses for harder tasks and shorter ones for simpler tasks. These findings highlight the value of high-quality, verified reasoning traces. We release the AM-Thinking-v1 and Qwen3-235B-A22B distilled datasets to support future research on open and high-performing reasoning-oriented language models. The datasets are publicly available on Hugging Face\footnote{Datasets are available on Hugging Face: \href{https://huggingface.co/datasets/a-m-team/AM-Thinking-v1-Distilled}{AM-Thinking-v1-Distilled}, \href{https://huggingface.co/datasets/a-m-team/AM-Qwen3-Distilled}{AM-Qwen3-Distilled}.}.

[Arxiv](https://arxiv.org/abs/2505.14464)