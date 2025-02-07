# LLMSecConfig: 基于LLM的软件容器配置修复方案

发布时间：2025年02月03日

`LLM应用

理由：该论文主要探讨了如何利用大型语言模型（LLMs）结合静态分析工具（SATs）和检索增强生成（RAG）技术，来自动修复容器编排器中的安全配置错误。这属于LLM在实际应用中的使用，特别是结合了RAG技术来增强LLM的能力，因此应归类为“LLM应用”。` `容器编排` `安全配置`

> LLMSecConfig: An LLM-Based Approach for Fixing Software Container Misconfigurations

# 摘要

> # 摘要
容器编排器（COs）中的安全配置错误可能对软件系统构成严重威胁。尽管静态分析工具（SATs）能有效检测这些漏洞，但行业目前缺乏自动修复方案。大型语言模型（LLMs）凭借其代码理解和生成能力，为解决这一问题提供了契机。本研究推出LLMSecConfig，一个创新框架，结合SATs与LLMs，填补了这一空白。我们采用先进的提示技术和检索增强生成（RAG），在保持操作功能的同时，自动修复安全配置错误。对1,000个真实Kubernetes配置的评估显示，成功率达94%，且引入新错误的概率极低。
这一研究为自动化容器安全管理迈出了重要一步，显著减少了配置维护的手动工作量。

> Security misconfigurations in Container Orchestrators (COs) can pose serious threats to software systems. While Static Analysis Tools (SATs) can effectively detect these security vulnerabilities, the industry currently lacks automated solutions capable of fixing these misconfigurations. The emergence of Large Language Models (LLMs), with their proven capabilities in code understanding and generation, presents an opportunity to address this limitation. This study introduces LLMSecConfig, an innovative framework that bridges this gap by combining SATs with LLMs. Our approach leverages advanced prompting techniques and Retrieval-Augmented Generation (RAG) to automatically repair security misconfigurations while preserving operational functionality. Evaluation of 1,000 real-world Kubernetes configurations achieved a 94\% success rate while maintaining a low rate of introducing new misconfigurations.
  Our work makes a promising step towards automated container security management, reducing the manual effort required for configuration maintenance.

[Arxiv](https://arxiv.org/abs/2502.02009)