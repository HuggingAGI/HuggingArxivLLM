# 关于智能体大型语言模型系统的实用考量

发布时间：2024年12月05日

`Agent` `代理模型`

> Practical Considerations for Agentic LLM Systems

# 摘要

> 近年来，大型语言模型（LLMs）的实力日益增强，人们对将其用作自主代理的底层模型的兴趣也愈发浓厚。尽管 LLMs 在自然语言领域展现出新兴能力和广博的专业知识，但其固有的不可预测性让 LLM 代理的实施困难重重，致使相关研究与这类系统的实际应用之间存在鸿沟。为了填补这一鸿沟，本文在既定的应用范式背景下，梳理了来自研究界的切实可行的见解和考量，助力构建并推动强大的 LLM 代理的合理部署。具体而言，我们依据应用重点文献中的常见做法，将相关研究成果归为四大类——规划、记忆、工具和控制流，并突出了为实际应用设计代理型 LLMs 时的实际考量，比如处理随机性和高效管理资源。虽然我们未进行实证评估，但确实为探讨学术界和工业界中代理型 LLM 设计的关键方面提供了必要基础。

> As the strength of Large Language Models (LLMs) has grown over recent years, so too has interest in their use as the underlying models for autonomous agents. Although LLMs demonstrate emergent abilities and broad expertise across natural language domains, their inherent unpredictability makes the implementation of LLM agents challenging, resulting in a gap between related research and the real-world implementation of such systems. To bridge this gap, this paper frames actionable insights and considerations from the research community in the context of established application paradigms to enable the construction and facilitate the informed deployment of robust LLM agents. Namely, we position relevant research findings into four broad categories--Planning, Memory, Tools, and Control Flow--based on common practices in application-focused literature and highlight practical considerations to make when designing agentic LLMs for real-world applications, such as handling stochasticity and managing resources efficiently. While we do not conduct empirical evaluations, we do provide the necessary background for discussing critical aspects of agentic LLM designs, both in academia and industry.

[Arxiv](https://arxiv.org/abs/2412.04093)