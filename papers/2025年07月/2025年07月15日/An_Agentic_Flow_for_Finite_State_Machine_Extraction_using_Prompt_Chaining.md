# 基于提示链的有限状态机提取流程

发布时间：2025年07月15日

`Agent

理由：这篇论文主要介绍了FlowFSM，一个结合大型语言模型（LLMs）、提示链和链式推理的智能体框架，用于从RFC文档中提取有限状态机（FSMs）。论文的重点在于智能体的设计和应用，展示其在协议分析和FSM推理中的价值，因此属于Agent类别。` `网络安全` `协议分析`

> An Agentic Flow for Finite State Machine Extraction using Prompt Chaining

# 摘要

> 有限状态机（FSMs）是建模网络协议操作逻辑的关键工具，支持验证、分析和漏洞挖掘。然而，现有FSM提取技术在可扩展性、覆盖范围和自然语言规范的清晰度方面存在局限。本文提出了一种名为FlowFSM的创新智能体框架，它结合大型语言模型（LLMs）、提示链和链式推理，能够从原始RFC文档中精准提取FSMs。通过连接智能体输出，FlowFSM系统性地处理协议规范，识别状态转换，并构建结构化的规则手册。在FTP和RTSP协议上的实验表明，FlowFSM不仅实现了高精度的FSM提取，还显著减少了幻觉转换，展现出巨大潜力。我们的研究结果凸显了基于智能体的LLM系统在推动协议分析和FSM推理方面的价值，这将为网络安全和逆向工程应用带来重要突破。

> Finite-State Machines (FSMs) are critical for modeling the operational logic of network protocols, enabling verification, analysis, and vulnerability discovery. However, existing FSM extraction techniques face limitations such as scalability, incomplete coverage, and ambiguity in natural language specifications. In this paper, we propose FlowFSM, a novel agentic framework that leverages Large Language Models (LLMs) combined with prompt chaining and chain-of-thought reasoning to extract accurate FSMs from raw RFC documents. FlowFSM systematically processes protocol specifications, identifies state transitions, and constructs structured rule-books by chaining agent outputs. Experimental evaluation across FTP and RTSP protocols demonstrates that FlowFSM achieves high extraction precision while minimizing hallucinated transitions, showing promising results. Our findings highlight the potential of agent-based LLM systems in the advancement of protocol analysis and FSM inference for cybersecurity and reverse engineering applications.

[Arxiv](https://arxiv.org/abs/2507.11222)