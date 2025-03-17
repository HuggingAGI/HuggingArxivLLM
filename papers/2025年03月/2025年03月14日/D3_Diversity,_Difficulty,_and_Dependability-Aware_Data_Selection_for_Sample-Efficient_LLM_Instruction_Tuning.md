# D3：兼顾多样性、难度和可靠性的数据选择，助力样本高效的 LLM 指令调优

发布时间：2025年03月14日

`LLM应用` `机器学习`

> D3: Diversity, Difficulty, and Dependability-Aware Data Selection for Sample-Efficient LLM Instruction Tuning

# 摘要

> 近期在大型语言模型（LLMs）的指令微调方面取得的进展表明，一个规模小但高质量的数据集能够显著提升LLMs的指令遵循能力，其表现往往超越了那些常因质量问题和冗余问题而负担过重的大规模数据集。然而，如何从大规模数据集中自动识别出具有价值的数据子集以提升指令微调的效果和效率仍是一个挑战。本文中，我们基于数据价值的三个核心维度——多样性、难度和可靠性——制定了数据选择标准，并提出了包含评分和选择两个关键步骤的D3方法。具体而言，在评分阶段，我们定义了多样性函数来衡量样本的独特性，并引入了基于不确定性的预测难度来评估样本难度，同时通过缓解面向上下文生成多样性的干扰来实现这一点。此外，我们还引入了外部LLM进行可靠性评估。在选择阶段，我们制定了D3加权核心集目标，该目标同时优化了数据价值的三个方面，以求解最具价值的子集。D3的两个步骤可以迭代多轮，并通过反馈自适应地调整选择重点。在三个数据集上的实验表明，D3能够利用不到整个数据集10%的数据，显著提升LLMs的指令遵循能力，使其达到具有竞争力甚至更优的水平。

> Recent advancements in instruction tuning for large language models (LLMs) suggest that a small, high-quality dataset can significantly equip LLMs with instruction-following capabilities, outperforming large datasets often burdened by quality and redundancy issues. However, the challenge lies in automatically identifying valuable subsets from large datasets to boost both the effectiveness and efficiency of instruction tuning. In this paper, we first establish data selection criteria based on three distinct aspects of data value: diversity, difficulty, and dependability, and then propose the D3 method comprising two key steps of scoring and selection. Specifically, in the scoring step, we define the diversity function to measure sample distinctiveness and introduce the uncertainty-based prediction difficulty to evaluate sample difficulty by mitigating the interference of context-oriented generation diversity. Additionally, we integrate an external LLM for dependability assessment. In the selection step, we formulate the D3 weighted coreset objective, which jointly optimizes three aspects of data value to solve for the most valuable subset. The two steps of D3 can iterate multiple rounds, incorporating feedback to refine the selection focus adaptively. Experiments on three datasets demonstrate the effectiveness of D3 in endowing LLMs with competitive or even superior instruction-following capabilities using less than 10% of the entire dataset.

[Arxiv](https://arxiv.org/abs/2503.11441)