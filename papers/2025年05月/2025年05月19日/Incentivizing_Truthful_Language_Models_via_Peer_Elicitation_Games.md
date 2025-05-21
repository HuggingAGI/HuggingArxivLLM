# # 激励诚实语言模型的同侪激励游戏

通过同侪激励游戏激励诚实的语言模型

发布时间：2025年05月19日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的对齐方法，提出了一种基于博弈论的框架（PEG），通过生成器与判别器的互动来提升模型的准确性和一致性。研究涉及理论分析和收敛证明，属于LLM理论范畴。` `信息检索` `问答系统`

> Incentivizing Truthful Language Models via Peer Elicitation Games

# 摘要

> 大型语言模型（LLMs）虽生成能力强大，但常出现不一致和幻觉问题。我们提出了一种无训练、基于博弈论的同侪征询游戏（PEG）框架，通过生成器与多个判别器的互动对齐LLMs。判别器在同侪评估环境中协作，采用行列式互信息分数计算奖励，无需真实标签即可激励真实报告。理论分析表明，每个代理通过在线学习实现次线性遗憾，即其累计性能接近最优固定真实策略。此外，我们证明了迭代收敛到真实的纳什均衡，确保代理策略随时间趋于稳定和真实。实证结果显示，PEG在多个基准上显著提升了事实准确性。这些结果表明，PEG是一种无需监督或微调即可从LLMs中提取真实行为的有效方法。

> Large Language Models (LLMs) have demonstrated strong generative capabilities but remain prone to inconsistencies and hallucinations. We introduce Peer Elicitation Games (PEG), a training-free, game-theoretic framework for aligning LLMs through a peer elicitation mechanism involving a generator and multiple discriminators instantiated from distinct base models. Discriminators interact in a peer evaluation setting, where rewards are computed using a determinant-based mutual information score that provably incentivizes truthful reporting without requiring ground-truth labels. We establish theoretical guarantees showing that each agent, via online learning, achieves sublinear regret in the sense their cumulative performance approaches that of the best fixed truthful strategy in hindsight. Moreover, we prove last-iterate convergence to a truthful Nash equilibrium, ensuring that the actual policies used by agents converge to stable and truthful behavior over time. Empirical evaluations across multiple benchmarks demonstrate significant improvements in factual accuracy. These results position PEG as a practical approach for eliciting truthful behavior from LLMs without supervision or fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.13636)