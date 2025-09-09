# SasAgent：面向小角散射数据分析的多智能体AI系统

发布时间：2025年09月03日

`Agent` `基础理论`

> SasAgent: Multi-Agent AI System for Small-Angle Scattering Data Analysis

# 摘要

> 我们推出了SasAgent——一个由大型语言模型（LLMs）驱动的多智能体AI系统，它借助SasView软件工具实现小角散射（SAS）数据分析的自动化，并支持用户通过文本输入进行交互。SasAgent的核心是协调智能体，它负责解读用户指令并将任务分配给三个专业智能体，分别处理散射长度密度（SLD）计算、合成数据生成和实验数据拟合。这些专业智能体借助LLM适配工具高效完成任务，包括模型数据工具、检索增强生成（RAG）文档工具、凸点拟合工具和SLD计算器工具，这些工具均源自SasView Python库。基于Gradio的用户友好界面进一步提升了系统的易用性。通过多个示例，我们验证了SasAgent能够准确解读复杂指令、计算SLD、生成可靠散射数据，并高精度拟合实验数据集。这项研究充分证明，LLM驱动的AI系统在简化科学工作流程、提升SAS研究自动化水平方面具有巨大潜力。

> We introduce SasAgent, a multi-agent AI system powered by large language models (LLMs) that automates small-angle scattering (SAS) data analysis by leveraging tools from the SasView software and enables user interaction via text input. SasAgent features a coordinator agent that interprets user prompts and delegates tasks to three specialized agents for scattering length density (SLD) calculation, synthetic data generation, and experimental data fitting. These agents utilize LLM-friendly tools to execute tasks efficiently. These tools, including the model data tool, Retrieval-Augmented Generation (RAG) documentation tool, bump fitting tool, and SLD calculator tool, are derived from the SasView Python library. A user-friendly Gradio-based interface enhances user accessibility. Through diverse examples, we demonstrate SasAgent's ability to interpret complex prompts, calculate SLDs, generate accurate scattering data, and fit experimental datasets with high precision. This work showcases the potential of LLM-driven AI systems to streamline scientific workflows and enhance automation in SAS research.

[Arxiv](https://arxiv.org/abs/2509.05363)