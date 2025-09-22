# 借助离线奖励评估与策略搜索增强生成式自动出价

发布时间：2025年09月19日

`强化学习` `零售与电商`

> Enhancing Generative Auto-bidding with Offline Reward Evaluation and Policy Search

# 摘要

> 自动出价是广告商提升投放效果的核心工具。近期研究显示，AI生成出价（AIGB）将自动出价转化为轨迹生成任务，通过在离线数据上训练条件扩散规划器，其性能优于传统基于离线强化学习（RL）的自动出价方法，且表现更稳定。然而，现有AIGB方法因忽视细粒度生成质量评估，且无法突破静态数据集的局限进行探索，仍存在性能瓶颈。为此，我们提出AIGB-Pearl（\emph{基于RL的评估器规划}）——一种融合生成式规划与策略优化的创新方法。AIGB-Pearl的关键在于构建非自举的\emph{轨迹评估器}，通过分配奖励引导策略搜索，让规划器能通过交互迭代优化生成质量。此外，为提升离线场景下轨迹评估器的精度，我们引入三项关键技术：（i）采用基于大型语言模型（LLM）的架构以增强表征能力；（ii）结合点态与对态混合损失以优化分数学习；（iii）自适应整合专家反馈以提升泛化能力。在模拟和真实广告系统上的大量实验表明，我们的方法达到了当前最先进的性能水平。

> Auto-bidding is an essential tool for advertisers to enhance their advertising performance. Recent progress has shown that AI-Generated Bidding (AIGB), which formulates the auto-bidding as a trajectory generation task and trains a conditional diffusion-based planner on offline data, achieves superior and stable performance compared to typical offline reinforcement learning (RL)-based auto-bidding methods. However, existing AIGB methods still encounter a performance bottleneck due to their neglect of fine-grained generation quality evaluation and inability to explore beyond static datasets. To address this, we propose AIGB-Pearl (\emph{Planning with EvAluator via RL}), a novel method that integrates generative planning and policy optimization. The key to AIGB-Pearl is to construct a non-bootstrapped \emph{trajectory evaluator} to assign rewards and guide policy search, enabling the planner to optimize its generation quality iteratively through interaction. Furthermore, to enhance trajectory evaluator accuracy in offline settings, we incorporate three key techniques: (i) a Large Language Model (LLM)-based architecture for better representational capacity, (ii) hybrid point-wise and pair-wise losses for better score learning, and (iii) adaptive integration of expert feedback for better generalization ability. Extensive experiments on both simulated and real-world advertising systems demonstrate the state-of-the-art performance of our approach.

[Arxiv](https://arxiv.org/abs/2509.15927)