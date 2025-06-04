# 主动学习中没有免费午餐：LLM嵌入质量是查询策略成功的关键

发布时间：2025年05月18日

`LLM应用` `主动学习`

> No Free Lunch in Active Learning: LLM Embedding Quality Dictates Query Strategy Success

# 摘要

> 大型语言模型（LLMs）的诞生让我们重新审视了深度主动学习（AL）的实用性。通过利用冻结的LLM嵌入，我们可以降低大型主干模型迭代微调的计算成本。本研究建立了一个基准，并系统性地探讨了LLM嵌入质量对深度AL中查询策略的影响。我们采用了来自MTEB排行榜上的五款顶级模型以及两个基线模型，针对十个多样化的文本分类任务进行了研究。研究发现：1. 基于多样性的采样方法初始化标注池，能够与高质量嵌入协同工作，提升主动学习早期迭代的性能表现；2. 最优查询策略的选择对嵌入质量非常敏感。虽然Margin采样方法计算成本低廉，但Badge策略在跨任务时表现出了更大的鲁棒性；3. 当这些策略与更高质量的嵌入结合使用时，它们的有效性往往会得到增强。我们的研究结果强调了根据具体上下文评估AL策略的必要性，因为性能表现很大程度上取决于嵌入质量和目标任务。

> The advent of large language models (LLMs) capable of producing general-purpose representations lets us revisit the practicality of deep active learning (AL): By leveraging frozen LLM embeddings, we can mitigate the computational costs of iteratively fine-tuning large backbones. This study establishes a benchmark and systematically investigates the influence of LLM embedding quality on query strategies in deep AL. We employ five top-performing models from the massive text embedding benchmark (MTEB) leaderboard and two baselines for ten diverse text classification tasks. Our findings reveal key insights: First, initializing the labeled pool using diversity-based sampling synergizes with high-quality embeddings, boosting performance in early AL iterations. Second, the choice of the optimal query strategy is sensitive to embedding quality. While the computationally inexpensive Margin sampling can achieve performance spikes on specific datasets, we find that strategies like Badge exhibit greater robustness across tasks. Importantly, their effectiveness is often enhanced when paired with higher-quality embeddings. Our results emphasize the need for context-specific evaluation of AL strategies, as performance heavily depends on embedding quality and the target task.

[Arxiv](https://arxiv.org/abs/2506.01992)