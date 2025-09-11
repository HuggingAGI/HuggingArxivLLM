# AgentGym-RL：基于多轮强化学习训练LLM智能体以实现长程决策

发布时间：2025年09月10日

`Agent` `基础理论`

> AgentGym-RL: Training LLM Agents for Long-Horizon Decision Making through Multi-Turn Reinforcement Learning

# 摘要

> 开发自主LLM智能体已成为前沿热点——这类智能体能够通过一系列智能决策解决复杂的现实任务。与人类认知发展类似，它们被期望通过探索环境、与之交互来习得知识与技能。尽管研究不断推进，但学界始终缺少一个统一的交互式强化学习（RL）框架：既能在多样真实环境中从零开始训练智能体，又无需依赖监督微调（SFT）。为此，我们推出了AgentGym-RL——一个基于强化学习训练LLM智能体进行多轮交互决策的全新框架。该框架采用模块化解耦架构，兼具高灵活性与可扩展性，不仅覆盖多种现实场景，还支持主流强化学习算法。此外，我们提出了ScalingInter-RL训练方法，专为平衡探索与利用、实现稳定强化学习优化而设计：训练初期通过限制交互次数侧重“利用”，后期逐步扩展交互视野转向“探索”，以此激发多样化的问题解决策略。这种方式能让智能体形成更丰富的行为模式，在长视野任务中有效避免性能崩溃。大量实验验证了AgentGym-RL框架与ScalingInter-RL方法的稳定性和有效性：我们的智能体在多样环境的27项任务中，性能已达到甚至超越商业模型。我们将分享核心见解，并开源完整的AgentGym-RL框架（含代码与数据集），助力研究社区打造下一代智能体。

> Developing autonomous LLM agents capable of making a series of intelligent decisions to solve complex, real-world tasks is a fast-evolving frontier. Like human cognitive development, agents are expected to acquire knowledge and skills through exploration and interaction with the environment. Despite advances, the community still lacks a unified, interactive reinforcement learning (RL) framework that can effectively train such agents from scratch -- without relying on supervised fine-tuning (SFT) -- across diverse and realistic environments. To bridge this gap, we introduce AgentGym-RL, a new framework to train LLM agents for multi-turn interactive decision-making through RL. The framework features a modular and decoupled architecture, ensuring high flexibility and extensibility. It encompasses a wide variety of real-world scenarios, and supports mainstream RL algorithms. Furthermore, we propose ScalingInter-RL, a training approach designed for exploration-exploitation balance and stable RL optimization. In early stages, it emphasizes exploitation by restricting the number of interactions, and gradually shifts towards exploration with larger horizons to encourage diverse problem-solving strategies. In this way, the agent develops more diverse behaviors and is less prone to collapse under long horizons. We perform extensive experiments to validate the stability and effectiveness of both the AgentGym-RL framework and the ScalingInter-RL approach. Our agents match or surpass commercial models on 27 tasks across diverse environments. We offer key insights and will open-source the complete AgentGym-RL framework -- including code and datasets -- to empower the research community in developing the next generation of intelligent agents.

[Arxiv](https://arxiv.org/abs/2509.08755)