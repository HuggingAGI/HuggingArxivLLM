# 通过同伴诱使游戏激励真实可靠的大型语言模型

发布时间：2025年05月19日

`LLM理论` `生成对抗网络`

> Incentivizing Truthful Language Models via Peer Elicitation Games

# 摘要

> 大型语言模型（LLMs）虽然生成能力强大，但仍然容易出现不一致和幻觉问题。我们提出了一种无训练的博弈论框架——Peer Elicitation Games（PEG），通过生成器与多个判别器（由不同基线模型实现）之间的_peer elicitation_机制来对齐LLMs。判别器在一种peer evaluation环境中互动，利用基于行列式的互信息分数计算奖励，无需真实标签即可激励真实报告。理论分析表明，每个代理通过在线学习能够实现次线性遗憾，即其累计性能接近于回顾中最佳固定真实策略的表现。此外，我们证明了最终迭代收敛于真实纳什均衡，确保代理实际采用的策略随时间收敛于稳定且真实的行为。在多个基准上的实证评估显示，事实准确性的显著提升。这些结果将PEG定位为一种无需监督或微调即可从LLMs中提取真实行为的实用方法。
    

> Large Language Models (LLMs) have demonstrated strong generative capabilities but remain prone to inconsistencies and hallucinations. We introduce Peer Elicitation Games (PEG), a training-free, game-theoretic framework for aligning LLMs through a peer elicitation mechanism involving a generator and multiple discriminators instantiated from distinct base models. Discriminators interact in a peer evaluation setting, where rewards are computed using a determinant-based mutual information score that provably incentivizes truthful reporting without requiring ground-truth labels. We establish theoretical guarantees showing that each agent, via online learning, achieves sublinear regret in the sense their cumulative performance approaches that of the best fixed truthful strategy in hindsight. Moreover, we prove last-iterate convergence to a truthful Nash equilibrium, ensuring that the actual policies used by agents converge to stable and truthful behavior over time. Empirical evaluations across multiple benchmarks demonstrate significant improvements in factual accuracy. These results position PEG as a practical approach for eliciting truthful behavior from LLMs without supervision or fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.13636)