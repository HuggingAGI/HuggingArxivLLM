# 主动学习中的免费午餐：LLM嵌入质量决定主动学习查询策略成败

发布时间：2025年05月18日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在主动学习中的应用，特别是如何利用LLM嵌入来优化主动学习策略。研究重点在于应用层面，分析嵌入质量对策略的影响，属于LLM应用的范畴。` `数据科学`

> No Free Lunch in Active Learning: LLM Embedding Quality Dictates Query Strategy Success

# 摘要

> 大型语言模型（LLMs）的出现让我们重新审视深度主动学习（AL）的实用性：通过利用冻结的LLM嵌入，我们可以降低大型主干模型迭代微调的计算成本。这项研究建立了一个基准，系统地研究了LLM嵌入质量对深度AL中查询策略的影响。我们从MTEB排行榜中采用了五个表现最佳的模型和两个基线，针对十个多样化的文本分类任务进行了实验。我们的发现揭示了以下关键见解：

1. 使用基于多样性的采样初始化标记池可以与高质量嵌入协同工作，在AL的早期迭代中显著提升性能。
2. 选择最优查询策略对嵌入质量非常敏感。虽然计算成本低廉的Margin采样可以在特定数据集上实现性能峰值，但我们发现像Badge这样的策略在任务间表现出更大的鲁棒性。重要的是，当与更高质量的嵌入配对时，它们的有效性通常会得到增强。

我们的结果强调了对AL策略进行具体情境评估的必要性，因为性能在很大程度上取决于嵌入质量和目标任务。

> The advent of large language models (LLMs) capable of producing general-purpose representations lets us revisit the practicality of deep active learning (AL): By leveraging frozen LLM embeddings, we can mitigate the computational costs of iteratively fine-tuning large backbones. This study establishes a benchmark and systematically investigates the influence of LLM embedding quality on query strategies in deep AL. We employ five top-performing models from the massive text embedding benchmark (MTEB) leaderboard and two baselines for ten diverse text classification tasks. Our findings reveal key insights: First, initializing the labeled pool using diversity-based sampling synergizes with high-quality embeddings, boosting performance in early AL iterations. Second, the choice of the optimal query strategy is sensitive to embedding quality. While the computationally inexpensive Margin sampling can achieve performance spikes on specific datasets, we find that strategies like Badge exhibit greater robustness across tasks. Importantly, their effectiveness is often enhanced when paired with higher-quality embeddings. Our results emphasize the need for context-specific evaluation of AL strategies, as performance heavily depends on embedding quality and the target task.

[Arxiv](https://arxiv.org/abs/2506.01992)