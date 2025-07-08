# GAF-Guard：大型语言模型的风险管理与治理智能体框架

发布时间：2025年07月01日

`LLM应用

理由：论文讨论了大型语言模型（LLMs）的应用监控和治理框架，旨在检测和管理潜在风险，确保模型符合用户需求和价值观。虽然提到了自主代理，但主要聚焦于LLM的实际应用和监控，属于应用层面。` `人工智能`

> GAF-Guard: An Agentic Framework for Risk Management and Governance in Large Language Models

# 摘要

> 随着大型语言模型 (LLMs) 在各领域的广泛应用，严格监控变得尤为重要，以防止意外的负面后果并确保模型稳健性。此外，LLMs 的设计需与人类价值观保持一致，例如防止有害内容传播并确保负责任的使用。然而，现有的 LLM 监控自动化系统主要关注与模型相关的特定问题，如幻觉现象，而对具体应用场景和用户需求的关注较少。本文提出了一种全新的 LLM 治理框架 GAF-Guard，该框架以用户、应用场景和模型为核心，旨在检测和监控 LLM 基础应用部署中的潜在风险。通过构建自主代理，GAF-Guard 在特定场景中识别风险，激活相应的风险检测工具，并持续监控和报告，从而提升 AI 安全性并满足用户期待。代码可在 https://github.com/IBM/risk-atlas-nexus-demos/tree/main/gaf-guard 获取。

> As Large Language Models (LLMs) continue to be increasingly applied across various domains, their widespread adoption necessitates rigorous monitoring to prevent unintended negative consequences and ensure robustness. Furthermore, LLMs must be designed to align with human values, like preventing harmful content and ensuring responsible usage. The current automated systems and solutions for monitoring LLMs in production are primarily centered on LLM-specific concerns like hallucination etc, with little consideration given to the requirements of specific use-cases and user preferences. This paper introduces GAF-Guard, a novel agentic framework for LLM governance that places the user, the use-case, and the model itself at the center. The framework is designed to detect and monitor risks associated with the deployment of LLM based applications. The approach models autonomous agents that identify risks, activate risk detection tools, within specific use-cases and facilitate continuous monitoring and reporting to enhance AI safety, and user expectations. The code is available at https://github.com/IBM/risk-atlas-nexus-demos/tree/main/gaf-guard.

[Arxiv](https://arxiv.org/abs/2507.02986)