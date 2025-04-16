# Kimina-Prover 预览：探索基于强化学习的大规模形式化推理模型

发布时间：2025年04月15日

`LLM理论

理由：这篇论文主要探讨了大型语言模型在形式定理证明中的应用，特别是通过强化学习训练和独特的推理模式来提高模型的性能。研究不仅展示了模型在特定任务中的应用效果，还深入分析了模型的采样效率、规模与性能的关系，以及推理风格的创新，这些都属于模型理论层面的研究。因此，这篇论文更适合归类到LLM理论。` `数学推理` `形式验证`

> Kimina-Prover Preview: Towards Large Formal Reasoning Models with Reinforcement Learning

# 摘要

> 我们很高兴推出 Kimina-Prover Preview，一个开创形式定理证明新范式的大型语言模型。该模型基于 Qwen2.5-72B 的强化学习流水线训练而成，通过独特的 	extit{形式推理模式}，在 Lean 4 证明生成中展现出强劲性能。这种推理模式使模型能够模拟人类在 Lean 中的问题解决策略，迭代生成并优化证明步骤。Kimina-Prover 在 miniF2F 基准测试中树立了新的标杆，以 pass@8192 达到 80.7% 的成绩。

除了在基准测试中的卓越表现，我们的研究还带来了几个重要发现：首先，Kimina-Prover 具备高采样效率，即使在最小采样（pass@1）下也能取得优异结果，并能有效扩展计算预算，这得益于其独特的推理模式和强化学习训练；其次，我们展示了模型规模与性能的明确关联，这一趋势在神经定理证明器的形式数学领域中此前未曾被观察到；最后，所学习的推理风格与传统搜索算法截然不同，展现出连接形式验证与非正式数学直觉的潜力。我们开源了 Kimina-Prover 的精简版本，参数量分别为 1.5B 和 7B。


> We introduce Kimina-Prover Preview, a large language model that pioneers a novel reasoning-driven exploration paradigm for formal theorem proving, as showcased in this preview release. Trained with a large-scale reinforcement learning pipeline from Qwen2.5-72B, Kimina-Prover demonstrates strong performance in Lean 4 proof generation by employing a structured reasoning pattern we term \textit{formal reasoning pattern}. This approach allows the model to emulate human problem-solving strategies in Lean, iteratively generating and refining proof steps. Kimina-Prover sets a new state-of-the-art on the miniF2F benchmark, reaching 80.7% with pass@8192. Beyond improved benchmark performance, our work yields several key insights: (1) Kimina-Prover exhibits high sample efficiency, delivering strong results even with minimal sampling (pass@1) and scaling effectively with computational budget, stemming from its unique reasoning pattern and RL training; (2) we demonstrate clear performance scaling with model size, a trend previously unobserved for neural theorem provers in formal mathematics; (3) the learned reasoning style, distinct from traditional search algorithms, shows potential to bridge the gap between formal verification and informal mathematical intuition. We open source distilled versions with 1.5B and 7B parameters of Kimina-Prover

[Arxiv](https://arxiv.org/abs/2504.11354)