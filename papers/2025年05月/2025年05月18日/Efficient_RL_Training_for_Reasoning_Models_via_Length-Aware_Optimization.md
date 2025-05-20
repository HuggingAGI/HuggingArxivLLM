# 高效强化学习训练方法用于推理模型：基于长度感知优化

发布时间：2025年05月18日

`LLM理论` `人工智能` `推理系统`

> Efficient RL Training for Reasoning Models via Length-Aware Optimization

# 摘要

> 大型推理模型（如 OpenAI o1 和 DeepSeek R1）在推理任务中表现卓越，但其推理路径往往漫长且消耗大量内存和时间。现有方法主要通过增加训练数据和阶段来缩短推理路径。本文提出三项关键奖励设计，直接整合到大型推理模型的强化学习过程中，无需额外训练阶段即可减少响应长度。实验结果表明，我们的方法在保持或提升性能的同时，显著缩短了响应长度。具体而言，在逻辑推理任务中，我们实现了平均步骤数减少 40% 的响应长度，并获得了 14% 的性能提升。对于数学问题，我们在保持性能的同时，将平均步骤数的响应长度减少了 33%。

> Large reasoning models, such as OpenAI o1 or DeepSeek R1, have demonstrated remarkable performance on reasoning tasks but often incur a long reasoning path with significant memory and time costs. Existing methods primarily aim to shorten reasoning paths by introducing additional training data and stages. In this paper, we propose three critical reward designs integrated directly into the reinforcement learning process of large reasoning models, which reduce the response length without extra training stages. Experiments on four settings show that our method significantly decreases response length while maintaining or even improving performance. Specifically, in a logic reasoning setting, we achieve a 40% reduction in response length averaged by steps alongside a 14% gain in performance. For math problems, we reduce response length averaged by steps by 33% while preserving performance.

[Arxiv](https://arxiv.org/abs/2505.12284)