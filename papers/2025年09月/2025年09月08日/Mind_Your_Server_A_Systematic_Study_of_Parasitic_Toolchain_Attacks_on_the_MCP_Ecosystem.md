# 警惕你的服务器：MCP生态系统寄生性工具链攻击的系统性研究

发布时间：2025年09月08日

`LLM应用` `基础理论`

> Mind Your Server: A Systematic Study of Parasitic Toolchain Attacks on the MCP Ecosystem

# 摘要

> 大型语言模型（LLMs）正通过模型上下文协议（MCP）与外部系统深度集成。这一协议不仅标准化了工具调用，更迅速成为LLM驱动应用的核心支柱。然而，这种功能增强的范式也带来了根本性的安全转变：LLMs从被动信息处理器蜕变为任务导向工具链的自主编排者，既扩大了攻击面，也将对抗目标从操纵单个输出升级为劫持整个执行流。

本文揭示了一类新型攻击——寄生工具链攻击，其具体表现为MCP意外隐私泄露（MCP-UPD）。此类攻击无需与受害者直接交互，攻击者只需将恶意指令植入LLMs在合法任务中访问的外部数据源即可。恶意逻辑会渗透到工具链中，并分三个阶段展开：寄生摄入、隐私收集与隐私泄露，最终实现隐私数据的隐秘窃取。

根本原因分析显示，MCP缺乏上下文-工具隔离机制和最小权限执行原则，导致恶意指令得以不受限制地传播至敏感工具调用。为评估风险严重性，我们设计了MCP-SEC，并对MCP生态系统开展了首次大规模安全普查，分析了1360台服务器上的12230个工具。研究结果表明，MCP生态系统中存在大量可利用的漏洞和多样的攻击手段，这凸显了MCP平台的系统性风险，以及在LLM集成环境中构建防御机制的迫切性。

> Large language models (LLMs) are increasingly integrated with external systems through the Model Context Protocol (MCP), which standardizes tool invocation and has rapidly become a backbone for LLM-powered applications. While this paradigm enhances functionality, it also introduces a fundamental security shift: LLMs transition from passive information processors to autonomous orchestrators of task-oriented toolchains, expanding the attack surface, elevating adversarial goals from manipulating single outputs to hijacking entire execution flows. In this paper, we reveal a new class of attacks, Parasitic Toolchain Attacks, instantiated as MCP Unintended Privacy Disclosure (MCP-UPD). These attacks require no direct victim interaction; instead, adversaries embed malicious instructions into external data sources that LLMs access during legitimate tasks. The malicious logic infiltrates the toolchain and unfolds in three phases: Parasitic Ingestion, Privacy Collection, and Privacy Disclosure, culminating in stealthy exfiltration of private data. Our root cause analysis reveals that MCP lacks both context-tool isolation and least-privilege enforcement, enabling adversarial instructions to propagate unchecked into sensitive tool invocations. To assess the severity, we design MCP-SEC and conduct the first large-scale security census of the MCP ecosystem, analyzing 12,230 tools across 1,360 servers. Our findings show that the MCP ecosystem is rife with exploitable gadgets and diverse attack methods, underscoring systemic risks in MCP platforms and the urgent need for defense mechanisms in LLM-integrated environments.

[Arxiv](https://arxiv.org/abs/2509.06572)