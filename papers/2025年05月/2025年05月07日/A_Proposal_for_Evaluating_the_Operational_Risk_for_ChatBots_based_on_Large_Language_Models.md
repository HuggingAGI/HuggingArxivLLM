# 基于大型语言模型的聊天机器人操作风险评估方案

发布时间：2025年05月07日

`LLM应用` `人工智能` `网络安全`

> A Proposal for Evaluating the Operational Risk for ChatBots based on Large Language Models

# 摘要

> 生成式AI与大型语言模型的诞生，让类人交互的先进聊天机器人成为可能。但这些对话型AI带来的不仅是超越传统网络安全范畴的风险，更是一系列全新的安全隐患。本研究提出了一种创新的风险评估指标，能够同时衡量服务提供方、终端用户和第三方面临的潜在威胁。我们的方法将诱导聊天机器人出错的技术难度（从简单故障到复杂的prompt注入攻击）与目标行业、用户年龄和漏洞严重性等情境因素相结合。借助开源LLM漏洞测试框架Garak，我们对其进行了升级，以应对虚假信息、代码幻觉、社会工程及恶意代码生成等多种威胁。通过一个基于检索增强生成（RAG）的聊天机器人案例，我们展示了聚合风险评分如何指导短期风险缓解和长期的模型优化部署。研究结果表明，多维度的风险评估是构建安全可靠的AI对话系统不可或缺的基础。

> The emergence of Generative AI (Gen AI) and Large Language Models (LLMs) has enabled more advanced chatbots capable of human-like interactions. However, these conversational agents introduce a broader set of operational risks that extend beyond traditional cybersecurity considerations. In this work, we propose a novel, instrumented risk-assessment metric that simultaneously evaluates potential threats to three key stakeholders: the service-providing organization, end users, and third parties. Our approach incorporates the technical complexity required to induce erroneous behaviors in the chatbot--ranging from non-induced failures to advanced prompt-injection attacks--as well as contextual factors such as the target industry, user age range, and vulnerability severity. To validate our metric, we leverage Garak, an open-source framework for LLM vulnerability testing. We further enhance Garak to capture a variety of threat vectors (e.g., misinformation, code hallucinations, social engineering, and malicious code generation). Our methodology is demonstrated in a scenario involving chatbots that employ retrieval-augmented generation (RAG), showing how the aggregated risk scores guide both short-term mitigation and longer-term improvements in model design and deployment. The results underscore the importance of multi-dimensional risk assessments in operationalizing secure, reliable AI-driven conversational systems.

[Arxiv](https://arxiv.org/abs/2505.04784)