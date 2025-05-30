# 分段策略优化：在大型语言模型的强化学习中实现有效的分段级奖励分配机制

发布时间：2025年05月29日

`LLM理论

理由：这篇论文探讨了强化学习在提升大型语言模型推理能力中的应用，提出了一种新的分段策略优化框架，并分析了其理论基础和优势。研究集中在模型优化方法上，属于理论层面。` `人工智能`

> Segment Policy Optimization: Effective Segment-Level Credit Assignment in RL for Large Language Models

# 摘要

> 提升大型语言模型的推理能力一直是强化学习 (RL) 领域的重要挑战。现有方法主要采用两种截然不同的优势估计粒度：基于标记的方法（例如 PPO）试图提供精细的优势信号，但由于难以训练准确的批评模型，导致估计不准确。而基于轨迹的方法（例如 GRPO）仅依赖于最终奖励提供的粗粒度优势信号，导致信用分配不够精确。为了解决这些问题，我们提出了一种新型的 RL 框架——分段策略优化 (SPO)，该框架采用中间粒度的分段优势估计，通过提供比基于轨迹的方法更精确的信用分配，并且比基于标记的方法需要更少的估计点，从而实现了更好的平衡。SPO 利用蒙特卡罗 (MC) 估计实现准确的优势估计，而无需批评模型。SPO 包含三个具有创新策略的组件：(1) 灵活的分段划分；(2) 准确的分段优势估计；(3) 基于分段优势的策略优化，包括一种新型的概率掩码策略。我们进一步将 SPO 应用于两个特定场景：(1) SPO 链，适用于短链式推理 (CoT)，采用基于切分点的划分和链式优势估计，与 PPO 和 GRPO 相比，在 GSM8K 上的准确率提升了 6-12 个百分点。 (2) SPO 树，适用于长链式推理，采用基于树的优势估计，显著降低了 MC 估计的成本，在 MATH500 上的准确率提升了 7-11 个百分点，适用于 2K 和 4K 上下文评估。我们的代码已公开发布在 https://github.com/AIFrameResearch/SPO。


> Enhancing the reasoning capabilities of large language models effectively using reinforcement learning (RL) remains a crucial challenge. Existing approaches primarily adopt two contrasting advantage estimation granularities: Token-level methods (e.g., PPO) aim to provide the fine-grained advantage signals but suffer from inaccurate estimation due to difficulties in training an accurate critic model. On the other extreme, trajectory-level methods (e.g., GRPO) solely rely on a coarse-grained advantage signal from the final reward, leading to imprecise credit assignment. To address these limitations, we propose Segment Policy Optimization (SPO), a novel RL framework that leverages segment-level advantage estimation at an intermediate granularity, achieving a better balance by offering more precise credit assignment than trajectory-level methods and requiring fewer estimation points than token-level methods, enabling accurate advantage estimation based on Monte Carlo (MC) without a critic model. SPO features three components with novel strategies: (1) flexible segment partition; (2) accurate segment advantage estimation; and (3) policy optimization using segment advantages, including a novel probability-mask strategy. We further instantiate SPO for two specific scenarios: (1) SPO-chain for short chain-of-thought (CoT), featuring novel cutpoint-based partition and chain-based advantage estimation, achieving $6$-$12$ percentage point improvements in accuracy over PPO and GRPO on GSM8K. (2) SPO-tree for long CoT, featuring novel tree-based advantage estimation, which significantly reduces the cost of MC estimation, achieving $7$-$11$ percentage point improvements over GRPO on MATH500 under 2K and 4K context evaluation. We make our code publicly available at https://github.com/AIFrameResearch/SPO.

[Arxiv](https://arxiv.org/abs/2505.23564)