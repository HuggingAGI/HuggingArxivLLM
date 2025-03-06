# KodCode：一个多样化、高难度且可验证的合成编码数据集

发布时间：2025年03月04日

`LLM应用` `人工智能`

> KodCode: A Diverse, Challenging, and Verifiable Synthetic Dataset for Coding

# 摘要

> 我们推出 KodCode，一个专为训练编程大型语言模型设计的合成数据集，旨在解决跨不同难度和领域获取高质量、可验证训练数据这一长期挑战。现有专注于代码的资源通常难以兼顾覆盖范围（如从简单任务到高级算法）和可验证正确性（如单元测试）。而 KodCode 通过系统性自我验证程序，由问题-解决方案-测试三元组构成。我们的生成流程始于广泛编程问题的合成，随后生成解决方案和测试用例，并为难题分配额外尝试。最后，通过将问题改写为多样格式，并基于测试的拒绝采样过程从推理模型（DeepSeek R1）生成响应，完成数据合成。这生成了一个大规模、稳健且多样化的编程数据集。KodCode 适用于监督微调，其配对单元测试也为强化学习调优提供了潜力。在 HumanEval(+)、MBPP(+)、BigCodeBench 和 LiveCodeBench 等编程基准测试上的实验表明，KodCode 调优的模型达到了最先进的性能，超越了 Qwen2.5-Coder-32B-Instruct 和 DeepSeek-R1-Distill-Llama-70B 等模型。

> We introduce KodCode, a synthetic dataset that addresses the persistent challenge of acquiring high-quality, verifiable training data across diverse difficulties and domains for training Large Language Models for coding. Existing code-focused resources typically fail to ensure either the breadth of coverage (e.g., spanning simple coding tasks to advanced algorithmic problems) or verifiable correctness (e.g., unit tests). In contrast, KodCode comprises question-solution-test triplets that are systematically validated via a self-verification procedure. Our pipeline begins by synthesizing a broad range of coding questions, then generates solutions and test cases with additional attempts allocated to challenging problems. Finally, post-training data synthesis is done by rewriting questions into diverse formats and generating responses under a test-based reject sampling procedure from a reasoning model (DeepSeek R1). This pipeline yields a large-scale, robust and diverse coding dataset. KodCode is suitable for supervised fine-tuning and the paired unit tests also provide great potential for RL tuning. Fine-tuning experiments on coding benchmarks (HumanEval(+), MBPP(+), BigCodeBench, and LiveCodeBench) demonstrate that KodCode-tuned models achieve state-of-the-art performance, surpassing models like Qwen2.5-Coder-32B-Instruct and DeepSeek-R1-Distill-Llama-70B.

[Arxiv](https://arxiv.org/abs/2503.02951)