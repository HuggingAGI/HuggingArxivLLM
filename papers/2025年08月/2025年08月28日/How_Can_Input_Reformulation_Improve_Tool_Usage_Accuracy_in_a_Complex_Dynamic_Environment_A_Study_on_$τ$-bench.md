# 输入重构如何在复杂动态环境中提高工具使用准确性？——一项关于【数学公式】的研究

发布时间：2025年08月28日

`Agent` `基础理论`

> How Can Input Reformulation Improve Tool Usage Accuracy in a Complex Dynamic Environment? A Study on $τ$-bench

# 摘要

> 大型语言模型（LLMs）在推理与规划能力上的最新突破，使其有望成为动态环境中能自主使用工具的智能体。但在【数学公式】-bench这类多轮对话场景中，这些智能体常面临三大挑战：推理一致性不足、难以遵守特定领域策略，以及在长时间工具调用与对话中难以提取准确信息。为捕捉并解决这些问题，我们对对话轨迹中的常见错误展开了全面人工分析。随后，我们通过重新表述工具调用智能体的输入，尝试优化其决策能力。最后，我们提出输入重构多智能体（IRMA）框架——它能自动重构用户查询，并补充相关领域规则与工具建议，引导工具调用智能体聚焦关键信息。结果显示，在总体pass^5评分中，IRMA的表现显著优于ReAct、函数调用和自我反思方法，分别提升了16.1%、12.7%和19.1%。这些发现表明，在动态环境中，IRMA相比其他方法具有更出色的可靠性和一致性。

> Recent advances in reasoning and planning capabilities of large language models (LLMs) have enabled their potential as autonomous agents capable of tool use in dynamic environments. However, in multi-turn conversational environments like $τ$-bench, these agents often struggle with consistent reasoning, adherence to domain-specific policies, and extracting correct information over a long horizon of tool-calls and conversation. To capture and mitigate these failures, we conduct a comprehensive manual analysis of the common errors occurring in the conversation trajectories. We then experiment with reformulations of inputs to the tool-calling agent for improvement in agent decision making. Finally, we propose the Input-Reformulation Multi-Agent (IRMA) framework, which automatically reformulates user queries augmented with relevant domain rules and tool suggestions for the tool-calling agent to focus on. The results show that IRMA significantly outperforms ReAct, Function Calling, and Self-Reflection by 16.1%, 12.7%, and 19.1%, respectively, in overall pass^5 scores. These findings highlight the superior reliability and consistency of IRMA compared to other methods in dynamic environments.

[Arxiv](https://arxiv.org/abs/2508.20931)