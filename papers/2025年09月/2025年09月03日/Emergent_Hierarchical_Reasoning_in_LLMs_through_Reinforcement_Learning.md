# 通过强化学习，大型语言模型中涌现层级推理

发布时间：2025年09月03日

`强化学习` `基础理论`

> Emergent Hierarchical Reasoning in LLMs through Reinforcement Learning

# 摘要

> 强化学习（RL）在提升大型语言模型（LLMs）的复杂推理能力方面成效显著，但其成功背后的深层机制仍大多成谜。我们的分析揭示，“顿悟时刻”“长度缩放”和熵动态等看似费解的现象并非孤立存在，而是涌现推理层级的典型特征，这类似于人类认知中高层战略规划与低层流程执行的分离。我们发现了一个清晰的两阶段动态规律：起初，模型受限于流程正确性，需着力提升底层技能；随后，学习瓶颈发生决定性转移，性能提升转而由高层战略规划的探索与掌握推动。这一洞见暴露出当前主流强化学习算法（如GRPO）的核心缺陷：它们无差别地施加优化压力，导致学习信号在所有token上被稀释。为此，我们提出层级感知信用分配（HICRA）算法，它能将优化重点集中在高影响力的规划token上。HICRA显著优于现有强基线模型，证明聚焦这一战略瓶颈正是解锁高级推理能力的关键。此外，我们证实语义熵是衡量战略探索的更佳指标，远优于token级熵等易误导的度量标准。

> Reinforcement Learning (RL) has proven highly effective at enhancing the complex reasoning abilities of Large Language Models (LLMs), yet underlying mechanisms driving this success remain largely opaque. Our analysis reveals that puzzling phenomena like ``aha moments", ``length-scaling'' and entropy dynamics are not disparate occurrences but hallmarks of an emergent reasoning hierarchy, akin to the separation of high-level strategic planning from low-level procedural execution in human cognition. We uncover a compelling two-phase dynamic: initially, a model is constrained by procedural correctness and must improve its low-level skills. The learning bottleneck then decisively shifts, with performance gains being driven by the exploration and mastery of high-level strategic planning. This insight exposes a core inefficiency in prevailing RL algorithms like GRPO, which apply optimization pressure agnostically and dilute the learning signal across all tokens. To address this, we propose HIerarchy-Aware Credit Assignment (HICRA), an algorithm that concentrates optimization efforts on high-impact planning tokens. HICRA significantly outperforms strong baselines, demonstrating that focusing on this strategic bottleneck is key to unlocking advanced reasoning. Furthermore, we validate semantic entropy as a superior compass for measuring strategic exploration over misleading metrics such as token-level entropy.

[Arxiv](https://arxiv.org/abs/2509.03646)