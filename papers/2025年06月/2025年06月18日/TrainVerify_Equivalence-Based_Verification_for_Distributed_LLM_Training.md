# # TrainVerify：分布式LLM训练的等价性验证方法

发布时间：2025年06月18日

`LLM理论

摘要讨论了大规模训练大型语言模型时的验证问题，并提出了一种名为TrainVerify的系统，用于验证分布式训练的正确性。这涉及到训练过程的理论和方法，因此归类为LLM理论。` `人工智能` `分布式计算`

> TrainVerify: Equivalence-Based Verification for Distributed LLM Training

# 摘要

> 大规模训练大型语言模型 (LLMs) 需要在数千个设备上并行执行，计算成本巨大。然而，这些昂贵的分布式训练过程往往缺乏验证，容易出现潜在错误，导致大量 GPU 资源浪费。我们提出了 TrainVerify，一个用于可验证分布式训练 LLM 的系统。TrainVerify 以深度学习模型的逻辑规范作为基准，正式验证分布式并行执行计划与之数学等价。直接验证因 LLM 的巨大规模而闻名困难，通常涉及数十亿变量和极其复杂的计算图。因此，TrainVerify 引入了形状缩减技术以及分阶段的并行验证算法，在保持形式正确性的同时显著降低了复杂性。TrainVerify 可扩展到前沿的 LLM，包括成功验证 Llama3 (405B) 和 DeepSeek-V3 (671B) 的训练计划。

> Training large language models (LLMs) at scale requires parallel execution across thousands of devices, incurring enormous computational costs. Yet, these costly distributed trainings are rarely verified, leaving them prone to silent errors and potentially wasting millions of GPU hours. We introduce TrainVerify, a system for verifiable distributed training of LLMs. Given a deep learning model's logical specification as the ground truth, TrainVerify formally verifies that a distributed parallel execution plan is mathematically equivalent to it. Direct verification is notoriously difficult due to the sheer scale of LLMs which often involves billions of variables and highly intricate computation graphs. Therefore, TrainVerify introduces shape-reduction techniques and a stage-wise parallel verification algorithm that significantly reduces complexity while preserving formal correctness. TrainVerify scales to frontier LLMs, including the successful verification of the Llama3 (405B) and DeepSeek-V3 (671B) training plans.

[Arxiv](https://arxiv.org/abs/2506.15961)