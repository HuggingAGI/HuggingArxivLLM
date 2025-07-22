# # RAD：通过检索高质量的演示样本提升决策能力

发布时间：2025年07月21日

`Agent

解释：这篇论文探讨了离线强化学习中的智能体策略学习，特别是通过结合非参数检索和生成建模来解决数据稀疏性和轨迹拼接问题。它专注于智能体的决策机制和学习策略，属于强化学习和智能体研究的范畴。` `人工智能`

> RAD: Retrieval High-quality Demonstrations to Enhance Decision-making

# 摘要

> 离线强化学习（RL）让智能体能从固定数据集中学习策略，避免了昂贵或不安全的环境交互。然而，数据集稀疏性以及次优轨迹与专家轨迹间缺乏状态转移重叠，使其在长期规划上面临挑战。基于合成数据增强或轨迹拼接的先前方案通常无法推广到新型状态，并依赖启发式拼接点。为解决这些问题，我们提出了用于决策的检索高质量演示（RAD），该方法结合了非参数检索与基于扩散的生成建模。RAD根据状态相似性和回报估计，从离线数据集中动态检索高回报状态作为目标状态，并通过条件引导的扩散模型规划朝向它们。这种检索引导的生成方式使轨迹拼接更加灵活，并在遇到代表性不足或分布外状态时提高了泛化能力。大量实验表明，与基线方法相比，RAD在各种基准测试中均能达到具有竞争力或更优的性能，验证了其有效性。

> Offline reinforcement learning (RL) enables agents to learn policies from fixed datasets, avoiding costly or unsafe environment interactions. However, its effectiveness is often limited by dataset sparsity and the lack of transition overlap between suboptimal and expert trajectories, which makes long-horizon planning particularly challenging. Prior solutions based on synthetic data augmentation or trajectory stitching often fail to generalize to novel states and rely on heuristic stitching points. To address these challenges, we propose Retrieval High-quAlity Demonstrations (RAD) for decision-making, which combines non-parametric retrieval with diffusion-based generative modeling. RAD dynamically retrieves high-return states from the offline dataset as target states based on state similarity and return estimation, and plans toward them using a condition-guided diffusion model. Such retrieval-guided generation enables flexible trajectory stitching and improves generalization when encountered with underrepresented or out-of-distribution states. Extensive experiments confirm that RAD achieves competitive or superior performance compared to baselines across diverse benchmarks, validating its effectiveness.

[Arxiv](https://arxiv.org/abs/2507.15356)