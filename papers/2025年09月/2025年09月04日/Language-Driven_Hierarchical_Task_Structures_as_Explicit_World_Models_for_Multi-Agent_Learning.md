# 语言驱动的层级任务结构：多智能体学习的显式世界模型

发布时间：2025年09月04日

`Agent` `工业与制造`

> Language-Driven Hierarchical Task Structures as Explicit World Models for Multi-Agent Learning

# 摘要

> 语言模型、智能体模型与世界模型的融合，是人工智能领域的关键前沿方向。尽管近期研究主要聚焦于扩展语言模型和智能体模型的规模，但复杂显式世界模型的开发仍是突出瓶颈，尤其在复杂长期多智能体任务中表现明显。以机器人足球为例，在高保真但结构扁平的模拟器中，采用标准强化学习训练的智能体常因探索空间复杂难控且奖励信号稀疏而失败。本立场论文提出，开发高性能智能体的下一个前沿，在于构建具备显式分层世界模型的环境。我们认为，这一目标通过“分层支架”能得到最佳实现——即将复杂目标分解为结构化、易处理的子目标。通过系统梳理2024年多智能体足球领域的研究，我们发现一个明确趋势：符号化与分层方法正与多智能体强化学习（MARL）深度融合，这些方法或隐或显地构建任务导向的世界模型，以指导智能体学习。据此，我们进一步提出范式转变：利用大型语言模型动态生成这种分层支架，借助语言实时构建世界模型结构。这种语言驱动的世界模型，能提供内在学习课程、密集且有意义的学习信号，以及组合式学习框架，从而有效连接低级反应行为与高级战略团队协作，为训练下一代智能体奠定强大且通用的基础。

> The convergence of Language models, Agent models, and World models represents a critical frontier for artificial intelligence. While recent progress has focused on scaling Language and Agent models, the development of sophisticated, explicit World Models remains a key bottleneck, particularly for complex, long-horizon multi-agent tasks. In domains such as robotic soccer, agents trained via standard reinforcement learning in high-fidelity but structurally-flat simulators often fail due to intractable exploration spaces and sparse rewards. This position paper argues that the next frontier in developing capable agents lies in creating environments that possess an explicit, hierarchical World Model. We contend that this is best achieved through hierarchical scaffolding, where complex goals are decomposed into structured, manageable subgoals. Drawing evidence from a systematic review of 2024 research in multi-agent soccer, we identify a clear and decisive trend towards integrating symbolic and hierarchical methods with multi-agent reinforcement learning (MARL). These approaches implicitly or explicitly construct a task-based world model to guide agent learning. We then propose a paradigm shift: leveraging Large Language Models to dynamically generate this hierarchical scaffold, effectively using language to structure the World Model on the fly. This language-driven world model provides an intrinsic curriculum, dense and meaningful learning signals, and a framework for compositional learning, enabling Agent Models to acquire sophisticated, strategic behaviors with far greater sample efficiency. By building environments with explicit, language-configurable task layers, we can bridge the gap between low-level reactive behaviors and high-level strategic team play, creating a powerful and generalizable framework for training the next generation of intelligent agents.

[Arxiv](https://arxiv.org/abs/2509.04731)