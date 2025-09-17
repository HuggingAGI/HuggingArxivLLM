# ActiveVLN：基于多轮强化学习（RL）的视觉-语言导航主动探索研究

发布时间：2025年09月15日

`强化学习` `交通运输`

> ActiveVLN: Towards Active Exploration via Multi-Turn RL in Vision-and-Language Navigation

# 摘要

> 视觉-语言导航（VLN）任务要求智能体依据自然语言指令在复杂环境中完成导航。现有的基于多模态大语言模型（MLLM）的VLN方法主要依赖模仿学习（IL），且常通过DAgger后训练来缓解协变量偏移问题。这类方法虽有成效，但数据收集与训练成本高昂。强化学习（RL）为此提供了颇具潜力的替代方案，然而以往的VLN强化学习方法缺乏与环境的动态交互，且依赖专家轨迹进行奖励塑造，而非开展开放式主动探索，这限制了智能体发现多样化合理导航路线的能力。

为解决这些局限，我们提出ActiveVLN——一个通过多轮强化学习实现主动探索的VLN框架。第一阶段，利用少量专家轨迹通过模仿学习引导智能体初始化；第二阶段，智能体通过迭代预测与执行动作，自动收集多样化轨迹，并借助GRPO目标优化多轨迹采样。为进一步提升强化学习效率，我们引入动态早停策略剪枝长尾或可能失败的轨迹，同时辅以其他工程优化手段。

实验结果显示，相较于基于DAgger和以往强化学习的后训练方法，ActiveVLN在IL基线上的性能提升最为显著；同时，尽管采用了更小的模型，其性能仍可与最先进方法相媲美。相关代码和数据即将发布。

> The Vision-and-Language Navigation (VLN) task requires an agent to follow natural language instructions and navigate through complex environments. Existing MLLM-based VLN methods primarily rely on imitation learning (IL) and often use DAgger for post-training to mitigate covariate shift. While effective, these approaches incur substantial data collection and training costs. Reinforcement learning (RL) offers a promising alternative. However, prior VLN RL methods lack dynamic interaction with the environment and depend on expert trajectories for reward shaping, rather than engaging in open-ended active exploration. This restricts the agent's ability to discover diverse and plausible navigation routes. To address these limitations, we propose ActiveVLN, a VLN framework that explicitly enables active exploration through multi-turn RL. In the first stage, a small fraction of expert trajectories is used for IL to bootstrap the agent. In the second stage, the agent iteratively predicts and executes actions, automatically collects diverse trajectories, and optimizes multiple rollouts via the GRPO objective. To further improve RL efficiency, we introduce a dynamic early-stopping strategy to prune long-tail or likely failed trajectories, along with additional engineering optimizations. Experiments show that ActiveVLN achieves the largest performance gains over IL baselines compared to both DAgger-based and prior RL-based post-training methods, while reaching competitive performance with state-of-the-art approaches despite using a smaller model. Code and data will be released soon.

[Arxiv](https://arxiv.org/abs/2509.12618)