# 黑暗崛起：角色扮演对话代理中安全与实用的权衡

发布时间：2025年02月28日

`LLM应用` `对话系统` `角色模拟`

> The Rise of Darkness: Safety-Utility Trade-Offs in Role-Playing Dialogue Agents

# 摘要

> 大型语言模型（LLMs）在角色扮演对话代理领域取得了显著进展，特别是在角色模拟方面展现出了强大的实用性。然而，这些模型在平衡角色表现的实用性和内容安全性方面仍面临挑战，因为角色模拟往往伴随着生成不安全内容的风险。为解决这一问题，我们首先对多个LLMs的安全性与实用性的权衡进行了系统性研究。分析发现，反派角色和用户查询引发的风险场景（即风险耦合）是导致这一权衡的主要原因。在此基础上，我们提出了一种新型的自适应动态多偏好（ADMP）方法，该方法能够根据风险耦合的程度动态调整安全性和实用性的偏好，引导模型生成偏向实用或安全的响应。此外，我们还将耦合间隔采样（CMS）引入到耦合检测中，以增强模型处理高风险场景的能力。实验结果表明，我们的方法在提升安全性的同时保持了实用性。

> Large Language Models (LLMs) have made remarkable advances in role-playing dialogue agents, demonstrating their utility in character simulations. However, it remains challenging for these agents to balance character portrayal utility with content safety because this essential character simulation often comes with the risk of generating unsafe content. To address this issue, we first conduct a systematic exploration of the safety-utility trade-off across multiple LLMs. Our analysis reveals that risk scenarios created by villain characters and user queries (referred to as risk coupling) contribute to this trade-off. Building on this, we propose a novel Adaptive Dynamic Multi-Preference (ADMP) method, which dynamically adjusts safety-utility preferences based on the degree of risk coupling and guides the model to generate responses biased toward utility or safety. We further introduce Coupling Margin Sampling (CMS) into coupling detection to enhance the model's ability to handle high-risk scenarios. Experimental results demonstrate that our approach improves safety metrics while maintaining utility.

[Arxiv](https://arxiv.org/abs/2502.20757)