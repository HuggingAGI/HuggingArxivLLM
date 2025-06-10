# SCGAgent：通过智能体工作流，重现推理模型在安全代码生成中的优势

发布时间：2025年06月08日

`LLM应用` `软件工程` `信息安全`

> SCGAgent: Recreating the Benefits of Reasoning Models for Secure Code Generation with Agentic Workflows

# 摘要

> 大型语言模型（LLMs）在日常和专业场景的代码生成任务中表现优异。然而，尽管当前LLMs能够生成功能正常的代码，但它们并不特别关注安全性，可能会产生存在可被利用漏洞的代码。在本研究中，我们提出了一种更可能生成安全代码的技术，并引入了SCGAgent（主动安全编码代理），该代理实现了我们的技术。我们结合安全编码指南和LLM生成的单元测试来保持功能正确性。在评估中，SCGAgent能够保留基础Sonnet-3.7 LLM近98%的功能性，同时实现了约25%的安全性提升。此外，SCGAgent通过非推理模型和代理工作流程，能够与采用复杂推理的先进LLM相媲美或超越其性能。

> Large language models (LLMs) have seen widespread success in code generation tasks for different scenarios, both everyday and professional. However current LLMs, despite producing functional code, do not prioritize security and may generate code with exploitable vulnerabilities. In this work, we propose techniques for generating code that is more likely to be secure and introduce SCGAgent, a proactive secure coding agent that implements our techniques. We use security coding guidelines that articulate safe programming practices, combined with LLM-generated unit tests to preserve functional correctness. In our evaluation, we find that SCGAgent is able to preserve nearly 98% of the functionality of the base Sonnet-3.7 LLM while achieving an approximately 25% improvement in security. Moreover, SCGAgent is able to match or best the performance of sophisticated reasoning LLMs using a non-reasoning model and an agentic workflow.

[Arxiv](https://arxiv.org/abs/2506.07313)