# 迈向PDDL规划副驾驶

发布时间：2025年09月16日

`Agent` `基础理论`

> Toward PDDL Planning Copilot

# 摘要

> 大型语言模型（LLMs）正日益成为能执行复杂任务的自主智能体，但它们在独立进行可靠的长期规划方面能力不足。为此，本文提出规划副驾驶（Planning Copilot）——一种集成多类规划工具、支持用户以自然语言指令调用的聊天机器人，以填补这一空白。该工具依托模型上下文协议（MCP）——一种近期研发的LLMs与外部工具及系统连接标准，支持使用任何兼容MCP的LLM，且无需特定领域微调。规划副驾驶可处理多种常见规划任务，包括检查规划问题语法、选择适配规划器、调用规划器、验证生成计划及模拟计划执行。我们基于三个开源LLM对其任务执行能力进行实证评估，结果显示，相较于未配备规划工具的同类LLM，规划副驾驶性能大幅提升。此外，我们还将该工具与最新商用LLM Chat GPT-5进行小规模定性对比，发现即便所依赖的LLM规模小得多，规划副驾驶仍显著优于GPT-5。这意味着，专用规划工具或为提升LLMs规划任务能力的有效途径。

> Large Language Models (LLMs) are increasingly being used as autonomous agents capable of performing complicated tasks. However, they lack the ability to perform reliable long-horizon planning on their own. This paper bridges this gap by introducing the Planning Copilot, a chatbot that integrates multiple planning tools and allows users to invoke them through instructions in natural language. The Planning Copilot leverages the Model Context Protocol (MCP), a recently developed standard for connecting LLMs with external tools and systems. This approach allows using any LLM that supports MCP without domain-specific fine-tuning. Our Planning Copilot supports common planning tasks such as checking the syntax of planning problems, selecting an appropriate planner, calling it, validating the plan it generates, and simulating their execution. We empirically evaluate the ability of our Planning Copilot to perform these tasks using three open-source LLMs. The results show that the Planning Copilot highly outperforms using the same LLMs without the planning tools. We also conducted a limited qualitative comparison of our tool against Chat GPT-5, a very recent commercial LLM. Our results shows that our Planning Copilot significantly outperforms GPT-5 despite relying on a much smaller LLM. This suggests dedicated planning tools may be an effective way to enable LLMs to perform planning tasks.

[Arxiv](https://arxiv.org/abs/2509.12987)