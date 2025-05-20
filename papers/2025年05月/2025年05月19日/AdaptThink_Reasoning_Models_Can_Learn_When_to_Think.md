# # 自适应思考：推理模型学会何时思考

发布时间：2025年05月19日

`LLM应用

理由：这篇论文主要探讨了如何优化大型语言模型（LLM）的推理过程，特别是通过自适应选择思考模式来提升模型的效率和性能。虽然它涉及强化学习算法（AdaptThink），但其核心目标是改进LLM的应用效果，因此归类为LLM应用。` `人工智能`

> AdaptThink: Reasoning Models Can Learn When to Think

# 摘要

> 大型推理模型 recently通过模拟人类的深度思考，在多种任务中展现出了令人惊叹的能力。然而，冗长的思考过程显著增加了推理开销，效率成为了关键瓶颈。在这项研究中，我们首先发现NoThinking——即让推理模型跳过思考环节，直接输出最终解决方案——在相对简单的任务中，无论是在性能还是效率上，都是更优的选择。基于这一发现，我们提出了AdaptThink，一种全新的强化学习算法，旨在让推理模型根据问题难度自适应地选择最优的思考模式。具体来说，AdaptThink包含两大核心组件：(1) 约束优化目标，鼓励模型在保持整体性能的同时优先选择NoThinking；(2) 重要性采样策略，通过在策略训练中平衡Thinking和NoThinking样本，实现冷启动，并让模型在整个训练过程中灵活探索和利用两种思考模式。实验结果表明，AdaptThink不仅显著降低了推理成本，还进一步提升了模型性能。值得注意的是，在三个数学数据集上，AdaptThink使DeepSeek-R1-Distill-Qwen-1.5B的平均响应长度减少了53%，准确率提升了2.4%，这充分证明了自适应选择思考模式在优化推理质量和效率平衡方面的巨大潜力。我们的代码和模型已开源，详情请访问https://github.com/THU-KEG/AdaptThink。


> Recently, large reasoning models have achieved impressive performance on various tasks by employing human-like deep thinking. However, the lengthy thinking process substantially increases inference overhead, making efficiency a critical bottleneck. In this work, we first demonstrate that NoThinking, which prompts the reasoning model to skip thinking and directly generate the final solution, is a better choice for relatively simple tasks in terms of both performance and efficiency. Motivated by this, we propose AdaptThink, a novel RL algorithm to teach reasoning models to choose the optimal thinking mode adaptively based on problem difficulty. Specifically, AdaptThink features two core components: (1) a constrained optimization objective that encourages the model to choose NoThinking while maintaining the overall performance; (2) an importance sampling strategy that balances Thinking and NoThinking samples during on-policy training, thereby enabling cold start and allowing the model to explore and exploit both thinking modes throughout the training process. Our experiments indicate that AdaptThink significantly reduces the inference costs while further enhancing performance. Notably, on three math datasets, AdaptThink reduces the average response length of DeepSeek-R1-Distill-Qwen-1.5B by 53% and improves its accuracy by 2.4%, highlighting the promise of adaptive thinking-mode selection for optimizing the balance between reasoning quality and efficiency. Our codes and models are available at https://github.com/THU-KEG/AdaptThink.

[Arxiv](https://arxiv.org/abs/2505.13417)