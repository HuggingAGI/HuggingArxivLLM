# # 真实世界中的 LLM 部署全景图：一项实证研究

发布时间：2025年05月05日

`其他` `网络安全` `人工智能`

> Unveiling the Landscape of LLM Deployment in the Wild: An Empirical Study

# 摘要

> # 背景与目标
大型语言模型（LLMs）正通过开源和商业框架快速普及，使个人和组织能够轻松部署先进AI能力。然而，当前LLM服务普遍面临安全风险，主要源于默认配置不安全和误配置问题。本研究旨在通过大规模实证分析，全面揭示野生环境中公开LLM部署的现状，重点关注服务普及、暴露特征、系统漏洞及风险。

# 方法与发现
我们对互联网进行了全面扫描，识别出基于15种主流框架的320,102个公开LLM服务实例。通过对158个API端点的深入分析，我们发现：
- 服务端点普遍存在不安全协议使用、TLS配置不当和关键操作无身份验证等问题
- 模型泄露、系统信息泄露和未授权访问等安全风险广泛存在
- 当前部署实践中存在诸多系统性问题，亟需改进

# 结论与建议
研究发现，当前公开LLM部署面临严重安全隐患和配置缺陷，易遭受滥用、模型窃取、资源劫持和远程攻击。我们建议：
1. 采用安全默认配置框架
2. 加强身份验证和访问控制
3. 完善部署实践和运营标准
4. 提升开发者和运维人员的安全意识

这些改进措施对于保障日益增长的自主托管LLM生态系统的安全性至关重要。

> Background: Large language models (LLMs) are increasingly deployed via open-source and commercial frameworks, enabling individuals and organizations to self-host advanced AI capabilities. However, insecure defaults and misconfigurations often expose LLM services to the public Internet, posing significant security and system engineering risks. Aims: This study aims to unveil the current landscape of public-facing LLM deployments in the wild through a large-scale empirical study, focusing on service prevalence, exposure characteristics, systemic vulnerabilities, and associated risks. Method: We conducted an Internet-wide measurement to identify public-facing LLM deployments across 15 frameworks, discovering 320,102 services. We extracted 158 unique API endpoints, grouped into 12 functional categories based on capabilities and security risks. We further analyzed configurations, authentication practices, and geographic distributions, revealing deployment trends and systemic issues in real-world LLM system engineering. Results: Our study shows that public LLM deployments are rapidly growing but often insecure. Among all endpoints, we observe widespread use of insecure protocols, poor TLS configurations, and unauthenticated access to critical operations. Security risks, including model disclosure, system leakage, and unauthorized access, are pervasive, highlighting the need for secure-by-default frameworks and stronger deployment practices. Conclusions: Public-facing LLM deployments suffer from widespread security and configuration flaws, exposing services to misuse, model theft, resource hijacking, and remote exploitation. Strengthening default security, deployment practices, and operational standards is critical for the growing self-hosted LLM ecosystem.

[Arxiv](https://arxiv.org/abs/2505.02502)