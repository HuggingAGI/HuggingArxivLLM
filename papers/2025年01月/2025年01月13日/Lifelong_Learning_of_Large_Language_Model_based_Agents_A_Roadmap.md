# 大型语言模型智能体的终身学习：发展蓝图

发布时间：2025年01月13日

`Agent

理由：这篇论文主要讨论了将终身学习（持续或增量学习）融入大型语言模型（LLM）代理的技术，并详细描述了感知模块、记忆模块和行动模块等核心组件。这些内容直接涉及到LLM代理的设计和实现，特别是如何让代理在动态环境中持续适应和提升性能。因此，这篇论文应归类为Agent。` `人工智能` `终身学习`

> Lifelong Learning of Large Language Model based Agents: A Roadmap

# 摘要

> 终身学习（又称持续或增量学习）是推动人工通用智能（AGI）发展的关键，它让系统能在动态环境中持续适应。尽管大型语言模型（LLMs）在自然语言处理上表现出色，但现有LLM代理多为静态系统设计，难以应对新挑战。本调查首次系统总结了将终身学习融入LLM代理的技术，将其核心组件分为三部分：感知模块（整合多模态输入）、记忆模块（存储与检索动态知识）、行动模块（与动态环境交互）。我们探讨了这些模块如何协同实现持续适应、避免灾难性遗忘并提升长期性能。本调查为开发LLM代理终身学习能力的研究者提供了路线图，涵盖新兴趋势、评估指标和应用场景。相关资源见\href{this url}{https://github.com/qianlima-lab/awesome-lifelong-llm-agent}。

> Lifelong learning, also known as continual or incremental learning, is a crucial component for advancing Artificial General Intelligence (AGI) by enabling systems to continuously adapt in dynamic environments. While large language models (LLMs) have demonstrated impressive capabilities in natural language processing, existing LLM agents are typically designed for static systems and lack the ability to adapt over time in response to new challenges. This survey is the first to systematically summarize the potential techniques for incorporating lifelong learning into LLM-based agents. We categorize the core components of these agents into three modules: the perception module for multimodal input integration, the memory module for storing and retrieving evolving knowledge, and the action module for grounded interactions with the dynamic environment. We highlight how these pillars collectively enable continuous adaptation, mitigate catastrophic forgetting, and improve long-term performance. This survey provides a roadmap for researchers and practitioners working to develop lifelong learning capabilities in LLM agents, offering insights into emerging trends, evaluation metrics, and application scenarios. Relevant literature and resources are available at \href{this url}{https://github.com/qianlima-lab/awesome-lifelong-llm-agent}.

[Arxiv](https://arxiv.org/abs/2501.07278)