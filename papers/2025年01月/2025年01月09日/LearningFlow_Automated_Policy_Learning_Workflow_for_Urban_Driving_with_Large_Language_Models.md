# LearningFlow: 利用大型语言模型实现城市驾驶策略的自动化学习工作流

发布时间：2025年01月09日

`Agent

理由：这篇论文主要介绍了一个名为LearningFlow的自动化策略学习框架，该框架通过多个大型语言模型（LLM）代理的协作来实现强化学习（RL）训练过程中的自动化和优化。论文的核心在于LLM代理的协作机制，这些代理负责生成训练课程和奖励函数，并评估训练进度。因此，这篇论文的重点在于LLM代理的应用和协作，属于Agent分类。` `自动驾驶`

> LearningFlow: Automated Policy Learning Workflow for Urban Driving with Large Language Models

# 摘要

> # 摘要
强化学习（RL）的最新进展揭示了其在自动驾驶领域的巨大潜力。然而，奖励函数的手动设计和复杂环境中的低样本效率等问题，依然制约着安全有效驾驶策略的发展。为此，我们推出了LearningFlow，一个专为城市驾驶打造的创新自动化策略学习框架。该框架通过多个大型语言模型（LLM）代理的协作，在RL训练过程中发挥作用。LearningFlow包含课程序列生成和奖励生成两大核心流程，它们协同工作，通过定制训练课程和奖励函数来引导RL策略。每个流程均由分析代理支持，负责评估训练进度并为生成代理提供关键见解。通过这些LLM代理的紧密合作，LearningFlow在一系列复杂驾驶任务中实现了策略学习的自动化，显著降低了对手动奖励函数设计的依赖，同时提升了样本效率。我们在高保真CARLA模拟器中进行了全面实验，并与现有方法进行了对比，验证了所提方法的有效性。实验结果表明，LearningFlow在奖励和课程生成方面表现优异，并在多种驾驶任务中展现出卓越的性能和强大的泛化能力，同时能够很好地适应不同的RL算法。

> Recent advancements in reinforcement learning (RL) demonstrate the significant potential in autonomous driving. Despite this promise, challenges such as the manual design of reward functions and low sample efficiency in complex environments continue to impede the development of safe and effective driving policies. To tackle these issues, we introduce LearningFlow, an innovative automated policy learning workflow tailored to urban driving. This framework leverages the collaboration of multiple large language model (LLM) agents throughout the RL training process. LearningFlow includes a curriculum sequence generation process and a reward generation process, which work in tandem to guide the RL policy by generating tailored training curricula and reward functions. Particularly, each process is supported by an analysis agent that evaluates training progress and provides critical insights to the generation agent. Through the collaborative efforts of these LLM agents, LearningFlow automates policy learning across a series of complex driving tasks, and it significantly reduces the reliance on manual reward function design while enhancing sample efficiency. Comprehensive experiments are conducted in the high-fidelity CARLA simulator, along with comparisons with other existing methods, to demonstrate the efficacy of our proposed approach. The results demonstrate that LearningFlow excels in generating rewards and curricula. It also achieves superior performance and robust generalization across various driving tasks, as well as commendable adaptation to different RL algorithms.

[Arxiv](https://arxiv.org/abs/2501.05057)