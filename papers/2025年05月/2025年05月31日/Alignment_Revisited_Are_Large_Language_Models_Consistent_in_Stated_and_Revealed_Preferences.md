# 再探对齐：大型语言模型的陈述偏好与揭示偏好是否一致？

发布时间：2025年05月31日

`LLM理论` `社会影响`

> Alignment Revisited: Are Large Language Models Consistent in Stated and Revealed Preferences?

# 摘要

> 近期大型语言模型（LLMs）的进步凸显了让LLMs行为与人类价值观对齐的必要性。一个关键但尚未充分研究的问题是，LLMs的声明偏好（其对一般原则的报告对齐情况）与其揭示偏好（从具体情境下的决策中推断得出）之间可能存在分歧。这种偏差引发了关于LLMs可解释性、可信度、推理透明度以及在高风险应用中进行道德部署的基本担忧。

本研究正式定义了这一偏好偏差并提出了一种测量方法。我们探讨了LLMs如何在特定情境下激活不同的指导原则，从而做出与先前声明的一般原则相悖的选择。我们的方法涉及创建一个精心设计的提示语丰富数据集，作为一系列强制二元选择，并将其呈现给LLMs。我们通过比较LLMs对一般原则提示的声明偏好与LLMs对情境化提示的揭示偏好，使用KL散度等指标量化偏差。

我们在不同类别的偏好以及四个主流LLMs上重复了这一分析，发现提示格式的微小变化常常会改变首选项，无论偏好类别和测试中的LLMs如何。这一普遍现象凸显了我们对LLM决策能力的理解和控制的不足。本研究将对将LLMs整合到服务中至关重要，尤其是在直接与人类互动的服务中，道德、公平和社会责任是关键维度。此外，识别或意识到此类偏差在LLMs日益被设想用于自主智能体任务时将至关重要，在这些任务中，人类无法对所有LLMs的中间决策步骤进行持续评估。

> Recent advances in Large Language Models (LLMs) highlight the need to align their behaviors with human values. A critical, yet understudied, issue is the potential divergence between an LLM's stated preferences (its reported alignment with general principles) and its revealed preferences (inferred from decisions in contextualized scenarios). Such deviations raise fundamental concerns for the interpretability, trustworthiness, reasoning transparency, and ethical deployment of LLMs, particularly in high-stakes applications. This work formally defines and proposes a method to measure this preference deviation. We investigate how LLMs may activate different guiding principles in specific contexts, leading to choices that diverge from previously stated general principles. Our approach involves crafting a rich dataset of well-designed prompts as a series of forced binary choices and presenting them to LLMs. We compare LLM responses to general principle prompts stated preference with LLM responses to contextualized prompts revealed preference, using metrics like KL divergence to quantify the deviation. We repeat the analysis across different categories of preferences and on four mainstream LLMs and find that a minor change in prompt format can often pivot the preferred choice regardless of the preference categories and LLMs in the test. This prevalent phenomenon highlights the lack of understanding and control of the LLM decision-making competence. Our study will be crucial for integrating LLMs into services, especially those that interact directly with humans, where morality, fairness, and social responsibilities are crucial dimensions. Furthermore, identifying or being aware of such deviation will be critically important as LLMs are increasingly envisioned for autonomous agentic tasks where continuous human evaluation of all LLMs' intermediary decision-making steps is impossible.

[Arxiv](https://arxiv.org/abs/2506.00751)