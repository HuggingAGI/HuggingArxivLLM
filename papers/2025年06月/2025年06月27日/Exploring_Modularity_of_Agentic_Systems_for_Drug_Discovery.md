# 探索智能体系统在药物发现中的模块化特性

发布时间：2025年06月27日

`Agent` `药物发现`

> Exploring Modularity of Agentic Systems for Drug Discovery

# 摘要

> 大型语言模型（LLMs）与智能体系统为药物发现与设计注入了创新活力。本研究聚焦于基于LLM的智能体系统在药物发现中的模块化特性，探讨其组成部分（如LLM）是否可互换这一关键问题。通过实证对比，我们发现Claude-3.5-Sonnet、Claude-3.7-Sonnet和GPT-4o在化学与药物发现工具编排中表现更优。尽管代码生成型智能体总体表现更佳，但其优势取决于具体问题与模型选择，提示重工程同样不可或缺。本研究呼吁进一步探索智能体系统模块化，以开发更稳定、更具扩展性的解决方案。

> Large-language models (LLMs) and agentic systems present exciting opportunities to accelerate drug discovery and design. In this study, we critically examine the modularity of LLM-based agentic systems for drug discovery, i.e., whether parts of the agentic system such as the LLM are interchangeable, a topic that has received limited attention in drug discovery applications. We compare the performance of different large language models (LLMs) and the effectiveness of tool-calling agents versus code-generating agents in this domain. Our case study, comparing performance in orchestrating tools for chemistry and drug discovery using an LLM-as-a-judge score, shows that Claude-3.5-Sonnet, Claude-3.7-Sonnet and GPT-4o outperform alternative language models such as Llama-3.1-8B, Llama-3.1-70B, GPT-3.5-Turbo, and Nova-Micro. Although we confirm that code-generating agents outperform the tool-calling ones on average, we show that this is highly question and model dependent. Furthermore, the impact of replacing system prompts is dependent on the specific question asked and the model used, underscoring that -- even in this particular domain -- one cannot just replace language models without considering prompt re-engineering. Our study highlights the necessity of further research into the modularity of agentic systems to enable the development of stable and scalable solutions for real-world problems.

[Arxiv](https://arxiv.org/abs/2506.22189)