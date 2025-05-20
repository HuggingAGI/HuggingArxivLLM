# # 通过长度感知优化提升推理模型的强化学习训练效率

发布时间：2025年05月18日

`LLM理论` `推理模型` `机器学习`

> Efficient RL Training for Reasoning Models via Length-Aware Optimization

# 摘要

> 大型推理模型（如 OpenAI o1 和 DeepSeek R1）在推理任务中表现优异，但其推理过程往往耗时长、占用大量内存。现有方法主要通过增加训练数据和阶段来缩短推理路径。本文提出了一种创新性解决方案：将三种关键奖励设计直接融入大型推理模型的强化学习过程，无需额外训练阶段即可大幅缩短响应长度。实验结果表明，我们的方法在保持甚至提升性能的同时，显著减少了响应长度。具体而言，在逻辑推理任务中，平均步骤数减少了 40%，性能提升了 14%；在数学问题中，平均步骤数减少 33%，同时保持了原有性能。

> Large reasoning models, such as OpenAI o1 or DeepSeek R1, have demonstrated remarkable performance on reasoning tasks but often incur a long reasoning path with significant memory and time costs. Existing methods primarily aim to shorten reasoning paths by introducing additional training data and stages. In this paper, we propose three critical reward designs integrated directly into the reinforcement learning process of large reasoning models, which reduce the response length without extra training stages. Experiments on four settings show that our method significantly decreases response length while maintaining or even improving performance. Specifically, in a logic reasoning setting, we achieve a 40% reduction in response length averaged by steps alongside a 14% gain in performance. For math problems, we reduce response length averaged by steps by 33% while preserving performance.

[Arxiv](https://arxiv.org/abs/2505.12284)