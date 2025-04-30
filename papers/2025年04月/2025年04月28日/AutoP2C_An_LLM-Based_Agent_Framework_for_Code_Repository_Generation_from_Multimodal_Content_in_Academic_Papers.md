# AutoP2C：基于LLM的代理框架，从学术论文中的多模态内容自动生成代码库

发布时间：2025年04月28日

`LLM应用` `软件工程` `人工智能`

> AutoP2C: An LLM-Based Agent Framework for Code Repository Generation from Multimodal Content in Academic Papers

# 摘要

> 机器学习研究通过学术论文传播，这些论文包含丰富的多模态内容，如文本、图表和表格结果。然而，将这些内容转化为可执行代码仍具挑战性，且耗时费力，需要深厚的专业知识。我们推出“Paper-to-Code”（P2C）任务，旨在将科学出版物的多模态内容转化为完整的代码仓库，超越现有仅将文本转为代码片段的方法。为实现这一目标，我们开发了AutoP2C，一个基于大型语言模型的多智能体框架，能够处理论文中的文本和视觉内容，生成完整的代码仓库。AutoP2C包含四个阶段：从现有代码库提取蓝图、整合多模态信息、分层任务分解生成代码，以及迭代反馈调试。在八篇论文的基准测试中，AutoP2C成功为全部八篇生成代码，而其他工具只能处理一篇。代码仓库可访问https://github.com/shoushouyu/Automated-Paper-to-Code。

> Machine Learning (ML) research is spread through academic papers featuring rich multimodal content, including text, diagrams, and tabular results. However, translating these multimodal elements into executable code remains a challenging and time-consuming process that requires substantial ML expertise. We introduce ``Paper-to-Code'' (P2C), a novel task that transforms the multimodal content of scientific publications into fully executable code repositories, which extends beyond the existing formulation of code generation that merely converts textual descriptions into isolated code snippets. To automate the P2C process, we propose AutoP2C, a multi-agent framework based on large language models that processes both textual and visual content from research papers to generate complete code repositories. Specifically, AutoP2C contains four stages: (1) repository blueprint extraction from established codebases, (2) multimodal content parsing that integrates information from text, equations, and figures, (3) hierarchical task decomposition for structured code generation, and (4) iterative feedback-driven debugging to ensure functionality and performance. Evaluation on a benchmark of eight research papers demonstrates the effectiveness of AutoP2C, which can successfully generate executable code repositories for all eight papers, while OpenAI-o1 or DeepSeek-R1 can only produce runnable code for one paper. The code is available at https://github.com/shoushouyu/Automated-Paper-to-Code.

[Arxiv](https://arxiv.org/abs/2504.20115)