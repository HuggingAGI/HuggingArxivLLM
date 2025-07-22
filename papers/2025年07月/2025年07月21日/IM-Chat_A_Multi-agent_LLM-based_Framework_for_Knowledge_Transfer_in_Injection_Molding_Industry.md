# IM-Chat：面向注塑行业的多智能体LLM知识转移框架

发布时间：2025年07月21日

`LLM应用` `制造业` `知识管理`

> IM-Chat: A Multi-agent LLM-based Framework for Knowledge Transfer in Injection Molding Industry

# 摘要

> 注塑成型行业在保留和转移现场知识方面面临关键挑战，尤其是随着经验丰富的工人退休以及多语言障碍阻碍了有效沟通。本研究介绍了IM-Chat，这是一个基于大型语言模型（LLMs）的多智能体框架，旨在促进注塑成型中的知识转移。IM-Chat整合了有限的文档知识（例如故障排除表、手册）以及通过数据驱动的过程条件生成器建模的大量现场数据，该生成器可以根据环境输入（如温度和湿度）推断出最优的制造设置，从而实现强大且情境感知的任务解决。通过采用基于检索增强生成（RAG）策略和工具调用智能体的模块化架构，IM-Chat确保了适应性，而无需进行微调。GPT-4o、GPT-4o-mini和GPT-3.5-turbo在100个单工具任务和60个混合任务上的性能由领域专家使用专注于相关性和正确性的10分评分标准进行了评估，并通过基于GPT-4o的领域自适应指令提示引导的自动化评估进一步补充。评估结果表明，能力更强的模型在复杂、工具集成的场景中往往能实现更高的准确性。总体而言，这些发现证明了多智能体LLM系统在工业知识工作流中的可行性，并确立了IM-Chat作为制造中AI辅助决策支持的可扩展且通用方法。


> The injection molding industry faces critical challenges in preserving and transferring field knowledge, particularly as experienced workers retire and multilingual barriers hinder effective communication. This study introduces IM-Chat, a multi-agent framework based on large language models (LLMs), designed to facilitate knowledge transfer in injection molding. IM-Chat integrates both limited documented knowledge (e.g., troubleshooting tables, manuals) and extensive field data modeled through a data-driven process condition generator that infers optimal manufacturing settings from environmental inputs such as temperature and humidity, enabling robust and context-aware task resolution. By adopting a retrieval-augmented generation (RAG) strategy and tool-calling agents within a modular architecture, IM-Chat ensures adaptability without the need for fine-tuning. Performance was assessed across 100 single-tool and 60 hybrid tasks for GPT-4o, GPT-4o-mini, and GPT-3.5-turbo by domain experts using a 10-point rubric focused on relevance and correctness, and was further supplemented by automated evaluation using GPT-4o guided by a domain-adapted instruction prompt. The evaluation results indicate that more capable models tend to achieve higher accuracy, particularly in complex, tool-integrated scenarios. Overall, these findings demonstrate the viability of multi-agent LLM systems for industrial knowledge workflows and establish IM-Chat as a scalable and generalizable approach to AI-assisted decision support in manufacturing.

[Arxiv](https://arxiv.org/abs/2507.15268)