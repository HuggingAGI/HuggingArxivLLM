# L3M+P：利用大型语言模型实现终身规划

发布时间：2025年08月03日

`Agent` `服务机器人` `知识图谱`

> L3M+P: Lifelong Planning with Large Language Models

# 摘要

> 通过结合经典规划方法与大型语言模型（LLMs），如LLM+P等最新研究使智能体能够根据自然语言描述规划通用任务。然而，将这些方法扩展到通用服务机器人仍面临两大挑战：首先，经典规划算法通常需要详细且一致的环境规范，而这并非总是唾手可得；其次，现有框架主要针对孤立的规划任务，而机器人往往需要在长期连续部署中服务，因此必须具备动态维护环境记忆的能力，该记忆可从多模态输入中更新，并为未来任务提取规划知识。

为了解决这些问题，本文提出了一种名为L3M+P（终身LLM+P）的框架，它采用外部知识图来表示世界状态。该知识图可以从多种信息源进行更新，包括传感器输入和与人类的自然语言交互。L3M+P通过设定绝对世界状态图的预期格式规则，确保图更新的一致性。在规划过程中，当接收到任务的自然语言描述时，L3M+P会从知识图中检索相关上下文，并为经典规划器生成问题定义。

在家庭机器人模拟器和真实世界的服务机器人上的评估表明，L3M+P在准确注册自然语言状态变化和正确生成规划方案方面均显著优于现有基线方法。这一优势得益于知识图的高效检索与验证机制。

> By combining classical planning methods with large language models (LLMs), recent research such as LLM+P has enabled agents to plan for general tasks given in natural language. However, scaling these methods to general-purpose service robots remains challenging: (1) classical planning algorithms generally require a detailed and consistent specification of the environment, which is not always readily available; and (2) existing frameworks mainly focus on isolated planning tasks, whereas robots are often meant to serve in long-term continuous deployments, and therefore must maintain a dynamic memory of the environment which can be updated with multi-modal inputs and extracted as planning knowledge for future tasks. To address these two issues, this paper introduces L3M+P (Lifelong LLM+P), a framework that uses an external knowledge graph as a representation of the world state. The graph can be updated from multiple sources of information, including sensory input and natural language interactions with humans. L3M+P enforces rules for the expected format of the absolute world state graph to maintain consistency between graph updates. At planning time, given a natural language description of a task, L3M+P retrieves context from the knowledge graph and generates a problem definition for classical planners. Evaluated on household robot simulators and on a real-world service robot, L3M+P achieves significant improvement over baseline methods both on accurately registering natural language state changes and on correctly generating plans, thanks to the knowledge graph retrieval and verification.

[Arxiv](https://arxiv.org/abs/2508.01917)