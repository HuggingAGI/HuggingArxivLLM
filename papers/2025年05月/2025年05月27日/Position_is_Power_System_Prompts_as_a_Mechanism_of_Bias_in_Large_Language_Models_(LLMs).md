# 位置即力量，权重即权力：系统提示词作为大型语言模型 (LLMs) 中偏见的机制。

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）中系统提示的位置和内容对模型输出的影响，特别是如何导致偏见和潜在的危害。这属于模型的应用层面，因为它研究的是模型在实际使用中的行为和影响，而不是模型本身的理论或机制。因此，归类为LLM应用。` `公平性`

> Position is Power: System Prompts as a Mechanism of Bias in Large Language Models (LLMs)

# 摘要

> # 摘要
大型语言模型（LLMs）中的系统提示是预定义的指令，用于指导模型行为，在文本处理和生成过程中优先于用户输入。LLM部署者越来越多地使用它们来确保跨上下文的一致性响应。虽然模型提供者设置了系统提示的基础，但部署者和第三方开发者可以在不查看他人添加内容的情况下附加额外的提示，而这种分层实现完全隐藏在终端用户之外。随着系统提示变得越来越复杂，它们可能会直接或间接地引入未被考虑的副作用。这种缺乏透明度的情况引发了一些基本问题：不同指令中信息的位置如何影响模型输出。因此，本研究旨在探讨信息位置如何影响模型行为。为此，我们比较了六种商用LLMs和50个 demographic groups在系统提示与用户提示中对 demographic information 的处理方式。我们的分析揭示了显著的偏见，表现为用户表示和决策场景中的差异。由于这些差异源于不可访问且不透明的系统级配置，它们可能引发代表性、分配性以及其他潜在的无法被用户察觉或纠正的偏见和下游危害。我们的发现引起了对这些关键问题的关注，如果这些问题未被深入研究，可能会导致持续的伤害。此外，我们主张将系统提示分析纳入AI审计流程，尤其是在可定制的系统提示在商业AI部署中越来越普遍的情况下。

> System prompts in Large Language Models (LLMs) are predefined directives that guide model behaviour, taking precedence over user inputs in text processing and generation. LLM deployers increasingly use them to ensure consistent responses across contexts. While model providers set a foundation of system prompts, deployers and third-party developers can append additional prompts without visibility into others' additions, while this layered implementation remains entirely hidden from end-users. As system prompts become more complex, they can directly or indirectly introduce unaccounted for side effects. This lack of transparency raises fundamental questions about how the position of information in different directives shapes model outputs. As such, this work examines how the placement of information affects model behaviour. To this end, we compare how models process demographic information in system versus user prompts across six commercially available LLMs and 50 demographic groups. Our analysis reveals significant biases, manifesting in differences in user representation and decision-making scenarios. Since these variations stem from inaccessible and opaque system-level configurations, they risk representational, allocative and potential other biases and downstream harms beyond the user's ability to detect or correct. Our findings draw attention to these critical issues, which have the potential to perpetuate harms if left unexamined. Further, we argue that system prompt analysis must be incorporated into AI auditing processes, particularly as customisable system prompts become increasingly prevalent in commercial AI deployments.

[Arxiv](https://arxiv.org/abs/2505.21091)