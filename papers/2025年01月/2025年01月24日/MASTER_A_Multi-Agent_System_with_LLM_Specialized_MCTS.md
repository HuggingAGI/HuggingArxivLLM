# MASTER: 基于LLM专用MCTS的多智能体系统

发布时间：2025年01月24日

`Agent

理由：这篇论文主要讨论了如何通过引入蒙特卡洛树搜索（MCTS）算法和多智能体系统（MASTER）来增强大型语言模型（LLM）的规划能力。论文的核心在于通过智能体之间的协调和通信来优化LLM在复杂任务中的表现。因此，这篇论文属于Agent分类，因为它主要关注智能体的设计和应用。` `人工智能` `问答系统`

> MASTER: A Multi-Agent System with LLM Specialized MCTS

# 摘要

> 大型语言模型（LLM）在问题解决任务中的应用日益广泛，但其战略规划能力常受质疑。近期研究引入蒙特卡洛树搜索（MCTS）算法以增强LLM的规划能力。然而，MCTS依赖大量采样模拟来近似真实奖励分布，带来两大问题：其一，MCTS在围棋等任务中表现优异，因为模拟结果可产生客观奖励（如胜利得1分，失败得0分），但在问答任务中，模拟结果仅为问题答案，缺乏真实答案时无法获得客观奖励；其二，获得统计显著的奖励估计通常需超过30次模拟，导致令牌消耗和时间成本过高。为此，我们提出基于LLM专用MCTS的多智能体系统（MASTER），通过LLM专用MCTS协调智能体招募与通信，系统根据任务复杂度自主调整智能体数量并确保其高效沟通。多项任务实验验证了该框架的有效性，在HotpotQA和WebShop数据集上分别达到76%和80%的准确率，创下新纪录。

> Large Language Models (LLM) are increasingly being explored for problem-solving tasks. However, their strategic planning capability is often viewed with skepticism. Recent studies have incorporated the Monte Carlo Tree Search (MCTS) algorithm to augment the planning capacity of LLM. Despite its potential, MCTS relies on extensive sampling simulations to approximate the true reward distribution, leading to two primary issues. Firstly, MCTS is effective for tasks like the Game of Go, where simulation results can yield objective rewards (e.g., 1 for a win and 0 for a loss). However, for tasks such as question answering, the result of a simulation is the answer to the question, which cannot obtain an objective reward without the ground truth. Secondly, obtaining statistically significant reward estimations typically requires a sample size exceeding 30 simulations, resulting in excessive token usage and time consumption. To address these challenges, we present Multi-Agent System with Tactical Execution and Reasoning using LLM Specialized MCTS (MASTER), a novel framework that coordinates agent recruitment and communication using LLM specialized MCTS. This system autonomously adjusts the number of agents based on task complexity and ensures focused communication among them. Comprehensive experiments across various tasks demonstrate the effectiveness of our proposed framework. It achieves 76% accuracy on HotpotQA and 80% on WebShop, setting new state-of-the-art performance on these datasets.

[Arxiv](https://arxiv.org/abs/2501.14304)