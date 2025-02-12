# # Training Language Models for Social Deduction with Multi-Agent Reinforcement Learning
通过多智能体强化学习训练用于社交推理的语言模型。

发布时间：2025年02月09日

`Agent` `多智能体系统` `社交推理`

> Training Language Models for Social Deduction with Multi-Agent Reinforcement Learning

# 摘要

> 在多智能体环境中，自然语言交流是强大的工具，它让独立智能体在部分可观察的环境中共享信息，并实现与人类的零样本协调。然而，现有方法大多存在局限性：要么依赖大量人类演示进行训练，要么无法生成自然且有效的沟通策略。在本研究中，我们训练语言模型无需任何人类演示，就能用自然语言进行富有成效的环境讨论。我们将沟通问题分解为倾听和说话两大核心能力。

我们的关键创新在于：通过智能体目标预测关于世界的有用信息，将其作为密集奖励信号来指导沟通。具体而言，我们通过训练模型根据讨论内容预测环境信息，来提升其倾听技能；同时，我们利用多智能体强化学习，根据消息对其他智能体的影响给予奖励，从而提升其说话技能。

为了研究复杂社交环境中沟通的作用和必要性，我们设计了一个基于《Among Us》的具身社交推理游戏，核心问题是识别一个对抗性的冒充者。通过分析我们的技术所引发的行为，如指控嫌疑人和提供证据，我们发现它能够实现强有力的讨论，与标准强化学习相比，胜率翻倍。我们的代码和模型已开源，详情请访问 https://socialdeductionllm.github.io/

> Communicating in natural language is a powerful tool in multi-agent settings, as it enables independent agents to share information in partially observable settings and allows zero-shot coordination with humans. However, most prior works are limited as they either rely on training with large amounts of human demonstrations or lack the ability to generate natural and useful communication strategies. In this work, we train language models to have productive discussions about their environment in natural language without any human demonstrations. We decompose the communication problem into listening and speaking. Our key idea is to leverage the agent's goal to predict useful information about the world as a dense reward signal that guides communication. Specifically, we improve a model's listening skills by training them to predict information about the environment based on discussions, and we simultaneously improve a model's speaking skills with multi-agent reinforcement learning by rewarding messages based on their influence on other agents. To investigate the role and necessity of communication in complex social settings, we study an embodied social deduction game based on Among Us, where the key question to answer is the identity of an adversarial imposter. We analyze emergent behaviors due to our technique, such as accusing suspects and providing evidence, and find that it enables strong discussions, doubling the win rates compared to standard RL. We release our code and models at https://socialdeductionllm.github.io/

[Arxiv](https://arxiv.org/abs/2502.06060)