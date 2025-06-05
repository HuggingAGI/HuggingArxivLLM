# GORACS：基于群体级别的最优传输引导的核选择方法，应用于LLM的推荐系统。

发布时间：2025年06月04日

`LLM应用` `推荐系统` `互联网`

> GORACS: Group-level Optimal Transport-guided Coreset Selection for LLM-based Recommender Systems

# 摘要

> 大型语言模型 (LLMs) 在推荐系统中潜力无限，但高昂的计算成本却限制了其实际应用。为打造高效且经济的 LLM 推荐系统，我们聚焦于核心集选择任务，通过优化测试损失，挑选精炼数据子集，从而提升微调效率。现有基于分布和重要性的子集选择方法，常因目标不一致或泛化能力不足而表现不佳。针对这些挑战，我们推出了 GORACS——专为 LLM 推荐系统设计的组级最优传输引导核心集选择框架。GORACS 基于两大原则：1) 选择与微调目标一致的最小化测试损失子集；2) 通过组级数据选择增强模型泛化。其两大核心组件为：1) 代理优化目标 (POO)，借助最优传输和梯度信息界定测试损失，减少计算；2) 初始化然后细化算法 (ITRA)，高效执行组级选择。实验表明，GORACS 在降低微调成本的同时，性能超越现有基线和全数据训练。代码已开源：https://github.com/Mithas-114/GORACS。

> Although large language models (LLMs) have shown great potential in recommender systems, the prohibitive computational costs for fine-tuning LLMs on entire datasets hinder their successful deployment in real-world scenarios. To develop affordable and effective LLM-based recommender systems, we focus on the task of coreset selection which identifies a small subset of fine-tuning data to optimize the test loss, thereby facilitating efficient LLMs' fine-tuning. Although there exist some intuitive solutions of subset selection, including distribution-based and importance-based approaches, they often lead to suboptimal performance due to the misalignment with downstream fine-tuning objectives or weak generalization ability caused by individual-level sample selection. To overcome these challenges, we propose GORACS, which is a novel Group-level Optimal tRAnsport-guided Coreset Selection framework for LLM-based recommender systems. GORACS is designed based on two key principles for coreset selection: 1) selecting the subsets that minimize the test loss to align with fine-tuning objectives, and 2) enhancing model generalization through group-level data selection. Corresponding to these two principles, GORACS has two key components: 1) a Proxy Optimization Objective (POO) leveraging optimal transport and gradient information to bound the intractable test loss, thus reducing computational costs by avoiding repeated LLM retraining, and 2) a two-stage Initialization-Then-Refinement Algorithm (ITRA) for efficient group-level selection. Our extensive experiments across diverse recommendation datasets and tasks validate that GORACS significantly reduces fine-tuning costs of LLMs while achieving superior performance over the state-of-the-art baselines and full data training. The source code of GORACS are available at https://github.com/Mithas-114/GORACS.

[Arxiv](https://arxiv.org/abs/2506.04015)