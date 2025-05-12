# LLMs 在多轮对话中迷失方向了吗？

发布时间：2025年05月09日

`LLM应用` `对话系统`

> LLMs Get Lost In Multi-Turn Conversation

# 摘要

> 大型语言模型（LLMs）作为对话交互界面，具备强大的潜力。它们不仅能在用户明确任务时提供帮助，还能通过多轮对话协助用户定义、探索和细化需求。尽管分析表明，用户指令中存在大量不完整或模糊的情况，但现有LLM评估主要集中在单轮、完整明确的指令场景。在本研究中，我们进行了大规模模拟实验，比较了LLMs在单轮和多轮对话中的性能表现。实验结果表明，所有测试的顶级开源和闭源LLMs在多轮对话中的表现均显著低于单轮对话，六个生成任务的平均性能下降了39%。通过对200,000+次模拟对话的分析，我们将性能下降归因于两个方面：能力的轻微损失和可靠性的显著下降。我们发现，LLMs往往在对话初期就做出假设，并过早尝试生成最终解决方案，而过度依赖这些假设。简单来说，我们发现当LLMs在对话中偏离正确方向时，它们会迷失并无法恢复。

> Large Language Models (LLMs) are conversational interfaces. As such, LLMs have the potential to assist their users not only when they can fully specify the task at hand, but also to help them define, explore, and refine what they need through multi-turn conversational exchange. Although analysis of LLM conversation logs has confirmed that underspecification occurs frequently in user instructions, LLM evaluation has predominantly focused on the single-turn, fully-specified instruction setting. In this work, we perform large-scale simulation experiments to compare LLM performance in single- and multi-turn settings. Our experiments confirm that all the top open- and closed-weight LLMs we test exhibit significantly lower performance in multi-turn conversations than single-turn, with an average drop of 39% across six generation tasks. Analysis of 200,000+ simulated conversations decomposes the performance degradation into two components: a minor loss in aptitude and a significant increase in unreliability. We find that LLMs often make assumptions in early turns and prematurely attempt to generate final solutions, on which they overly rely. In simpler terms, we discover that *when LLMs take a wrong turn in a conversation, they get lost and do not recover*.

[Arxiv](https://arxiv.org/abs/2505.06120)