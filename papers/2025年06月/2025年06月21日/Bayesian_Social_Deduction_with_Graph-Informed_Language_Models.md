# 图信息增强语言模型的贝叶斯社会推理

发布时间：2025年06月21日

`Agent` `人工智能` `社交推理`

> Bayesian Social Deduction with Graph-Informed Language Models

# 摘要

> 社会推理——从观察其他智能体的部分行为推断其隐藏的信念与意图——仍是大型语言模型 (LLMs) 面临的一大挑战。我们在社交推理游戏阿瓦隆中评估了现有推理语言模型的局限性，发现尽管最大规模的模型表现出色，但它们需要大量推理过程，并且在压缩为更小、实时可用的变体时性能急剧下降。为了解决这一问题，我们提出了一种混合推理框架，将信念推理外化为一个结构化概率模型，同时利用 LLM 进行语言理解和交互。我们的方法在智能体对战中与更大规模的模型表现相当，并且值得注意的是，这是首个在受控研究中击败人类玩家的语言智能体——实现了 67% 的胜率，并且在定性评分上超过了所有推理基线和人类队友。我们发布了代码、模型和数据集，以支持未来在 LLM 智能体社会推理方面的研究，详情请访问 https://camp-lab-purdue.github.io/bayesian-social-deduction/

> Social reasoning - inferring unobservable beliefs and intentions from partial observations of other agents - remains a challenging task for large language models (LLMs). We evaluate the limits of current reasoning language models in the social deduction game Avalon and find that while the largest models demonstrate strong performance, they require extensive test-time inference and degrade sharply when distilled to smaller, real-time-capable variants. To address this, we introduce a hybrid reasoning framework that externalizes belief inference to a structured probabilistic model, while using an LLM for language understanding and interaction. Our approach achieves competitive performance with much larger models in Agent-Agent play and, notably, is the first language agent to defeat human players in a controlled study - achieving a 67% win rate and receiving higher qualitative ratings than both reasoning baselines and human teammates. We release code, models, and a dataset to support future work on social reasoning in LLM agents, which can be found at https://camp-lab-purdue.github.io/bayesian-social-deduction/

[Arxiv](https://arxiv.org/abs/2506.17788)