# SoK：大型语言模型生成的文本钓鱼攻击活动 生成、特征与检测的端到端分析

发布时间：2025年08月29日

`LLM应用` `基础理论`

> SoK: Large Language Model-Generated Textual Phishing Campaigns End-to-End Analysis of Generation, Characteristics, and Detection

# 摘要

> 网络钓鱼是一种常见的社会工程学攻击手段，攻击者冒充可信实体以窃取信息或诱使受害者执行有害操作。基于文本的钓鱼攻击凭借低成本、可扩展性强和隐蔽性高等优势占据主流，而大型语言模型（LLMs）的出现进一步放大了这些优势，让“钓鱼即服务”攻击可在几分钟内大规模发起。尽管针对LLM辅助钓鱼攻击的研究不断深入，但对钓鱼攻击生命周期的系统性综合研究仍显不足。本文首次对LLM生成的钓鱼攻击进行知识系统化（SoK）梳理，并进行了从生成技术、攻击特征到缓解策略的端到端分析。我们提出了生成-特征-防御（GenCharDef）框架，该框架从方法论、安全视角、数据依赖性和评估实践等维度，系统梳理了LLM生成钓鱼攻击与传统钓鱼攻击的差异。此框架揭示了LLM驱动钓鱼攻击的独特挑战，为理解不断演变的威胁态势及设计更具韧性的防御方案奠定了坚实基础。

> Phishing is a pervasive form of social engineering in which attackers impersonate trusted entities to steal information or induce harmful actions. Text-based phishing dominates for its low cost, scalability, and concealability, advantages recently amplified by large language models (LLMs) that enable ``Phishing-as-a-Service'' attacks at scale within minutes. Despite the growing research into LLM-facilitated phishing attacks, consolidated systematic research on the phishing attack life cycle remains scarce. In this work, we present the first systematization of knowledge (SoK) on LLM-generated phishing, offering an end-to-end analysis that spans generation techniques, attack features, and mitigation strategies. We introduce Generation-Characterization-Defense (GenCharDef), which systematizes the ways in which LLM-generated phishing differs from traditional phishing across methodologies, security perspectives, data dependencies, and evaluation practices. This framework highlights unique challenges of LLM-driven phishing, providing a coherent foundation for understanding the evolving threat landscape and guiding the design of more resilient defenses.

[Arxiv](https://arxiv.org/abs/2508.21457)