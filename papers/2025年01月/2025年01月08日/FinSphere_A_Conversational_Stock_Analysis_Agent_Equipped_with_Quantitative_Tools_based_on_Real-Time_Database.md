# FinSphere: 基于实时数据库的量化工具驱动的对话式股票分析智能体

发布时间：2025年01月08日

`Agent

理由：这篇论文介绍了一个名为FinSphere的对话式股票分析代理，该代理能够根据用户查询生成高质量的股票分析报告。论文的重点在于开发一个能够执行特定任务（股票分析）的AI代理，并提出了相关的数据集和评估框架来支持该代理的功能。因此，这篇论文主要属于Agent分类。` `股票分析`

> FinSphere: A Conversational Stock Analysis Agent Equipped with Quantitative Tools based on Real-Time Database

# 摘要

> 当前金融领域的LLMs存在两大瓶颈：一是股票分析深度不足，难以生成专业级洞察；二是缺乏客观的评估指标来衡量股票分析报告的质量。为此，本文推出了FinSphere，一个对话式股票分析代理，并带来了三大创新：（1）Stocksis，一个由行业专家精心打造的数据集，旨在提升LLMs的股票分析能力；（2）AnalyScore，一个系统化的评估框架，用于衡量股票分析质量；（3）FinSphere，一个能够根据用户查询生成高质量股票分析报告的AI代理。实验证明，FinSphere在性能上超越了通用和特定领域的LLMs，以及现有的基于代理的系统，即使这些系统增强了实时数据访问和少量样本指导。集成框架结合了实时数据流、量化工具和指令调优的LLM，显著提升了现实世界股票分析的分析质量和实际应用性。

> Current financial Large Language Models (LLMs) struggle with two critical limitations: a lack of depth in stock analysis, which impedes their ability to generate professional-grade insights, and the absence of objective evaluation metrics to assess the quality of stock analysis reports. To address these challenges, this paper introduces FinSphere, a conversational stock analysis agent, along with three major contributions: (1) Stocksis, a dataset curated by industry experts to enhance LLMs' stock analysis capabilities, (2) AnalyScore, a systematic evaluation framework for assessing stock analysis quality, and (3) FinSphere, an AI agent that can generate high-quality stock analysis reports in response to user queries. Experiments demonstrate that FinSphere achieves superior performance compared to both general and domain-specific LLMs, as well as existing agent-based systems, even when they are enhanced with real-time data access and few-shot guidance. The integrated framework, which combines real-time data feeds, quantitative tools, and an instruction-tuned LLM, yields substantial improvements in both analytical quality and practical applicability for real-world stock analysis.

[Arxiv](https://arxiv.org/abs/2501.12399)