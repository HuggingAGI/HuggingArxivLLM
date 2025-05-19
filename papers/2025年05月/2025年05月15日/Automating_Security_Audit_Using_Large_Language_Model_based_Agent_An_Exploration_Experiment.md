# # 使用 LLM 代理实现安全审计自动化：一项探索实验

发布时间：2025年05月15日

`LLM应用

理由：该论文探讨了大型语言模型（LLMs）在安全审计任务中的应用，特别是利用LLMs作为自主代理来执行密码策略合规性审计。这属于将LLMs应用于具体任务的范畴，因此归类为LLM应用。` `信息安全` `人工智能`

> Automating Security Audit Using Large Language Model based Agent: An Exploration Experiment

# 摘要

> 在当今快速变迁的数字环境中，企业面临着持续的压力，需要确保其系统的安全性。安全审计通过确保政策到位、控制措施落实以及识别网络安全风险缓解的缺口，有助于维护强大的安全态势。然而，传统的安全审计往往需要手动操作，耗时耗力，成本高昂。

本文探讨了开发一个框架的可能性，该框架利用大型语言模型（LLMs）作为自主代理，执行部分安全审计任务，具体针对Windows操作系统的密码策略合规性进行现场审计。通过使用GPT-4与Langchain进行探索性实验，该代理能够准确识别密码策略违规，并执行审计任务，效率似乎高于传统的手动审计。

尽管在复杂多变的环境中，该框架在操作一致性方面可能存在局限性，但它为扩展到实时威胁监控和合规性检查提供了可能性。

> In the current rapidly changing digital environment, businesses are under constant stress to ensure that their systems are secured. Security audits help to maintain a strong security posture by ensuring that policies are in place, controls are implemented, gaps are identified for cybersecurity risks mitigation. However, audits are usually manual, requiring much time and costs. This paper looks at the possibility of developing a framework to leverage Large Language Models (LLMs) as an autonomous agent to execute part of the security audit, namely with the field audit. password policy compliance for Windows operating system. Through the conduct of an exploration experiment of using GPT-4 with Langchain, the agent executed the audit tasks by accurately flagging password policy violations and appeared to be more efficient than traditional manual audits. Despite its potential limitations in operational consistency in complex and dynamic environment, the framework suggests possibilities to extend further to real-time threat monitoring and compliance checks.

[Arxiv](https://arxiv.org/abs/2505.10732)