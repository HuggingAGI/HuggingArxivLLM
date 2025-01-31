# 大型语言模型思考速度过快，难以有效探索。

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在开放式任务中的探索能力，特别是以Little Alchemy 2为例，研究了LLMs在探索能力上的表现。研究涉及LLMs在特定任务中的应用和表现，属于LLM在实际任务中的应用研究，因此归类为LLM应用。` `人工智能` `认知科学`

> Large Language Models Think Too Fast To Explore Effectively

# 摘要

> 大型语言模型（LLMs）已展现出多种智能能力。尽管已有众多基准测试评估其智能，但对其探索能力的关注却相对较少，而探索能力在自然和人工系统中发现新信息、适应新环境至关重要。LLMs在开放式任务中的探索能力究竟如何，目前尚不明确。本研究以Little Alchemy 2为范例，探究LLMs在开放式任务中是否能在探索能力上超越人类。在该任务中，代理通过组合元素来发现新元素。结果显示，除o1模型外，大多数LLMs的表现不及人类。传统LLMs主要依赖不确定性驱动的策略，而人类则能平衡不确定性与赋权。通过稀疏自编码器对模型进行表示分析发现，不确定性和选择在较早的transformer块中体现，而赋权值则在后期处理，导致LLMs思考过快、决策过早，阻碍了有效探索。这些发现揭示了LLM探索的局限性，并为提升其适应性提供了方向。

> Large Language Models have emerged many intellectual capacities. While numerous benchmarks assess their intelligence, limited attention has been given to their ability to explore, an essential capacity for discovering new information and adapting to novel environments in both natural and artificial systems. The extent to which LLMs can effectively explore, particularly in open-ended tasks, remains unclear. This study investigates whether LLMs can surpass humans in exploration during an open-ended task, using Little Alchemy 2 as a paradigm, where agents combine elements to discover new ones. Results show most LLMs underperform compared to humans, except for the o1 model, with those traditional LLMs relying primarily on uncertainty driven strategies, unlike humans who balance uncertainty and empowerment. Representational analysis of the models with Sparse Autoencoders revealed that uncertainty and choices are represented at earlier transformer blocks, while empowerment values are processed later, causing LLMs to think too fast and make premature decisions, hindering effective exploration. These findings shed light on the limitations of LLM exploration and suggest directions for improving their adaptability.

[Arxiv](https://arxiv.org/abs/2501.18009)