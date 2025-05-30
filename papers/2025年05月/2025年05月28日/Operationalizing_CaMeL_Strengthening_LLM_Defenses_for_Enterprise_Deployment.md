# # 将 CaMeL 付诸实践：提升企业级 LLM 部署的安全防护能力

发布时间：2025年05月28日

`LLM应用` `企业安全`

> Operationalizing CaMeL: Strengthening LLM Defenses for Enterprise Deployment

# 摘要

> CaMeL（机器学习能力）引入了一种基于能力的沙盒，有效缓解了大型语言模型（LLM）代理中的提示注入攻击。然而，CaMeL在假设用户提示可信的同时，忽略了侧信道问题，并因双LLM设计导致性能权衡。本研究识别这些问题，并提出四项工程改进，以扩展CaMeL的威胁覆盖范围和运营实用性。具体包括：（1）对初始输入的提示筛选，（2）检测指令泄露的输出审核，（3）分层风险访问模型以平衡可用性和控制，（4）一种经过验证的中间语言以提供正式保证。这些升级使CaMeL与企业安全的最佳实践保持一致，支持更广泛的部署。

> CaMeL (Capabilities for Machine Learning) introduces a capability-based sandbox to mitigate prompt injection attacks in large language model (LLM) agents. While effective, CaMeL assumes a trusted user prompt, omits side-channel concerns, and incurs performance tradeoffs due to its dual-LLM design. This response identifies these issues and proposes engineering improvements to expand CaMeL's threat coverage and operational usability. We introduce: (1) prompt screening for initial inputs, (2) output auditing to detect instruction leakage, (3) a tiered-risk access model to balance usability and control, and (4) a verified intermediate language for formal guarantees. Together, these upgrades align CaMeL with best practices in enterprise security and support scalable deployment.

[Arxiv](https://arxiv.org/abs/2505.22852)