# 具身推理：用工具赋能大型语言模型，开启深度研究之旅

发布时间：2025年02月06日

`Agent` `人工智能` `知识图谱`

> Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research

# 摘要

> 我们提出了一种名为智能体推理（Agentic Reasoning）的新框架，通过整合外部工具代理来增强大型语言模型（LLM）的推理能力。与传统仅依赖内部推理的LLM推理方法不同，智能体推理框架结合了网络搜索、代码执行和结构化推理上下文记忆，能够有效解决需要深度研究和多步逻辑推理的复杂问题。我们的框架引入了心智图代理（Mind Map agent），该代理通过构建结构化知识图谱追踪逻辑关系，从而提升演绎推理能力。此外，整合网络搜索和代码执行代理实现了实时信息检索和计算分析，进一步提升了推理准确性和决策能力。在博士水平科学推理任务（GPQA）和特定领域的深度研究任务上进行的评估表明，我们的方法显著优于现有模型，包括领先的检索增强生成（RAG）系统和闭源LLM。此外，我们的实验结果表明，智能体推理框架在专家级知识整合、推理时扩展性和结构化问题解决方面均有显著提升。代码地址：https://github.com/theworldofagents/Agentic-Reasoning。

> We introduce Agentic Reasoning, a framework that enhances large language model (LLM) reasoning by integrating external tool-using agents. Unlike conventional LLM-based reasoning approaches, which rely solely on internal inference, Agentic Reasoning dynamically engages web search, code execution, and structured reasoning-context memory to solve complex problems requiring deep research and multi-step logical deduction. Our framework introduces the Mind Map agent, which constructs a structured knowledge graph to track logical relationships, improving deductive reasoning. Additionally, the integration of web-search and coding agents enables real-time retrieval and computational analysis, enhancing reasoning accuracy and decision-making. Evaluations on PhD-level scientific reasoning (GPQA) and domain-specific deep research tasks demonstrate that our approach significantly outperforms existing models, including leading retrieval-augmented generation (RAG) systems and closed-source LLMs. Moreover, our results indicate that agentic reasoning improves expert-level knowledge synthesis, test-time scalability, and structured problem-solving. The code is at: https://github.com/theworldofagents/Agentic-Reasoning.

[Arxiv](https://arxiv.org/abs/2502.04644)