# LongFuncEval：评估长上下文模型在函数调用任务中的效果

发布时间：2025年04月30日

`LLM应用` `人工智能`

> LongFuncEval: Measuring the effectiveness of long context models for function calling

# 摘要

> 近期多项研究表明，大型语言模型（LLMs）在调用外部工具或函数方面表现出色。也有研究关注于LLMs处理更长上下文长度的能力。在这两个研究领域交汇处，我们发现一个有趣的问题：LLMs在长上下文环境下能否准确调用函数。尤其在调用工具时，LLMs面临三大主要挑战：1) 工具种类繁多，2) 工具API返回的响应过长，3) 多轮对话的长度增加。这些问题在企业级应用中尤为突出，因为LLMs需要通过多轮对话与用户交互，完成需要大量复杂工具的复杂任务。文献中已有许多关于自然语言任务中长上下文挑战的研究，如“中间迷失”或“大海捞针”现象。本文首次尝试全面研究工具调用场景下这些模型的长上下文理解能力。我们针对挑战1和3修改了现有基准测试，并为挑战2创建了一个新的评估集，以便进行分析。我们逐步增加输入上下文长度，并改变答案在输入中的位置。在使用多个长上下文模型进行评估时，我们发现随着工具数量的增加，性能下降了7%到85%；随着工具响应长度的增加，答案检索能力下降了7%到91%；而随着多轮对话的延长，性能分别下降了13%和40%。我们的研究表明，LLMs在工具调用场景下仍难以应对长上下文挑战，这为未来的研究提供了方向，以推动LLMs的进一步改进。

> Multiple recent studies have documented large language models' (LLMs) performance on calling external tools/functions. Others focused on LLMs' abilities to handle longer context lengths. At the intersection of these areas lies another interesting problem: LLMs' abilities to accurately perform function calls in long context settings. Particularly, when calling tools, LLMs are encumbered by three predominant challenges: (1) a large catalog of tools, (2) long responses from the tool APIs, and (3) long multi-turn conversations. These challenges are particularly relevant to enterprise applications of LLMs which engage in multi-turn conversations with users to complete complex tasks that require a large catalog of complex tools. The literature contains multiple investigations of long context challenges such as lost in the middle or needle in the haystack for natural language tasks. In this paper, we make the first attempt to comprehensively study the long context understanding capabilities of these models in the tool calling setup. We modify existing benchmarks for challenge 1 and 3, and create a new evaluation set for challenge 2 to enable this analysis. We gradually increase the input context length and also vary the position of the answer in the input. When evaluated with several long context models, we observe a performance drop of 7% to 85% as the number of tools increases, a 7% to 91% degradation in answer retrieval as the tool responses length increases, and 13% and 40% degradation for as multi-turn conversations get longer. Our study shows that LLMs still struggle with long context in tool calling settings, motivating future research to drive further LLM improvements.

[Arxiv](https://arxiv.org/abs/2505.10570)