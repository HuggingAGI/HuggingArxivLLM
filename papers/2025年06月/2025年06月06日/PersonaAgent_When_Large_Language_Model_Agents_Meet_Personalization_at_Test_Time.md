# # PersonaAgent: 大型语言模型代理在测试时与个性化相遇

发布时间：2025年06月06日

`Agent` `人工智能` `用户体验`

> PersonaAgent: When Large Language Model Agents Meet Personalization at Test Time

# 摘要

> 大型语言模型（LLM）赋能的智能体在众多领域和任务中展现出卓越性能。然而，现有LLM智能体往往采用通用方法，难以灵活应对用户多变的需求和偏好。为解决这一问题，我们开发了PersonaAgent——首个专注于多样化个性化任务的个性化LLM智能体框架。PersonaAgent集成了两个互补组件：包含情景与语义记忆机制的个性化记忆模块，以及支持用户定制化工具动作的个性化动作模块。核心在于，每个用户的唯一系统提示（即人格）作为中介：它利用个性化记忆的洞察力来控制智能体行为，而这些行为的结果又进一步优化记忆。基于此框架，我们提出了一种测试时用户偏好对齐策略，通过模拟最新的n个交互来优化人格提示，利用模拟与真实响应间的文本损失反馈，实现实时用户偏好对齐。实验结果表明，PersonaAgent不仅有效实现了动作空间的个性化，还在测试时的实际应用中展现出显著优势，优于其他基线方法。这充分证明了我们的方法在提供定制化、动态用户体验方面的巨大潜力。

> Large Language Model (LLM) empowered agents have recently emerged as advanced paradigms that exhibit impressive capabilities in a wide range of domains and tasks. Despite their potential, current LLM agents often adopt a one-size-fits-all approach, lacking the flexibility to respond to users' varying needs and preferences. This limitation motivates us to develop PersonaAgent, the first personalized LLM agent framework designed to address versatile personalization tasks. Specifically, PersonaAgent integrates two complementary components - a personalized memory module that includes episodic and semantic memory mechanisms; a personalized action module that enables the agent to perform tool actions tailored to the user. At the core, the persona (defined as unique system prompt for each user) functions as an intermediary: it leverages insights from personalized memory to control agent actions, while the outcomes of these actions in turn refine the memory. Based on the framework, we propose a test-time user-preference alignment strategy that simulate the latest n interactions to optimize the persona prompt, ensuring real-time user preference alignment through textual loss feedback between simulated and ground-truth responses. Experimental evaluations demonstrate that PersonaAgent significantly outperforms other baseline methods by not only personalizing the action space effectively but also scaling during test-time real-world applications. These results underscore the feasibility and potential of our approach in delivering tailored, dynamic user experiences.

[Arxiv](https://arxiv.org/abs/2506.06254)