# 利用部分SMILES验证方案优化药物设计的强化学习框架

发布时间：2025年05月01日

`LLM应用` `药物发现` `分子生成`

> Leveraging Partial SMILES Validation Scheme for Enhanced Drug Design in Reinforcement Learning Frameworks

# 摘要

> 基于SMILES的分子生成已成为药物发现领域中一种强大的方法。通过结合深度强化学习（RL）和大型语言模型（LLM），研究人员能够生成具有高匹配度的分子候选。然而，强化学习阶段的灾难性遗忘问题仍然严峻：分子有效性等关键知识在预训练阶段通常超过99%，但在后续训练中却大幅下降。现有如REINVENT等算法通过先验模型保留预训练知识，但缺乏稳健的探索机制。为解决这一问题，我们提出了Partial SMILES Validation-PPO（PSV-PPO），一种创新的强化学习算法。与传统方法仅在生成完整序列后验证分子结构不同，PSV-PPO在每个自回归步骤中进行实时的部分SMILES验证，不仅评估当前选择的标记候选，还评估所有潜在的分支路径。这种机制能够提前发现所有可能路径中的无效部分SMILES，从而在探索广阔化学空间的同时保持高有效性。实验结果表明，PSV-PPO显著减少了无效结构的数量，同时保持了强大的探索和优化性能。未来，尽管本研究主要关注分子有效性，但PSV-PPO框架可进一步扩展，整合更多领域的专业知识，从而为药物发现中的强化学习应用带来更大的提升。

> SMILES-based molecule generation has emerged as a powerful approach in drug discovery. Deep reinforcement learning (RL) using large language model (LLM) has been incorporated into the molecule generation process to achieve high matching score in term of likelihood of desired molecule candidates. However, a critical challenge in this approach is catastrophic forgetting during the RL phase, where knowledge such as molecule validity, which often exceeds 99\% during pretraining, significantly deteriorates. Current RL algorithms applied in drug discovery, such as REINVENT, use prior models as anchors to retian pretraining knowledge, but these methods lack robust exploration mechanisms. To address these issues, we propose Partial SMILES Validation-PPO (PSV-PPO), a novel RL algorithm that incorporates real-time partial SMILES validation to prevent catastrophic forgetting while encouraging exploration. Unlike traditional RL approaches that validate molecule structures only after generating entire sequences, PSV-PPO performs stepwise validation at each auto-regressive step, evaluating not only the selected token candidate but also all potential branches stemming from the prior partial sequence. This enables early detection of invalid partial SMILES across all potential paths. As a result, PSV-PPO maintains high validity rates even during aggressive exploration of the vast chemical space. Our experiments on the PMO and GuacaMol benchmark datasets demonstrate that PSV-PPO significantly reduces the number of invalid generated structures while maintaining competitive exploration and optimization performance. While our work primarily focuses on maintaining validity, the framework of PSV-PPO can be extended in future research to incorporate additional forms of valuable domain knowledge, further enhancing reinforcement learning applications in drug discovery.

[Arxiv](https://arxiv.org/abs/2505.00530)