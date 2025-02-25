# 借助大型语言模型实现多智能体信用分配的有效性和可解释性研究

发布时间：2025年02月24日

`LLM应用` `机器人技术` `人工智能`

> Leveraging Large Language Models for Effective and Explainable Multi-Agent Credit Assignment

# 摘要

> 近年来，从自动驾驶车辆协调到太空组装等研究工作表明，学习协作行为对实现机器人共同目标至关重要。集中式训练、分布式执行的范式是常用的学习协作行为的方法，但这一方法也带来了新的挑战：如何评估每个代理行为对团队成功或失败的贡献。这一信用分配问题至今仍未完全解决，并在多智能体强化学习领域得到了广泛研究。有趣的是，人类通过手动检查代理行为，往往能生成比现有方法更好的信用评估结果。

我们结合这一观察结果与近期研究，发现大型语言模型在许多模式识别任务中表现出了与人类相当的水平。我们的核心思路是将信用分配重新定义为两个模式识别问题：序列改进和归因，从而提出了新颖的LLM-MCA方法。该方法利用一个集中的LLM奖励评判器，根据每个代理在场景中的个性化贡献，对环境奖励进行数值分解，并据此反馈更新代理的策略网络。

我们还提出了扩展方法LLM-TACA，其中LLM评判器通过直接向场景中的每个代理策略传递中间目标，实现显式的任务分配。在基于级别的觅食任务、机器人仓库任务，以及我们引入的新Spaceworld基准测试中，我们的方法均大幅超越现有最佳方法。Spaceworld基准测试集成了与碰撞相关的安全约束，进一步验证了方法的普适性。

作为方法的副产品，我们生成了大型轨迹数据集，每个时间步都标注了每个代理的奖励信息，这些信息采样自我们的LLM评判器。

> Recent work, spanning from autonomous vehicle coordination to in-space assembly, has shown the importance of learning collaborative behavior for enabling robots to achieve shared goals. A common approach for learning this cooperative behavior is to utilize the centralized-training decentralized-execution paradigm. However, this approach also introduces a new challenge: how do we evaluate the contributions of each agent's actions to the overall success or failure of the team. This credit assignment problem has remained open, and has been extensively studied in the Multi-Agent Reinforcement Learning literature. In fact, humans manually inspecting agent behavior often generate better credit evaluations than existing methods. We combine this observation with recent works which show Large Language Models demonstrate human-level performance at many pattern recognition tasks. Our key idea is to reformulate credit assignment to the two pattern recognition problems of sequence improvement and attribution, which motivates our novel LLM-MCA method. Our approach utilizes a centralized LLM reward-critic which numerically decomposes the environment reward based on the individualized contribution of each agent in the scenario. We then update the agents' policy networks based on this feedback. We also propose an extension LLM-TACA where our LLM critic performs explicit task assignment by passing an intermediary goal directly to each agent policy in the scenario. Both our methods far outperform the state-of-the-art on a variety of benchmarks, including Level-Based Foraging, Robotic Warehouse, and our new Spaceworld benchmark which incorporates collision-related safety constraints. As an artifact of our methods, we generate large trajectory datasets with each timestep annotated with per-agent reward information, as sampled from our LLM critics.

[Arxiv](https://arxiv.org/abs/2502.16863)