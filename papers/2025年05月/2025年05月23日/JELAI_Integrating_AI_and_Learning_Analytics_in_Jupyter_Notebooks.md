# # JELAI：在Jupyter笔记本中融合AI与学习分析

发布时间：2025年05月23日

`LLM应用` `AI辅导系统`

> JELAI: Integrating AI and Learning Analytics in Jupyter Notebooks

# 摘要

> 生成式AI在教育领域展现出巨大潜力，但目前仍面临两大挑战：缺乏扎实的教学法基础，以及忽视学生学习环境的背景。此外，在真实学习场景中研究学生与这些工具的互动关系仍然充满挑战。为解决这些问题，我们推出JELAI——一个开源平台架构，旨在将精细的学习分析（LA）与基于大语言模型（LLM）的辅导系统无缝集成到Jupyter Notebook环境中。

JELAI采用模块化、容器化设计，集成了用于遥测和聊天的JupyterLab扩展，并通过中央中间件实现学习分析处理和基于上下文的LLM提示增强。这种创新架构能够捕获集成的代码交互和聊天数据，从而支持实时、基于上下文的AI支架功能，并深入研究学生行为模式。

我们详细阐述了JELAI的设计与实现，并通过系统性能基准测试和两个概念验证用例，充分展示了其在记录多模态数据、分析求助模式以及支持AI配置的A/B测试方面的强大功能。JELAI的核心价值在于其技术框架，为研究人员和教育者提供了一个灵活的工具，助力他们在广泛使用的Jupyter生态系统中开发、部署和研究基于学习分析的AI辅导系统。

> Generative AI offers potential for educational support, but often lacks pedagogical grounding and awareness of the student's learning context. Furthermore, researching student interactions with these tools within authentic learning environments remains challenging. To address this, we present JELAI, an open-source platform architecture designed to integrate fine-grained Learning Analytics (LA) with Large Language Model (LLM)-based tutoring directly within a Jupyter Notebook environment. JELAI employs a modular, containerized design featuring JupyterLab extensions for telemetry and chat, alongside a central middleware handling LA processing and context-aware LLM prompt enrichment. This architecture enables the capture of integrated code interaction and chat data, facilitating real-time, context-sensitive AI scaffolding and research into student behaviour. We describe the system's design, implementation, and demonstrate its feasibility through system performance benchmarks and two proof-of-concept use cases illustrating its capabilities for logging multi-modal data, analysing help-seeking patterns, and supporting A/B testing of AI configurations. JELAI's primary contribution is its technical framework, providing a flexible tool for researchers and educators to develop, deploy, and study LA-informed AI tutoring within the widely used Jupyter ecosystem.

[Arxiv](https://arxiv.org/abs/2505.17593)