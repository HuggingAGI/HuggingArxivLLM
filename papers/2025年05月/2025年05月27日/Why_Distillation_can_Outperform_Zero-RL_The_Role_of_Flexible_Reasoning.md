# 蒸馏为何超越零样本RL：灵活推理的关键作用

发布时间：2025年05月27日

`LLM应用` `人工智能` `机器学习`

> Why Distillation can Outperform Zero-RL: The Role of Flexible Reasoning

# 摘要

> 强化学习（RL）在提升大型语言模型（LLMs）推理能力方面发挥着重要作用。尽管一些研究通过直接将RL应用于较小规模的基础模型（即零RL）取得了显著成果，但我们在本文中发现，仅使用920个示例，一种基于基础模型的简单蒸馏方法就能显著超越零RL的表现，而零RL通常需要大量数据和计算成本。通过对模型输出中代词频率的分析，我们发现蒸馏模型展现出更灵活的推理能力，其代词和逻辑连接词的使用频率远高于零RL模型。进一步研究表明，蒸馏方法增强了两种高级认知行为：多角度思考或尝试以及元认知意识。这两种行为的频繁出现是实现灵活推理的关键，而零RL方法未能显著提升这些行为的频率。灵活推理能力对于解决复杂推理问题至关重要。

> Reinforcement learning (RL) has played an important role in improving the reasoning ability of large language models (LLMs). Some studies apply RL directly to \textit{smaller} base models (known as zero-RL) and also achieve notable progress. However, in this paper, we show that using only 920 examples, a simple distillation method based on the base model can clearly outperform zero-RL, which typically requires much more data and computational cost. By analyzing the token frequency in model outputs, we find that the distilled model shows more flexible reasoning. It uses anthropomorphic tokens and logical connectors much more often than the zero-RL model. Further analysis reveals that distillation enhances the presence of two advanced cognitive behaviors: Multi-Perspective Thinking or Attempting and Metacognitive Awareness. Frequent occurrences of these two advanced cognitive behaviors give rise to flexible reasoning, which is essential for solving complex reasoning problems, while zero-RL fails to significantly boost the frequency of these behaviors.

[Arxiv](https://arxiv.org/abs/2505.21067)