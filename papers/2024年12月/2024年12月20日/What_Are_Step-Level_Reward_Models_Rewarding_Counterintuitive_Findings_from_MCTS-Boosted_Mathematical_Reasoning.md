# 究竟步骤级奖励模型在奖励什么？来自 MCTS 增强数学推理的令人意想不到的发现

发布时间：2024年12月20日

`LLM应用`

> What Are Step-Level Reward Models Rewarding? Counterintuitive Findings from MCTS-Boosted Mathematical Reasoning

# 摘要

> 步骤级奖励模型（SRMs）能借助基于强化学习的过程监督或步骤级偏好对齐，大幅提升数学推理性能。SRMs 的性能举足轻重，是关键的指引，能保证推理过程的每一步都符合预期结果。近来，类似 AlphaZero 的方法，即采用蒙特卡罗树搜索（MCTS）进行自动步骤级偏好标注的方法，已证实效果显著。然而，SRMs 成功背后的精确机制在很大程度上仍未被探究清楚。为填补这一空缺，本研究深入钻研了 SRMs 有悖常理的方面，尤其聚焦基于 MCTS 的方法。我们的发现表明，去除思维过程的自然语言描述对 SRMs 的效果影响甚微。此外，我们证明 SRMs 善于评估数学语言中的复杂逻辑连贯性，而在自然语言方面则表现不佳。这些见解为数学推理中有效步骤级奖励建模的核心要素提供了细腻的理解。通过揭示这些机制，本研究为开发更高效、更精简的 SRMs 提供了宝贵的指导，可通过关注数学推理的关键部分来达成。

> Step-level reward models (SRMs) can significantly enhance mathematical reasoning performance through process supervision or step-level preference alignment based on reinforcement learning. The performance of SRMs is pivotal, as they serve as critical guidelines, ensuring that each step in the reasoning process is aligned with desired outcomes. Recently, AlphaZero-like methods, where Monte Carlo Tree Search (MCTS) is employed for automatic step-level preference annotation, have proven particularly effective. However, the precise mechanisms behind the success of SRMs remain largely unexplored. To address this gap, this study delves into the counterintuitive aspects of SRMs, particularly focusing on MCTS-based approaches. Our findings reveal that the removal of natural language descriptions of thought processes has minimal impact on the efficacy of SRMs. Furthermore, we demonstrate that SRMs are adept at assessing the complex logical coherence present in mathematical language while having difficulty in natural language. These insights provide a nuanced understanding of the core elements that drive effective step-level reward modeling in mathematical reasoning. By shedding light on these mechanisms, this study offers valuable guidance for developing more efficient and streamlined SRMs, which can be achieved by focusing on the crucial parts of mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2412.15904)