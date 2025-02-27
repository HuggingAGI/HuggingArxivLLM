# # 数据高效多智能体空间规划与大型语言模型（LLMs）
利用大型语言模型（LLMs）实现高效多智能体空间规划。

发布时间：2025年02月25日

`LLM应用` `人工智能`

> Data-Efficient Multi-Agent Spatial Planning with LLMs

# 摘要

> 本项目旨在探索如何利用预训练大型语言模型的全球知识储备，提升多智能体决策中的学习效率与稳健性。我们以出租车路线规划与分配问题为例，研究智能体如何最优接载乘客以最小化总体等待时间。尽管该问题基于图形道路网络，但通过适当提示，零样本学习在此任务上表现优异。更重要的是，结合有限微调和逐次展开的前瞻算法，大型语言模型在环境交互次数减少50倍的情况下，仍能超越现有方法。我们还发现，将某些易于计算的信息纳入提示，能显著提升性能。最后，大型语言模型内置的语义理解能力也得到了充分展示，其通过简单提示即可适应环境因素的潜力令人瞩目。

> In this project, our goal is to determine how to leverage the world-knowledge of pretrained large language models for efficient and robust learning in multiagent decision making. We examine this in a taxi routing and assignment problem where agents must decide how to best pick up passengers in order to minimize overall waiting time. While this problem is situated on a graphical road network, we show that with the proper prompting zero-shot performance is quite strong on this task. Furthermore, with limited fine-tuning along with the one-at-a-time rollout algorithm for look ahead, LLMs can out-compete existing approaches with 50 times fewer environmental interactions. We also explore the benefits of various linguistic prompting approaches and show that including certain easy-to-compute information in the prompt significantly improves performance. Finally, we highlight the LLM's built-in semantic understanding, showing its ability to adapt to environmental factors through simple prompts.

[Arxiv](https://arxiv.org/abs/2502.18822)