# ACEBench: 工具学习中的赛点花落谁家？

发布时间：2025年01月22日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在决策和推理方面的应用，特别是如何评估LLM在复杂场景中的函数调用能力。论文提出了一个综合评估系统ACEBench，用于评估LLM在不同场景下的表现，包括普通、特殊和代理场景。这些内容主要涉及LLM在实际应用中的表现和评估方法，因此归类为“LLM应用”。` `人工智能` `评估系统`

> ACEBench: Who Wins the Match Point in Tool Learning?

# 摘要

> 大型语言模型（LLMs）在决策和推理方面展现了巨大潜力，尤其是在结合工具解决复杂问题时。然而，现有评估系统在评估LLM函数调用能力方面存在局限：（1）评估场景有限，缺乏真实多轮对话中的评估；（2）评估维度狭窄，缺少对细粒度函数调用的详细评估；（3）依赖LLMs或真实API执行，带来显著开销。为此，我们提出了ACEBench综合评估系统，涵盖广泛的函数调用场景，并将其分为普通、特殊和代理三类。普通评估基本场景中的函数调用；特殊评估指令模糊或不完整场景中的函数调用；代理引入多代理交互，模拟真实多轮交互中的函数调用评估。我们在ACEBench上进行了广泛实验，深入分析各类LLMs，并对不同数据类型的错误原因进行了细粒度分析。

> Large language models (LLMs) have demonstrated significant potential in decision-making and reasoning, especially when combined with various tools to effectively solve complex problems. However, existing evaluation systems for assessing LLM function calling capabilities have several limitations: (1) limited evaluation scenarios, lacking assessments in real multi-turn dialogue contexts; (2) narrow evaluation dimensions, lacking detailed assessments for fine-grained function calls; (3) relying on LLMs or real API executions for result evaluation, which introduces significant overhead. To address these issues, we propose a comprehensive evaluation system named ACEBench. This system is meticulously designed to encompass a wide spectrum of function calling scenarios. Moreover, it categorizes these scenarios into three primary types according to the evaluation methodology: Normal, Special, and Agent. Normal evaluates function calls in basic scenarios; Special evaluates function calls in scenarios with vague or incomplete instructions; Agent introduces multi-agent interactions to simulate function calling evaluation in real-world multi-turn interactions. We conducted extensive experiments on ACEBench, analyzing various LLMs in-depth and performing a more granular analysis of error causes across different data types.

[Arxiv](https://arxiv.org/abs/2501.12851)