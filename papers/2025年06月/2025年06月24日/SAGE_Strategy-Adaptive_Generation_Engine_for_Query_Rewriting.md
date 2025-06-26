# SAGE：策略自适应生成引擎，用于查询改写

发布时间：2025年06月24日

`LLM应用` `信息检索` `查询优化`

> SAGE: Strategy-Adaptive Generation Engine for Query Rewriting

# 摘要

> 查询重写是提升密集检索效果的关键，但现有方法要么依赖大规模监督数据，要么在强化学习（RL）探索中效率低下。在本研究中，我们发现通过使用专家设计的策略（如语义扩展和实体消歧）来引导大型语言模型（LLMs），可以在HotpotQA、FEVER、NFCorpus和SciFact等具有挑战性的基准测试中显著提升检索效果。基于这一发现，我们提出了策略自适应生成引擎（SAGE），在强化学习框架中实现了这些策略。SAGE引入了两种创新的奖励成形机制——策略信用成形（SCS）和对比奖励成形（CRS），以提供更丰富的学习信号。这种基于策略的方法不仅在NDCG@10指标上达到了新的最先进水平，还展现出一种引人注目的行为：智能体学会了选择最优策略，减少了不必要的探索，生成了简洁的重写，从而在不降低性能的情况下降低了推理成本。我们的研究结果表明，结合精细奖励成形的基于策略强化学习，为开发下一代稳健信息检索系统提供了一种可扩展、高效且更易解释的范式。

> Query rewriting is pivotal for enhancing dense retrieval, yet current methods demand large-scale supervised data or suffer from inefficient reinforcement learning (RL) exploration. In this work, we first establish that guiding Large Language Models (LLMs) with a concise set of expert-crafted strategies, such as semantic expansion and entity disambiguation, substantially improves retrieval effectiveness on challenging benchmarks, including HotpotQA, FEVER, NFCorpus, and SciFact. Building on this insight, we introduce the Strategy-Adaptive Generation Engine (SAGE), which operationalizes these strategies in an RL framework. SAGE introduces two novel reward shaping mechanisms-Strategic Credit Shaping (SCS) and Contrastive Reward Shaping (CRS)-to deliver more informative learning signals. This strategy-guided approach not only achieves new state-of-the-art NDCG@10 results, but also uncovers a compelling emergent behavior: the agent learns to select optimal strategies, reduces unnecessary exploration, and generates concise rewrites, lowering inference cost without sacrificing performance. Our findings demonstrate that strategy-guided RL, enhanced with nuanced reward shaping, offers a scalable, efficient, and more interpretable paradigm for developing the next generation of robust information retrieval systems.

[Arxiv](https://arxiv.org/abs/2506.19783)