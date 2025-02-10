# # 基于LLM的对话数据捕获的动态基准框架

发布时间：2025年02月04日

`LLM应用` `对话系统`

> Dynamic benchmarking framework for LLM-based conversational data capture

# 摘要

> 大型语言模型（LLMs）的快速发展彻底改变了对话代理领域，使其能够支持复杂的机器与人类交互。然而，现有的评估框架往往专注于单一任务，难以捕捉多轮对话的动态特性。本文提出了一种动态基准框架，通过与合成用户交互的方式，全面评估基于LLMs的对话代理。该框架集成了生成式代理模拟，从信息抽取、上下文感知和自适应参与三个关键维度评估性能。通过模拟用户行为的各个方面，我们的研究提供了一种可扩展、自动化且灵活的基准评估方法。在贷款申请的实际案例中，实验结果表明该框架在单次和少量样本抽取条件下均表现优异。特别是，自适应策略能够显著提高数据抽取的准确性，尤其是在处理模糊回应时效果显著。未来，我们将扩展该框架在更广泛领域的适用性，并纳入更多评估指标（例如，对话连贯性、用户参与度）。本研究为评估基于LLMs的对话代理提供了一种结构化且可扩展的方法，为实际应用的部署铺平了道路。

> The rapid evolution of large language models (LLMs) has transformed conversational agents, enabling complex human-machine interactions. However, evaluation frameworks often focus on single tasks, failing to capture the dynamic nature of multi-turn dialogues. This paper introduces a dynamic benchmarking framework to assess LLM-based conversational agents through interactions with synthetic users. The framework integrates generative agent simulation to evaluate performance on key dimensions: information extraction, context awareness, and adaptive engagement. By simulating various aspects of user behavior, our work provides a scalable, automated, and flexible benchmarking approach. Experimental evaluation - within a loan application use case - demonstrates the framework's effectiveness under one-shot and few-shot extraction conditions. Results show that adaptive strategies improve data extraction accuracy, especially when handling ambiguous responses. Future work will extend its applicability to broader domains and incorporate additional metrics (e.g., conversational coherence, user engagement). This study contributes a structured, scalable approach to evaluating LLM-based conversational agents, facilitating real-world deployment.

[Arxiv](https://arxiv.org/abs/2502.04349)