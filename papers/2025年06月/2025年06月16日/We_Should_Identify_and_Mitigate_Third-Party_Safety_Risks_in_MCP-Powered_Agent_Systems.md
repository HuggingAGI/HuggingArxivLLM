# 在 MCP 驱动的智能体系统中，识别和缓解第三方安全风险至关重要。

发布时间：2025年06月16日

`Agent`

> We Should Identify and Mitigate Third-Party Safety Risks in MCP-Powered Agent Systems

# 摘要

> 大语言模型（LLMs）的发展已步入经验驱动的新时代，这一转变标志着环境反馈驱动学习（通过强化学习实现）以及工具使用代理的出现。这推动了模型上下文协议（MCP）的出现，该协议定义了LLMs应如何与外部服务（如API和数据）交互的标准。然而，尽管MCP已成为LLM代理系统的事实标准，但它同时也带来了新的安全风险。具体而言，MCP引入了第三方服务提供商，而这些提供商不受LLM开发者的控制。这些第三方MCP服务提供商可能具有恶意，且有经济动机利用漏洞破坏用户与代理之间的交互。在这篇立场论文中，我们呼吁LLM安全领域的研究社区密切关注MCP带来的新型安全风险，并开发新技术以构建安全的MCP驱动代理系统。为支持我们的立场，我们从三个关键部分展开论述。首先，我们构建了一个受控框架ramework，用于研究MCP驱动代理系统中的安全问题。其次，我们开展了一系列试点实验，以证明MCP驱动代理系统中的安全风险确实是一个现实威胁，且其防御并非易事。最后，我们通过展示构建安全MCP驱动代理系统的路线图，提出了我们的展望。特别地，我们呼吁研究人员追求以下研究方向：红队测试、MCP安全LLM开发、MCP安全评估、MCP安全数据积累、MCP服务保障以及MCP安全生态系统建设。我们希望这篇立场论文能够提升研究界对MCP安全的关注，并鼓励更多研究人员加入这一重要研究方向。我们的代码可在https://github.com/littlelittlenine/SafeMCP.git获取。

> The development of large language models (LLMs) has entered in a experience-driven era, flagged by the emergence of environment feedback-driven learning via reinforcement learning and tool-using agents. This encourages the emergenece of model context protocol (MCP), which defines the standard on how should a LLM interact with external services, such as \api and data. However, as MCP becomes the de facto standard for LLM agent systems, it also introduces new safety risks. In particular, MCP introduces third-party services, which are not controlled by the LLM developers, into the agent systems. These third-party MCP services provider are potentially malicious and have the economic incentives to exploit vulnerabilities and sabotage user-agent interactions. In this position paper, we advocate the research community in LLM safety to pay close attention to the new safety risks issues introduced by MCP, and develop new techniques to build safe MCP-powered agent systems. To establish our position, we argue with three key parts. (1) We first construct \framework, a controlled framework to examine safety issues in MCP-powered agent systems. (2) We then conduct a series of pilot experiments to demonstrate the safety risks in MCP-powered agent systems is a real threat and its defense is not trivial. (3) Finally, we give our outlook by showing a roadmap to build safe MCP-powered agent systems. In particular, we would call for researchers to persue the following research directions: red teaming, MCP safe LLM development, MCP safety evaluation, MCP safety data accumulation, MCP service safeguard, and MCP safe ecosystem construction. We hope this position paper can raise the awareness of the research community in MCP safety and encourage more researchers to join this important research direction. Our code is available at https://github.com/littlelittlenine/SafeMCP.git.

[Arxiv](https://arxiv.org/abs/2506.13666)