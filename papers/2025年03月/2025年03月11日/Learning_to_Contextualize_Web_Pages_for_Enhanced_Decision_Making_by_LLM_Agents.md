# LLM智能体通过网页情境化学习提升决策能力

发布时间：2025年03月11日

`LLM应用` `网络自动化` `网页处理`

> Learning to Contextualize Web Pages for Enhanced Decision Making by LLM Agents

# 摘要

> 大型语言模型（LLMs）的最新进展激发了人们对开发基于LLM的网络任务自动化代理的浓厚兴趣。然而，这些代理在处理真实网站的简单任务时仍面临挑战，主要源于其对复杂网页结构的理解和处理能力有限。为此，我们提出了LCoW框架，专注于将复杂网页结构转化为更易理解的形式，从而显著提升LLM代理的决策能力。LCoW通过将网页理解与决策过程解耦，训练一个独立的上下文化模块，将复杂的网页内容转化为易于处理的格式，供决策代理使用。实验结果表明，LCoW能够与不同规模的LLM代理无缝结合，显著提升其在网络自动化任务中的决策能力。具体而言，LCoW将闭源LLMs（如Gemini-1.5-flash、GPT-4o、Claude-3.5-Sonnet）的成功率平均提升了15.6%，并在WorkArena基准测试中，开源语言模型（如Llama-3.1-8B、Llama-3.1-70B）的成功率平均提高了23.7%。此外，配备LCoW的Gemini-1.5-flash代理在WebShop基准测试中表现卓越，超越了人类专家的水平。相关代码和材料可在我们的项目页面获取：https://lcowiclr2025.github.io。

> Recent advances in large language models (LLMs) have led to a growing interest in developing LLM-based agents for automating web tasks. However, these agents often struggle with even simple tasks on real-world websites due to their limited capability to understand and process complex web page structures. In this work, we introduce LCoW, a framework for Learning language models to Contextualize complex Web pages into a more comprehensible form, thereby enhancing decision making by LLM agents. LCoW decouples web page understanding from decision making by training a separate contextualization module to transform complex web pages into comprehensible format, which are then utilized by the decision-making agent. We demonstrate that our contextualization module effectively integrates with LLM agents of various scales to significantly enhance their decision-making capabilities in web automation tasks. Notably, LCoW improves the success rates of closed-source LLMs (e.g., Gemini-1.5-flash, GPT-4o, Claude-3.5-Sonnet) by an average of 15.6%, and demonstrates a 23.7% average improvement in success rates for open-source LMs (e.g., Llama-3.1-8B, Llama-3.1-70B) on the WorkArena benchmark. Moreover, the Gemini-1.5-flash agent with LCoW achieves state-of-the-art results on the WebShop benchmark, outperforming human experts. The relevant code materials are available at our project page: https://lcowiclr2025.github.io.

[Arxiv](https://arxiv.org/abs/2503.10689)