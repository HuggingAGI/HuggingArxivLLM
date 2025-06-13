# 以智能体为中心构建网络，而不是让智能体适应网络。

发布时间：2025年06月12日

`Agent` `智能体技术` `Web技术`

> Build the web for agents, not agents for the web

# 摘要

> 大型语言模型（LLMs）及其多模态衍生模型的最新进展激起了人们对开发Web代理的巨大兴趣，这些AI系统能够自主在Web环境中导航并完成任务。尽管在自动化复杂Web交互方面展现出巨大潜力，但现有方法由于人类设计界面与LLM能力之间的根本性不匹配，仍面临重大挑战。现有方法在处理这些输入时面临诸多挑战，无论是解析庞大的DOM树，依赖附加信息的截图，还是完全绕过用户界面通过API交互。本文呼吁在Web代理研究中实现范式转变：与其迫使Web代理适应为人类设计的界面，不如开发一种专门针对智能体能力优化的新交互范式。为此，我们引入了智能体网页界面（AWI）的概念，这是一种专为智能体设计的网站导航界面。我们制定了六项设计指导原则，强调安全性、效率和标准化，以平衡所有主要利益相关者的诉求。这一重新构想旨在克服现有界面的根本性限制，为更高效、可靠和透明的Web代理设计铺平道路，这将是一项需要更广泛ML社区共同参与的协作努力。

> Recent advancements in Large Language Models (LLMs) and multimodal counterparts have spurred significant interest in developing web agents -- AI systems capable of autonomously navigating and completing tasks within web environments. While holding tremendous promise for automating complex web interactions, current approaches face substantial challenges due to the fundamental mismatch between human-designed interfaces and LLM capabilities. Current methods struggle with the inherent complexity of web inputs, whether processing massive DOM trees, relying on screenshots augmented with additional information, or bypassing the user interface entirely through API interactions. This position paper advocates for a paradigm shift in web agent research: rather than forcing web agents to adapt to interfaces designed for humans, we should develop a new interaction paradigm specifically optimized for agentic capabilities. To this end, we introduce the concept of an Agentic Web Interface (AWI), an interface specifically designed for agents to navigate a website. We establish six guiding principles for AWI design, emphasizing safety, efficiency, and standardization, to account for the interests of all primary stakeholders. This reframing aims to overcome fundamental limitations of existing interfaces, paving the way for more efficient, reliable, and transparent web agent design, which will be a collaborative effort involving the broader ML community.

[Arxiv](https://arxiv.org/abs/2506.10953)