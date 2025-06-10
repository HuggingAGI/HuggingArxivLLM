# 个体学习，团队进化：多智能体LLMs在具身环境中的适应性研究

发布时间：2025年06月08日

`Agent` `多智能体系统` `具身智能体`

> Learn as Individuals, Evolve as a Team: Multi-agent LLMs Adaptation in Embodied Environments

# 摘要

> 大型语言模型（LLMs）凭借其丰富的知识库和强大的推理能力，在具身环境中展现出复杂多智能体规划的潜力。然而，尽管LLMs能力先进且基于智能体的方法设计精巧，现有基于LLMs的规划算法仍受限于对多智能体具身场景的适应能力不足。为解决这一问题，我们提出了一种框架，使LLM智能体能够在测试前和测试时持续学习与进化，配备环境相关知识以提升规划能力，并通过增强沟通实现更好的合作。受多智能体强化学习中集中式训练与分布式执行的启发，我们提出了	extit{Learn as Individuals, Evolve as a Team (LIET)}范式，用于多智能体LLMs的适应。在个体层面，LLM智能体通过探索性数据集学习一个局部效用函数，从而更好地理解具身环境，并在测试时利用该函数支持有依据的决策。在团队层面，LLM智能体基于新经验共同维护和更新一个共享的合作知识列表，以此指导更有效的沟通。通过将个体学习与团队进化相结合，LIET使LLM智能体实现全面且灵活的适应。我们的实验结果表明，在Communicative Watch-And-Help和ThreeD-World Multi-Agent Transport基准测试中，基于LLaMA和GPT-4实现的LIET不仅超越现有基线，还展现出强大的合作规划能力。

> Large language models (LLMs) possess extensive knowledge bases and strong reasoning capabilities, making them promising tools for complex, multi-agent planning in embodied environments. However, despite LLMs' advanced abilities and the sophisticated modular design of agentic methods, existing LLM-based planning algorithms remain limited by weak adaptation capabilities to multi-agent embodied scenarios. We address this limitation by introducing a framework that enables LLM agents to learn and evolve both before and during test time, equipping them with environment-relevant knowledge for better planning and enhanced communication for improved cooperation. Inspired by centralized training with decentralized execution in multi-agent reinforcement learning, we propose a \textit{Learn as Individuals, Evolve as a Team (LIET)} paradigm for multi-agent LLMs adaptation. At the individual level, LLM agents learn a local utility function from exploratory datasets to better comprehend the embodied environment, which is then queried during test time to support informed decision-making. At the team level, LLM agents collaboratively and iteratively maintain and update a shared cooperation knowledge list based on new experiences, using it to guide more effective communication. By combining individual learning with team evolution, LIET enables comprehensive and flexible adaptation for LLM agents. Our experiments on Communicative Watch-And-Help and ThreeD-World Multi-Agent Transport benchmarks demonstrate that LIET, instantiated with both LLaMA and GPT-4o, outperforms existing baselines and exhibits strong cooperative planning abilities.

[Arxiv](https://arxiv.org/abs/2506.07232)