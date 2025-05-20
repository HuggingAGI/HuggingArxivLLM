# 通过隐藏档案任务评估多智能体LLMs的集体推理表现

发布时间：2025年05月15日

`LLM应用` `人工智能` `社会心理学`

> Assessing Collective Reasoning in Multi-Agent LLMs via Hidden Profile Tasks

# 摘要

> 基于大型语言模型（LLMs）的多智能体系统通过整合分布式信息，展现出强大的问题解决潜力，但同时也可能复制人类群体中常见的集体推理失误。目前，尚无理论支持的基准来系统性评估这些失误。本文引入社会心理学中的“隐藏配置范式”，为多智能体LLM系统提供了一个诊断测试床。通过在智能体间不对称分配关键信息，该范式揭示了智能体间动态如何影响集体推理的成败。我们首先将该范式形式化，用于分布式知识环境下的多智能体决策，并构建了一个包含九项任务的基准，涵盖多样化场景，包括对人类研究的改编。实验中，我们使用GPT-4.1和其他五种领先LLMs（包括增强推理的变体）进行测试，结果表明所有模型的多智能体系统在集体推理中的准确性均低于单智能体在完整信息情况下的表现。虽然智能体的集体表现总体上与人类群体相当，但细微的行为差异显现，例如对社会可接受性的敏感度增加。最后，我们通过探索多智能体LLM系统中合作与矛盾的权衡，展示了该范式的诊断价值。我们发现，尽管合作型智能体在集体环境中易过度协调，但增加矛盾则会损害群体收敛能力。这项研究为评估多智能体LLM系统提供了一个可复现的框架，并为未来在人工集体智能和人机交互领域的研究提供了重要启示。

> Multi-agent systems built on large language models (LLMs) promise enhanced problem-solving through distributed information integration, but also risk replicating collective reasoning failures observed in human groups. Yet, no theory-grounded benchmark exists to systematically evaluate such failures. In this paper, we introduce the Hidden Profile paradigm from social psychology as a diagnostic testbed for multi-agent LLM systems. By distributing critical information asymmetrically across agents, the paradigm reveals how inter-agent dynamics support or hinder collective reasoning. We first formalize the paradigm for multi-agent decision-making under distributed knowledge and instantiate it as a benchmark with nine tasks spanning diverse scenarios, including adaptations from prior human studies. We then conduct experiments with GPT-4.1 and five other leading LLMs, including reasoning-enhanced variants, showing that multi-agent systems across all models fail to match the accuracy of single agents given complete information. While agents' collective performance is broadly comparable to that of human groups, nuanced behavioral differences emerge, such as increased sensitivity to social desirability. Finally, we demonstrate the paradigm's diagnostic utility by exploring a cooperation-contradiction trade-off in multi-agent LLM systems. We find that while cooperative agents are prone to over-coordination in collective settings, increased contradiction impairs group convergence. This work contributes a reproducible framework for evaluating multi-agent LLM systems and motivates future research on artificial collective intelligence and human-AI interaction.

[Arxiv](https://arxiv.org/abs/2505.11556)