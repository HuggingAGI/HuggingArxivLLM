# AutoJudge：无需人工标注的智能解码评估

发布时间：2025年04月28日

`LLM应用`

> AutoJudge: Judge Decoding Without Manual Annotation

# 摘要

> 我们介绍 AutoJudge，一个通过任务特定的有损推测解码加速大型语言模型（LLM）推理的框架。不同于传统的逐词匹配原模型输出分布的方法，我们专注于识别哪些生成的令牌会影响最终生成响应的质量，从而放宽保证，使“不重要”的令牌能够更快生成。我们的方法采用半贪婪搜索算法，用于测试目标模型与草稿模型之间的哪些不匹配需要纠正以保持质量，哪些可以跳过。随后，我们基于现有 LLM 嵌入训练一个轻量级分类器，用于在推理时预测哪些不匹配的令牌可以被轻松接受，而不会影响最终答案的质量。我们在零样本 GSM8K 推理任务中使用 Llama 3.2 1B（草稿）和 Llama 3.1 8B（目标）模型对我们的方法进行测试，与标准推测解码相比，每轮验证中接受的令牌数量增加了 1.5 倍，答案准确率仅下降不到 1%，与小幅度准确率损失相比，速度提升超过 2 倍。当应用于 LiveCodeBench 基准测试时，我们的方法能够自动检测其他特定于编程的重要令牌，并显示出类似的加速效果，证明了其跨任务的泛化能力。

> We introduce AutoJudge, a framework that accelerates large language model (LLM) inference with task-specific lossy speculative decoding. Instead of matching the original model output distribution token-by-token, we identify which of the generated tokens affect the downstream quality of the generated response, relaxing the guarantee so that the "unimportant" tokens can be generated faster. Our approach relies on a semi-greedy search algorithm to test which of the mismatches between target and draft model should be corrected to preserve quality, and which ones may be skipped. We then train a lightweight classifier based on existing LLM embeddings to predict, at inference time, which mismatching tokens can be safely accepted without compromising the final answer quality. We test our approach with Llama 3.2 1B (draft) and Llama 3.1 8B (target) models on zero-shot GSM8K reasoning, where it achieves up to 1.5x more accepted tokens per verification cycle with under 1% degradation in answer accuracy compared to standard speculative decoding and over 2x with small loss in accuracy. When applied to the LiveCodeBench benchmark, our approach automatically detects other, programming-specific important tokens and shows similar speedups, demonstrating its ability to generalize across tasks.

[Arxiv](https://arxiv.org/abs/2504.20039)