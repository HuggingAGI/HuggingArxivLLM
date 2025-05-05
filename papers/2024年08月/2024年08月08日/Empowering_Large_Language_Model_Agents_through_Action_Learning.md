# 通过行动学习赋能大型语言模型代理

发布时间：2024年08月08日

`Agent` `机器人` `智能代理`

> Empowering Large Language Model Agents through Action Learning

# 摘要

> 大型语言模型（LLM）代理最近吸引了越来越多的关注，但它们在从试错中学习的能力上存在局限，而这正是智能行为的关键。本研究主张，从经验中学习新动作的能力是推进LLM代理学习的核心。虽然人类天生就能通过经验扩展动作空间并发展技能，但LLM代理通常在固定的动作空间内运行，限制了它们的增长潜力。

为了解决这些挑战，我们探索了语言代理的开放动作学习。我们引入了一个名为LearnAct的框架，采用迭代学习策略，以Python函数的形式创建和改进动作。在每次迭代中，LLM会根据未成功训练任务中发现的错误，修订和更新当前可用的动作，从而提高动作的有效性。

我们在机器人规划和Alfworld环境中进行的实验评估表明，经过在少量训练任务实例上的学习后，我们的开放动作学习方法显著提升了代理在特定任务类型上的性能（例如，在AlfWorld中，与ReAct+Reflexion相比，性能提升了32%），突显了经验动作学习在开发更智能的LLM代理中的重要性。

> Large Language Model (LLM) Agents have recently garnered increasing interest yet they are limited in their ability to learn from trial and error, a key element of intelligent behavior. In this work, we argue that the capacity to learn new actions from experience is fundamental to the advancement of learning in LLM agents. While humans naturally expand their action spaces and develop skills through experiential learning, LLM agents typically operate within fixed action spaces, limiting their potential for growth. To address these challenges, our study explores open-action learning for language agents. We introduce a framework LearnAct with an iterative learning strategy to create and improve actions in the form of Python functions. In each iteration, LLM revises and updates the currently available actions based on the errors identified in unsuccessful training tasks, thereby enhancing action effectiveness. Our experimental evaluations across Robotic Planning and Alfworld environments reveal that after learning on a few training task instances, our approach to open-action learning markedly improves agent performance for the type of task (by 32 percent in AlfWorld compared to ReAct+Reflexion, for instance) highlighting the importance of experiential action learning in the development of more intelligent LLM agents.

[Arxiv](https://arxiv.org/abs/2402.15809)