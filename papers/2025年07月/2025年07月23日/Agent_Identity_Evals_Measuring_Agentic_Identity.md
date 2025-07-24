# 能动身份评估：测量能动身份

发布时间：2025年07月23日

`Agent` `人工智能` `代理系统`

> Agent Identity Evals: Measuring Agentic Identity

# 摘要

> 大型语言模型代理（LMAs）的代理能力和可信度关键在于其在时间过程中保持稳定、可靠自我认同的能力。然而，LMAs继承了大型语言模型（LLMs）的某些缺陷（如无状态性、随机性、对提示的敏感性以及语言中介性），这些缺陷可能削弱它们的可识别性、连续性、持久性和一致性。这种自我认同的流失可能通过干扰LMAs的代理能力（如推理、规划和行动）来损害其可靠性、可信度和实用性。为了应对这些挑战，我们引入了	extit{代理身份评估}（AIE），这是一个严格且数据驱动的实证框架，用于衡量LMA系统在时间过程中表现出和维持其代理身份的程度，包括其能力、属性以及从状态扰动中恢复的能力。AIE包含一组新颖的指标，这些指标可以与其他性能、能力和代理稳健性指标结合使用，以辅助设计优化的LMA基础设施和支撑结构，如记忆和工具。我们提出了可以在LMA生命周期的每个阶段应用的正式定义和方法，并提供了如何应用它们的示例。


> Central to agentic capability and trustworthiness of language model agents (LMAs) is the extent they maintain stable, reliable, identity over time. However, LMAs inherit pathologies from large language models (LLMs) (statelessness, stochasticity, sensitivity to prompts and linguistically-intermediation) which can undermine their identifiability, continuity, persistence and consistency. This attrition of identity can erode their reliability, trustworthiness and utility by interfering with their agentic capabilities such as reasoning, planning and action. To address these challenges, we introduce \textit{agent identity evals} (AIE), a rigorous, statistically-driven, empirical framework for measuring the degree to which an LMA system exhibit and maintain their agentic identity over time, including their capabilities, properties and ability to recover from state perturbations. AIE comprises a set of novel metrics which can integrate with other measures of performance, capability and agentic robustness to assist in the design of optimal LMA infrastructure and scaffolding such as memory and tools. We set out formal definitions and methods that can be applied at each stage of the LMA life-cycle, and worked examples of how to apply them.

[Arxiv](https://arxiv.org/abs/2507.17257)