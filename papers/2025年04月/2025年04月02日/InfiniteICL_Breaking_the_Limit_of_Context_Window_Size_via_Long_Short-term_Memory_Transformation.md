# 无限ICL：借助长短时记忆变换突破上下文窗口限制

发布时间：2025年04月02日

`LLM应用` `智能对话系统`

> InfiniteICL: Breaking the Limit of Context Window Size via Long Short-term Memory Transformation

# 摘要

> 上下文学习（ICL）对大型语言模型（LLMs）至关重要，但受限于有限的上下文窗口，尤其是在超长上下文中。为突破这一限制，我们提出了InfiniteICL框架，它模拟人类记忆系统，将LLMs中的上下文和参数与短期和长期记忆相对应，专注于将临时上下文知识转化为永久参数更新。这种方法显著减少内存使用，保持了在不同输入长度下的稳定性能，并通过上下文知识提取、选择和巩固的原理，理论上实现了无限上下文的整合。实验结果表明，我们的方法将上下文长度减少了90%，同时在事实回忆、基于事实的推理和技能获取任务中，平均性能达到了全上下文提示的103%。在处理复杂的真实世界上下文（长度高达2M令牌）的连续多轮转换时，我们的方法不仅超越了全上下文提示，还仅使用了原始上下文的0.4%。这些发现凸显了InfiniteICL在突破传统上下文窗口大小限制、提升LLMs的可扩展性和效率方面的巨大潜力。

> In-context learning (ICL) is critical for large language models (LLMs), but its effectiveness is constrained by finite context windows, particularly in ultra-long contexts. To overcome this, we introduce InfiniteICL, a framework that parallels context and parameters in LLMs with short- and long-term memory in human cognitive systems, focusing on transforming temporary context knowledge into permanent parameter updates. This approach significantly reduces memory usage, maintains robust performance across varying input lengths, and theoretically enables infinite context integration through the principles of context knowledge elicitation, selection, and consolidation. Evaluations demonstrate that our method reduces context length by 90% while achieving 103% average performance of full-context prompting across fact recall, grounded reasoning, and skill acquisition tasks. When conducting sequential multi-turn transformations on complex, real-world contexts (with length up to 2M tokens), our approach surpasses full-context prompting while using only 0.4% of the original contexts. These findings highlight InfiniteICL's potential to enhance the scalability and efficiency of LLMs by breaking the limitations of conventional context window sizes.

[Arxiv](https://arxiv.org/abs/2504.01707)