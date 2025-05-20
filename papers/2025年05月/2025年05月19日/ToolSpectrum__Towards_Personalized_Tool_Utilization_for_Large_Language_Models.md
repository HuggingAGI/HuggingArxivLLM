# 工具谱：迈向大型语言模型的个性化工具应用

发布时间：2025年05月19日

`LLM应用` `人工智能` `工具增强型模型`

> ToolSpectrum : Towards Personalized Tool Utilization for Large Language Models

# 摘要

> 在大型语言模型（LLMs）中整合外部工具能够增强其访问实时信息和特定领域服务的能力。然而，现有方法仅关注根据用户指令选择功能性工具，忽视了工具选择中的情境感知个性化。这种忽视导致用户体验不佳和工具使用效率低下，特别是在需要基于情境因素进行精细选择的重叠工具集场景中。为了解决这一问题，我们提出了ToolSpectrum，这是一个评估LLMs在个性化工具利用方面能力的基准。具体来说，我们正式定义了个性化工具利用的两个关键维度：用户档案和环境因素，并分析了它们对工具利用的独立和协同影响。通过在ToolSpectrum上的广泛实验，我们证明了个性化工具利用在各种场景下显著提升了用户体验。然而，即使是当前最先进的LLMs在同时考虑用户档案和环境因素方面也表现出有限的能力，常常优先考虑一个维度而牺牲另一个。我们的研究结果强调了在工具增强型LLMs中实现情境感知个性化的重要性，并揭示了当前模型的关键局限性。我们的数据和代码可在https://github.com/Chengziha0/ToolSpectrum获取。

> While integrating external tools into large language models (LLMs) enhances their ability to access real-time information and domain-specific services, existing approaches focus narrowly on functional tool selection following user instructions, overlooking the context-aware personalization in tool selection. This oversight leads to suboptimal user satisfaction and inefficient tool utilization, particularly when overlapping toolsets require nuanced selection based on contextual factors. To bridge this gap, we introduce ToolSpectrum, a benchmark designed to evaluate LLMs' capabilities in personalized tool utilization. Specifically, we formalize two key dimensions of personalization, user profile and environmental factors, and analyze their individual and synergistic impacts on tool utilization. Through extensive experiments on ToolSpectrum, we demonstrate that personalized tool utilization significantly improves user experience across diverse scenarios. However, even state-of-the-art LLMs exhibit the limited ability to reason jointly about user profiles and environmental factors, often prioritizing one dimension at the expense of the other. Our findings underscore the necessity of context-aware personalization in tool-augmented LLMs and reveal critical limitations for current models. Our data and code are available at https://github.com/Chengziha0/ToolSpectrum.

[Arxiv](https://arxiv.org/abs/2505.13176)