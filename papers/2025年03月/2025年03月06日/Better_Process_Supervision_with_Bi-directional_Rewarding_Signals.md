# 双向奖励机制助力更优流程管理

发布时间：2025年03月06日

`LLM应用` `数学推理`

> Better Process Supervision with Bi-directional Rewarding Signals

# 摘要

> 过程监督，即对每一步进行评估，对于复杂大型语言模型（LLM）推理和测试时的搜索至关重要，尤其是在增加推理计算的情况下。现有方法，以过程奖励模型（PRMs）为代表，主要关注到当前步骤的奖励信号，表现出单向性，缺乏建模到最终目标距离的机制。为了解决这个问题，我们从A*算法中获得启发，该算法指出，有效的监督信号应同时考虑已发生成本和达到目标的估计成本。基于这一关键见解，我们引入了BiRM，这是一种新型的过程监督模型，不仅评估之前步骤的正确性，还建模未来成功概率。我们在数学推理任务上进行了广泛实验，证明BiRM对LLM推理步骤提供了更精确的评估，在Best-of-N采样方法下，与PRM相比，在Gaokao2023上提高了3.1%。此外，在基于搜索的策略中，BiRM提供了更全面的指导，在MATH-500上分别比ORM高出5.0%和比PRM高出3.8%。

> Process supervision, i.e., evaluating each step, is critical for complex large language model (LLM) reasoning and test-time searching with increased inference compute. Existing approaches, represented by process reward models (PRMs), primarily focus on rewarding signals up to the current step, exhibiting a one-directional nature and lacking a mechanism to model the distance to the final target. To address this problem, we draw inspiration from the A* algorithm, which states that an effective supervisory signal should simultaneously consider the incurred cost and the estimated cost for reaching the target. Building on this key insight, we introduce BiRM, a novel process supervision model that not only evaluates the correctness of previous steps but also models the probability of future success. We conduct extensive experiments on mathematical reasoning tasks and demonstrate that BiRM provides more precise evaluations of LLM reasoning steps, achieving an improvement of 3.1% on Gaokao2023 over PRM under the Best-of-N sampling method. Besides, in search-based strategies, BiRM provides more comprehensive guidance and outperforms ORM by 5.0% and PRM by 3.8% respectively on MATH-500.

[Arxiv](https://arxiv.org/abs/2503.04618)