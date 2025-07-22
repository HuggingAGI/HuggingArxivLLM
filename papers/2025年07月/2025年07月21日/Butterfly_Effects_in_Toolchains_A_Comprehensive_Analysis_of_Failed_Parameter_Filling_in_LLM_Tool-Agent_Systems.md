# 蝴蝶效应在工具链中的体现：大型语言模型工具-代理系统中参数填充失败的全面分析

发布时间：2025年07月21日

`Agent` `工具代理` `模型可靠性`

> Butterfly Effects in Toolchains: A Comprehensive Analysis of Failed Parameter Filling in LLM Tool-Agent Systems

# 摘要

> 工具代理范式的出现极大地拓宽了大型语言模型（LLM）的能力边界，使其能够完成更加复杂的任务。然而，由于执行过程中参数失效的问题，这一范式的有效性受到了限制。本研究首先构建了一个参数失效分类法，从主流工具代理的调用链中衍生出了五类失效情况。通过在输入中应用15种不同的输入扰动方法，我们探究了三种不同输入源与失效类别之间的关联性。实验结果表明，参数名称幻觉失效主要源于LLM自身的固有局限，而输入源的问题则主要引发了其他类型的失效模式。为了提升工具代理交互的可靠性和有效性，我们提出了标准化工具返回格式、优化错误反馈机制以及确保参数一致性等改进建议。

> The emergence of the tool agent paradigm has broadened the capability boundaries of the Large Language Model (LLM), enabling it to complete more complex tasks. However, the effectiveness of this paradigm is limited due to the issue of parameter failure during its execution. To explore this phenomenon and propose corresponding suggestions, we first construct a parameter failure taxonomy in this paper. We derive five failure categories from the invocation chain of a mainstream tool agent. Then, we explore the correlation between three different input sources and failure categories by applying 15 input perturbation methods to the input. Experimental results show that parameter name hallucination failure primarily stems from inherent LLM limitations, while issues with input sources mainly cause other failure patterns. To improve the reliability and effectiveness of tool-agent interactions, we propose corresponding improvement suggestions, including standardizing tool return formats, improving error feedback mechanisms, and ensuring parameter consistency.

[Arxiv](https://arxiv.org/abs/2507.15296)