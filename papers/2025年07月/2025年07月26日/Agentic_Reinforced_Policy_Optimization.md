# 智能体强化策略优化

发布时间：2025年07月26日

`Agent` `计算推理` `知识推理`

> Agentic Reinforced Policy Optimization

# 摘要

> 可验证奖励的大规模强化学习 (RLVR) 在利用大型语言模型 (LLMs) 进行单轮推理任务方面展现了显著效果。在实际推理场景中，LLMs通常能借助外部工具辅助完成任务。然而，现有强化学习算法在平衡模型的长期推理能力和多轮工具交互能力方面表现不足。为解决这一问题，我们提出了基于智能体的强化策略优化（ARPO），这是一种专为训练多轮LLM代理而设计的新型智能体强化学习算法。通过初步实验，我们发现LLMs在与外部工具交互后，通常会表现出高度不确定的行为，表现为生成标记的熵分布增加。基于这一观察，ARPO引入了基于熵的自适应展开机制，动态平衡全局轨迹采样和逐级采样，从而在工具使用后不确定性较高的步骤中促进探索。通过集成优势归属估计，ARPO使LLMs能够内化逐步工具使用交互中的优势差异。我们在计算推理、知识推理和深度搜索领域的13个具有挑战性的基准测试中进行了实验，结果表明ARPO在轨迹级强化学习算法中表现更优。值得注意的是，ARPO仅需现有方法一半的工具使用预算即可实现更好的性能，为使LLM代理与实时动态环境保持一致提供了可扩展的解决方案。我们的代码和数据集已发布在https://github.com/dongguanting/ARPO

> Large-scale reinforcement learning with verifiable rewards (RLVR) has demonstrated its effectiveness in harnessing the potential of large language models (LLMs) for single-turn reasoning tasks. In realistic reasoning scenarios, LLMs can often utilize external tools to assist in task-solving processes. However, current RL algorithms inadequately balance the models' intrinsic long-horizon reasoning capabilities and their proficiency in multi-turn tool interactions. To bridge this gap, we propose Agentic Reinforced Policy Optimization (ARPO), a novel agentic RL algorithm tailored for training multi-turn LLM-based agents. Through preliminary experiments, we observe that LLMs tend to exhibit highly uncertain behavior, characterized by an increase in the entropy distribution of generated tokens, immediately following interactions with external tools. Motivated by this observation, ARPO incorporates an entropy-based adaptive rollout mechanism, dynamically balancing global trajectory sampling and step-level sampling, thereby promoting exploration at steps with high uncertainty after tool usage. By integrating an advantage attribution estimation, ARPO enables LLMs to internalize advantage differences in stepwise tool-use interactions. Our experiments across 13 challenging benchmarks in computational reasoning, knowledge reasoning, and deep search domains demonstrate ARPO's superiority over trajectory-level RL algorithms. Remarkably, ARPO achieves improved performance using only half of the tool-use budget required by existing methods, offering a scalable solution for aligning LLM-based agents with real-time dynamic environments. Our code and datasets are released at https://github.com/dongguanting/ARPO

[Arxiv](https://arxiv.org/abs/2507.19849)