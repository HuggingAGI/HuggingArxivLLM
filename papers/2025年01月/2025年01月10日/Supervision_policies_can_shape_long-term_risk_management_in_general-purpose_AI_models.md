# 监督策略能够影响通用AI模型的长期风险管理。

发布时间：2025年01月10日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLMs）在通用人工智能（GPAI）模型中的应用，特别是它们在AI监管和风险管理中的角色。论文提出了一个模拟框架，用于评估不同的监管政策如何影响风险报告和处理，这直接涉及到LLMs在实际应用中的使用和影响。因此，这篇论文应被分类为“LLM应用”。` `人工智能` `风险管理`

> Supervision policies can shape long-term risk management in general-purpose AI models

# 摘要

> 通用人工智能（GPAI）模型，尤其是大型语言模型（LLMs）的迅速普及和部署，给AI监管机构带来了前所未有的挑战。我们推测，这些机构将不得不应对一个新兴的风险和事件报告生态系统，这一系统可能超出其监管能力。为此，我们开发了一个模拟框架，该框架通过从多样化的风险、事件或危害报告生态系统中提取的特征进行参数化，包括社区驱动的平台、众包倡议和专家评估。我们评估了四种监管政策：非优先（先到先得）、随机选择、基于优先级（优先处理高风险）和多样性优先（在优先处理高风险的同时，平衡覆盖所有风险类型）。结果表明，虽然基于优先级和多样性优先的政策在缓解高影响风险方面更为有效，特别是那些由专家识别的风险，但它们可能会无意中忽视由更广泛社区报告的系统性问题。这种疏忽可能会产生反馈循环，放大某些类型的报告，同时抑制其他类型的报告，导致对整体风险格局的扭曲认知。我们通过几个真实世界的数据集验证了模拟结果，其中包括一个包含超过一百万次ChatGPT互动的数据集，其中超过15万次对话被识别为有风险。这一验证揭示了AI风险监管中固有的复杂权衡，并强调了风险管理政策的选择如何塑造社会中使用各种GPAI模型的未来风险格局。

> The rapid proliferation and deployment of General-Purpose AI (GPAI) models, including large language models (LLMs), present unprecedented challenges for AI supervisory entities. We hypothesize that these entities will need to navigate an emergent ecosystem of risk and incident reporting, likely to exceed their supervision capacity. To investigate this, we develop a simulation framework parameterized by features extracted from the diverse landscape of risk, incident, or hazard reporting ecosystems, including community-driven platforms, crowdsourcing initiatives, and expert assessments. We evaluate four supervision policies: non-prioritized (first-come, first-served), random selection, priority-based (addressing the highest-priority risks first), and diversity-prioritized (balancing high-priority risks with comprehensive coverage across risk types). Our results indicate that while priority-based and diversity-prioritized policies are more effective at mitigating high-impact risks, particularly those identified by experts, they may inadvertently neglect systemic issues reported by the broader community. This oversight can create feedback loops that amplify certain types of reporting while discouraging others, leading to a skewed perception of the overall risk landscape. We validate our simulation results with several real-world datasets, including one with over a million ChatGPT interactions, of which more than 150,000 conversations were identified as risky. This validation underscores the complex trade-offs inherent in AI risk supervision and highlights how the choice of risk management policies can shape the future landscape of AI risks across diverse GPAI models used in society.

[Arxiv](https://arxiv.org/abs/2501.06137)