# GenPlan：生成式序列模型充当自适应规划器

发布时间：2024年12月11日

`Agent` `行为规划`

> GenPlan: Generative sequence models as adaptive planners

# 摘要

> 离线强化学习借助先前收集的演示进行学习，在行为规划领域成果斐然。但在多任务场景下的决策仍面临严峻挑战。比如，某项任务可能要求智能体探索未知环境、发现目标并抵达，即便这意味着要与沿途的障碍物互动。这类行为规划难题之所以难以解决，原因在于：a）智能体无法超越通过奖励函数所学的单个任务去适应，b）无法推广应用到训练演示未涵盖的新环境，比如演示中所有门都未锁的环境。所以，前沿的决策方法只适用于那些所需任务在训练演示中体现良好且能在短时间规划范围内解决的任务。为应对此问题，我们提出了 GenPlan：一种随机且自适应的规划器，它借助离散流模型进行生成序列建模，实现高效的样本探索与利用。该框架依靠迭代去噪流程来生成一系列目标和动作。此方法捕捉多模态动作分布，有助于目标和任务的发现，从而增强对分布外任务和环境（即不属于训练数据的任务）的泛化能力。我们通过多个模拟环境验证了该方法的有效性。值得一提的是，在自适应规划任务中，GenPlan 比前沿方法的表现高出 10%以上，其中智能体在利用单目标达成任务的演示的同时适应多任务。

> Offline reinforcement learning has shown tremendous success in behavioral planning by learning from previously collected demonstrations. However, decision-making in multitask missions still presents significant challenges. For instance, a mission might require an agent to explore an unknown environment, discover goals, and navigate to them, even if it involves interacting with obstacles along the way. Such behavioral planning problems are difficult to solve due to: a) agents failing to adapt beyond the single task learned through their reward function, and b) the inability to generalize to new environments not covered in the training demonstrations, e.g., environments where all doors were unlocked in the demonstrations. Consequently, state-of-the-art decision making methods are limited to missions where the required tasks are well-represented in the training demonstrations and can be solved within a short (temporal) planning horizon. To address this, we propose GenPlan: a stochastic and adaptive planner that leverages discrete-flow models for generative sequence modeling, enabling sample-efficient exploration and exploitation. This framework relies on an iterative denoising procedure to generate a sequence of goals and actions. This approach captures multi-modal action distributions and facilitates goal and task discovery, thereby enhancing generalization to out-of-distribution tasks and environments, i.e., missions not part of the training data. We demonstrate the effectiveness of our method through multiple simulation environments. Notably, GenPlan outperforms the state-of-the-art methods by over 10% on adaptive planning tasks, where the agent adapts to multi-task missions while leveraging demonstrations on single-goal-reaching tasks.

[Arxiv](https://arxiv.org/abs/2412.08565)