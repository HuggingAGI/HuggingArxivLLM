# 迈向突破推理模型的蒸馏瓶颈

发布时间：2025年03月03日

`LLM应用

理由：这篇论文讨论了如何通过蒸馏和蒙特卡洛树搜索（MCTS）等方法提升小型模型的推理能力，特别是在生成和优化长链式思维（CoT）数据方面。这些方法属于大型语言模型（LLM）的应用研究，旨在通过数据生成和训练策略改进模型性能。` `人工智能` `机器学习`

> Towards Widening The Distillation Bottleneck for Reasoning Models

# 摘要

> 大型推理模型（LRMs）如 OpenAI o1 和 DeepSeek-R1 通过扩展推理时间和生成长链式思维（CoT）展现了令人惊叹的推理能力。蒸馏是一种简单而有效的方法，可以通过在 LRMs 生成的数据上进行后训练来提升小型模型的推理能力。然而，它面临一个关键瓶颈：我们发现，蒸馏生成的长链式 CoT 数据会对小型模型的学习造成困难，并在使用监督微调（SFT）和强化学习（RL）方法时导致偏见（即过度思考）的继承。为了解决这一问题，我们提出通过蒙特卡洛树搜索（MCTS）从头构建树状 CoT 数据。随后，我们采用一组 CoT 感知方法，包括思维长度平衡、细粒度 DPO 和联合后训练目标，来提升在构建数据上进行的 SFT 和 RL。

> Large Reasoning Models(LRMs) such as OpenAI o1 and DeepSeek-R1 have shown remarkable reasoning capabilities by scaling test-time compute and generating long Chain-of-Thought(CoT). Distillation--post-training on LRMs-generated data--is a straightforward yet effective method to enhance the reasoning abilities of smaller models, but faces a critical bottleneck: we found that distilled long CoT data poses learning difficulty for small models and leads to the inheritance of biases (i.e. over-thinking) when using Supervised Fine-tuning(SFT) and Reinforcement Learning(RL) methods. To alleviate this bottleneck, we propose constructing tree-based CoT data from scratch via Monte Carlo Tree Search(MCTS). We then exploit a set of CoT-aware approaches, including Thoughts Length Balance, Fine-grained DPO, and Joint Post-training Objective, to enhance SFT and RL on the construted data.

[Arxiv](https://arxiv.org/abs/2503.01461)