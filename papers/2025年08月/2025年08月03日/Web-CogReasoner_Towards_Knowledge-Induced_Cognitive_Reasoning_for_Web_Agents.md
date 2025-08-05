# Web-CogReasoner：致力于知识驱动的认知推理，用于网络智能体

发布时间：2025年08月03日

`Agent` `互联网` `人工智能`

> Web-CogReasoner: Towards Knowledge-Induced Cognitive Reasoning for Web Agents

# 摘要

> 多模态大规模模型推动了Web代理的发展，使它们能够像人类认知一样感知和与数字环境交互。本文认为，Web代理要有效参与认知推理，必须首先获取足够的知识。因此，我们将Web代理的能力分解为知识内容学习和认知过程两个关键阶段。为了形式化这一过程，我们提出了Web-CogKnowledge框架，将知识分为事实性、概念性和程序性三类。其中，知识内容学习对应于代理的 Memorizing（记忆）和 Understanding（理解）过程，依赖前两种知识类型，代表学习的“内容”；而认知过程对应于 Exploring（探索），基于程序性知识，定义推理和行动的“方法”。为了促进知识获取，我们构建了Web-CogDataset，这是一个从14个真实网站整理的结构化资源，旨在系统地传授Web代理所需的核心知识。该数据集作为代理的概念基础——理解构建的“名词”——以及学习如何推理和行动的基础。在此基础上，我们通过知识驱动的链式推理（Chain-of-Thought, CoT）框架，开发并训练了我们的Web-CogReasoner代理。大量实验表明，它显著优于现有模型，尤其是在需要结构化知识决定的未见任务上。为了进行严格的评估，我们引入了Web-CogBench，这是一个全面的评估套件，旨在评估和比较代理在划定的知识领域和认知能力方面的性能。我们的代码和数据已开源，地址为https://github.com/Gnonymous/Web-CogReasoner

> Multimodal large-scale models have significantly advanced the development of web agents, enabling perception and interaction with digital environments akin to human cognition. In this paper, we argue that web agents must first acquire sufficient knowledge to effectively engage in cognitive reasoning. Therefore, we decompose a web agent's capabilities into two essential stages: knowledge content learning and cognitive processes. To formalize this, we propose Web-CogKnowledge Framework, categorizing knowledge as Factual, Conceptual, and Procedural. In this framework, knowledge content learning corresponds to the agent's processes of Memorizing and Understanding, which rely on the first two knowledge types, representing the "what" of learning. Conversely, cognitive processes correspond to Exploring, grounded in Procedural knowledge, defining the "how" of reasoning and action. To facilitate knowledge acquisition, we construct the Web-CogDataset, a structured resource curated from 14 real-world websites, designed to systematically instill core knowledge necessary for web agent. This dataset serves as the agent's conceptual grounding-the "nouns" upon which comprehension is built-as well as the basis for learning how to reason and act. Building on this foundation, we operationalize these processes through a novel knowledge-driven Chain-of-Thought (CoT) reasoning framework, developing and training our proposed agent, the Web-CogReasoner. Extensive experimentation reveals its significant superiority over existing models, especially in generalizing to unseen tasks where structured knowledge is decisive. To enable rigorous evaluation, we introduce the Web-CogBench, a comprehensive evaluation suite designed to assess and compare agent performance across the delineated knowledge domains and cognitive capabilities. Our code and data is open sourced at https://github.com/Gnonymous/Web-CogReasoner

[Arxiv](https://arxiv.org/abs/2508.01858)