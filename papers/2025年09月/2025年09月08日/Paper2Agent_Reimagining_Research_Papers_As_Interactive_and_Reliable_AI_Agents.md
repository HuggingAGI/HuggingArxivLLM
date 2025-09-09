# Paper2Agent：让研究论文化身为交互可靠的AI智能体

发布时间：2025年09月08日

`Agent` `医疗健康`

> Paper2Agent: Reimagining Research Papers As Interactive and Reliable AI Agents

# 摘要

> 我们推出Paper2Agent——一个能将研究论文自动转化为AI智能体的框架。它将研究成果从被动的静态成果转变为主动系统，加速下游应用、推广与新发现。传统研究论文中，读者往往需耗费大量精力理解并迁移论文中的代码、数据和方法，形成知识传播与复用的壁垒。而Paper2Agent通过将论文自动转化为智能研究助手，轻松化解这一难题。该框架借助多智能体系统分析论文及相关代码库，构建模型上下文协议（MCP）服务器，随后通过迭代生成和运行测试，不断优化并提升MCP的稳健性。这些论文MCP可灵活对接聊天智能体（如Claude Code），支持用户通过自然语言处理复杂科学问题，同时调用原始论文中的工具与工作流。我们通过深入案例研究，验证了Paper2Agent在构建可靠、高效论文智能体方面的出色表现：它已成功创建基于AlphaGenome的基因组变异解读智能体，以及基于ScanPy和TISSUE的单细胞与空间转录组学分析智能体。结果显示，这些智能体不仅能复现原论文成果，还能准确响应新的用户指令。通过将静态论文转化为动态交互式AI智能体，Paper2Agent开创了知识传播新范式，也为AI协作者的协作生态奠定了基础。

> We introduce Paper2Agent, an automated framework that converts research papers into AI agents. Paper2Agent transforms research output from passive artifacts into active systems that can accelerate downstream use, adoption, and discovery. Conventional research papers require readers to invest substantial effort to understand and adapt a paper's code, data, and methods to their own work, creating barriers to dissemination and reuse. Paper2Agent addresses this challenge by automatically converting a paper into an AI agent that acts as a knowledgeable research assistant. It systematically analyzes the paper and the associated codebase using multiple agents to construct a Model Context Protocol (MCP) server, then iteratively generates and runs tests to refine and robustify the resulting MCP. These paper MCPs can then be flexibly connected to a chat agent (e.g. Claude Code) to carry out complex scientific queries through natural language while invoking tools and workflows from the original paper. We demonstrate Paper2Agent's effectiveness in creating reliable and capable paper agents through in-depth case studies. Paper2Agent created an agent that leverages AlphaGenome to interpret genomic variants and agents based on ScanPy and TISSUE to carry out single-cell and spatial transcriptomics analyses. We validate that these paper agents can reproduce the original paper's results and can correctly carry out novel user queries. By turning static papers into dynamic, interactive AI agents, Paper2Agent introduces a new paradigm for knowledge dissemination and a foundation for the collaborative ecosystem of AI co-scientists.

[Arxiv](https://arxiv.org/abs/2509.06917)