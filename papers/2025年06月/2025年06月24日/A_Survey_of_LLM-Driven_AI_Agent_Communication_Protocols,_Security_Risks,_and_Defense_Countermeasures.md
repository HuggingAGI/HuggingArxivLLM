# 由LLM驱动的AI代理通信综述：协议、安全风险与防御对策

发布时间：2025年06月24日

`Agent` `人工智能` `代理通信`

> A Survey of LLM-Driven AI Agent Communication: Protocols, Security Risks, and Defense Countermeasures

# 摘要

> 近年来，大语言模型驱动的AI代理展现出前所未有的智能性、灵活性和适应性，正在迅速改变人类的生产和生活方式。如今，代理正在经历新一轮的进化，它们不再是孤立存在的大语言模型，而是开始与其它代理和工具等外部实体进行沟通，共同完成更复杂的任务。在此背景下，代理通信被视为未来AI生态系统的基石，许多组织在近几个月内开始密集设计相关通信协议（如Anthropic的MCP和Google的A2A）。然而，这一新兴领域也暴露出了严重的安全隐患，可能对现实世界造成严重损害。为了帮助研究者快速把握这一充满前景的主题并促进未来代理通信的发展，本文对代理通信安全进行了全面综述。具体而言，我们首先给出了代理通信的清晰定义，并将其整个生命周期划分为用户-代理交互、代理-代理通信和代理-环境通信三个阶段。接着，针对每个通信阶段，我们剖析相关协议并根据其通信特性分析安全风险。然后，我们总结并展望了针对每种风险的可能防御对策。最后，我们探讨了这一富有前景的研究领域中的开放问题和未来方向。

> In recent years, Large-Language-Model-driven AI agents have exhibited unprecedented intelligence, flexibility, and adaptability, and are rapidly changing human production and lifestyle. Nowadays, agents are undergoing a new round of evolution. They no longer act as an isolated island like LLMs. Instead, they start to communicate with diverse external entities, such as other agents and tools, to collectively perform more complex tasks. Under this trend, agent communication is regarded as a foundational pillar of the future AI ecosystem, and many organizations intensively begin to design related communication protocols (e.g., Anthropic's MCP and Google's A2A) within the recent few months. However, this new field exposes significant security hazard, which can cause severe damage to real-world scenarios. To help researchers to quickly figure out this promising topic and benefit the future agent communication development, this paper presents a comprehensive survey of agent communication security. More precisely, we first present a clear definition of agent communication and categorize the entire lifecyle of agent communication into three stages: user-agent interaction, agent-agent communication, and agent-environment communication. Next, for each communication phase, we dissect related protocols and analyze its security risks according to the communication characteristics. Then, we summarize and outlook on the possible defense countermeasures for each risk. Finally, we discuss open issues and future directions in this promising research field.

[Arxiv](https://arxiv.org/abs/2506.19676)