# 基于LLM的去中心化生成式智能体结合自适应分层知识图谱实现协作规划

发布时间：2025年02月08日

`Agent` `多智能体系统` `机器人`

> LLM-Powered Decentralized Generative Agents with Adaptive Hierarchical Knowledge Graph for Cooperative Planning

# 摘要

> 在动态开放世界场景中开发具备长期合作能力的智能体是多智能体系统领域的重要挑战。传统的多智能体强化学习（MARL）框架，如集中式训练分布式执行（CTDE），在扩展性和灵活性方面存在局限。这些方法需要集中式长期规划，而这一过程在缺乏定制奖励函数的情况下难以实现，并且在处理多模态数据时也面临困难。此外，CTDE方法假设合作策略固定不变，这在动态环境中并不适用，因为智能体需要具备适应能力和独立规划的能力。为了解决分散式多智能体合作的难题，我们提出了分散式自适应知识图谱记忆和结构化通信系统（DAMCS），并在新型多智能体Craft环境（Multi-agent Crafter）中进行了实现。我们的生成智能体由大型语言模型（LLMs）驱动，通过利用外部知识和语言进行长期规划和推理，展现出比传统MARL智能体更强的扩展性。DAMCS引入了一种基于分层知识图谱的多模态记忆系统和结构化通信协议，取代了传统方法中完全共享所有过去经验信息的做法，从而优化智能体之间的合作。这使智能体能够从过去的交互中进行推理，并高效地共享相关信息。在新颖的多智能体开放世界任务上的实验表明，DAMCS在任务效率和协作方面显著优于MARL和LLM基线。与单智能体场景相比，双智能体场景以少63%的步骤实现相同目标，而六智能体场景则以少74%的步骤完成任务，充分体现了自适应记忆和结构化通信在实现长期目标中的重要性。我们的项目已公开发布，地址为：https://happyeureka.github.io/damcs。

> Developing intelligent agents for long-term cooperation in dynamic open-world scenarios is a major challenge in multi-agent systems. Traditional Multi-agent Reinforcement Learning (MARL) frameworks like centralized training decentralized execution (CTDE) struggle with scalability and flexibility. They require centralized long-term planning, which is difficult without custom reward functions, and face challenges in processing multi-modal data. CTDE approaches also assume fixed cooperation strategies, making them impractical in dynamic environments where agents need to adapt and plan independently. To address decentralized multi-agent cooperation, we propose Decentralized Adaptive Knowledge Graph Memory and Structured Communication System (DAMCS) in a novel Multi-agent Crafter environment. Our generative agents, powered by Large Language Models (LLMs), are more scalable than traditional MARL agents by leveraging external knowledge and language for long-term planning and reasoning. Instead of fully sharing information from all past experiences, DAMCS introduces a multi-modal memory system organized as a hierarchical knowledge graph and a structured communication protocol to optimize agent cooperation. This allows agents to reason from past interactions and share relevant information efficiently. Experiments on novel multi-agent open-world tasks show that DAMCS outperforms both MARL and LLM baselines in task efficiency and collaboration. Compared to single-agent scenarios, the two-agent scenario achieves the same goal with 63% fewer steps, and the six-agent scenario with 74% fewer steps, highlighting the importance of adaptive memory and structured communication in achieving long-term goals. We publicly release our project at: https://happyeureka.github.io/damcs.

[Arxiv](https://arxiv.org/abs/2502.05453)