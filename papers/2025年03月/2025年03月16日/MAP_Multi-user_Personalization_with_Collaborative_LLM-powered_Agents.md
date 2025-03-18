# MAP：协作式LLM驱动代理实现的多用户个性化

发布时间：2025年03月16日

`Agent` `多用户环境` `个性化服务`

> MAP: Multi-user Personalization with Collaborative LLM-powered Agents

# 摘要

> 大规模语言模型（LLMs）和LLM驱动的代理在多用户环境中的广泛应用凸显了可靠且易于使用的方法的重要性，这些方法能够适应多样化的偏好并解决冲突指令。基于冲突解决理论，我们提出了一种面向用户的多用户个性化工作流程，包含三个阶段：反思、分析和反馈。随后，我们介绍了MAP——一个多智能体系统，用于实现这一工作流程。通过将子任务委托给专门的智能体，MAP (1) 检索并反思相关用户信息，同时通过智能体之间的互动增强可靠性，(2) 提供详细分析以提升透明度和可用性，以及 (3) 集成用户反馈以迭代优化结果。我们的用户研究结果（n=12）凸显了MAP在冲突解决中的有效性和可用性，同时强调了用户在解决验证和故障管理中的参与重要性。这项研究展示了多智能体系统在实施用户中心化多用户个性化工作流程方面的潜力，并通过为多用户环境中的个性化提供见解来总结我们的研究。

> The widespread adoption of Large Language Models (LLMs) and LLM-powered agents in multi-user settings underscores the need for reliable, usable methods to accommodate diverse preferences and resolve conflicting directives. Drawing on conflict resolution theory, we introduce a user-centered workflow for multi-user personalization comprising three stages: Reflection, Analysis, and Feedback. We then present MAP -- a \textbf{M}ulti-\textbf{A}gent system for multi-user \textbf{P}ersonalization -- to operationalize this workflow. By delegating subtasks to specialized agents, MAP (1) retrieves and reflects on relevant user information, while enhancing reliability through agent-to-agent interactions, (2) provides detailed analysis for improved transparency and usability, and (3) integrates user feedback to iteratively refine results. Our user study findings (n=12) highlight MAP's effectiveness and usability for conflict resolution while emphasizing the importance of user involvement in resolution verification and failure management. This work highlights the potential of multi-agent systems to implement user-centered, multi-user personalization workflows and concludes by offering insights for personalization in multi-user contexts.

[Arxiv](https://arxiv.org/abs/2503.12757)