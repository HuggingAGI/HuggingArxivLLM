# CyberRAG：一款基于智能体的RAG网络攻击分类与上报工具

发布时间：2025年07月03日

`Agent` `网络安全` `信息安全`

> CyberRAG: An agentic RAG cyber attack classification and reporting tool

# 摘要

> 大型企业的入侵检测和防御系统（IDS/IPS）每小时可能生成数以十万计的警报，给安全分析师带来巨大压力，需要他们具备深厚且迅速发展的专业知识。传统机器学习检测器虽然减少了警报数量，但误报率仍然很高，而标准的单次检索增强生成（RAG）管道经常检索到不相关的上下文，并无法合理解释其预测结果。为了解决这些问题，我们提出了CyberRAG，一个模块化、基于代理的RAG框架，能够实时对网络攻击进行分类、解释和结构化报告。

CyberRAG的核心是一个大型语言模型（LLM）代理，负责协调三部分组件：（i）一组微调后的专用分类器，每个分类器专门针对不同的攻击家族；（ii）用于丰富信息和触发警报的工具适配器；以及（iii）一个迭代检索与推理循环，该循环会持续查询特定领域的知识库，直到证据既相关又自洽。与传统RAG系统不同，CyberRAG采用了代理设计，支持动态控制流和自适应推理。

这种以代理为中心的架构能够自主优化其威胁标签和自然语言解释，从而降低误报率并提高可解释性。该框架完全可扩展：只需添加新的分类器即可支持新的攻击类型，而无需重新训练核心代理。CyberRAG通过语义编排实现了超过94%的每类准确率，并将最终分类准确率提升至94.92%。生成的解释在BERTScore中得分高达0.94，并在基于GPT-4的专家评估中获得4.9/5的高分。

这些结果表明，以代理为中心、专注于专家的RAG方法能够将高检测准确率与可信、适合安全运营中心（SOC）的文本相结合，为实现半自动化的网络安全工作流程提供了一条实用且可扩展的路径。

> Intrusion Detection and Prevention Systems (IDS/IPS) in large enterprises can generate hundreds of thousands of alerts per hour, overwhelming security analysts with logs that demand deep, rapidly evolving domain expertise. Conventional machine-learning detectors trim the alert volume but still yield high false-positive rates, while standard single-pass Retrieval-Augmented Generation (RAG) pipelines often retrieve irrelevant context and fail to justify their predictions. To overcome these shortcomings, we present CyberRAG, a modular, agent-based RAG framework that delivers real-time classification, explanation, and structured reporting for cyber-attacks. A central LLM agent orchestrates (i) a pool of fine-tuned specialized classifiers, each tailored to a distinct attack family; (ii) tool adapters for enrichment and alerting; and (iii) an iterative retrieval-and-reason loop that continuously queries a domain-specific knowledge base until the evidence is both relevant and self-consistent. Unlike traditional RAG systems, CyberRAG embraces an agentic design that enables dynamic control flow and adaptive reasoning. This agent-centric architecture refines its threat labels and natural-language justifications autonomously, reducing false positives and enhancing interpretability. The framework is fully extensible: new attack types can be supported by simply adding a classifier without retraining the core agent. CyberRAG has been evaluated achieving over 94% accuracy per class and pushing final classification accuracy to 94.92% through semantic orchestration. Generated explanations score up to 0.94 in BERTScore and 4.9/5 in GPT-4-based expert evaluation. These results show that agentic, specialist-oriented RAG can pair high detection accuracy with trustworthy, SOC-ready prose, offering a practical and scalable path toward semi-autonomous cyber-defence workflows.

[Arxiv](https://arxiv.org/abs/2507.02424)