# 简单方法有效防御真实世界攻击中的RAG系统。

发布时间：2025年08月04日

`RAG` `信息安全`

> Simple Methods Defend RAG Systems Well Against Real-World Attacks

# 摘要

> 在安全关键应用中，确保检索增强生成（RAG）系统的安全性和领域内响应至关重要，但仍然是一个重大挑战。我们评估了四种针对领域外（OOD）查询检测的方法：GPT-4o、回归、主成分分析（PCA）和神经坍塌（NC），以确保 RAG 系统仅对知识库范围内的查询做出响应。具体而言，我们探索了两种新颖的降维和特征分离策略：	extit{PCA}（通过解释方差或 OOD 可分性选择顶部组件）和	extit{神经坍塌特征分离}的适应。我们在标准数据集（StackExchange 和 MSMARCO）和实际应用（如物质使用和 COVID-19）上验证了我们的方法，并针对 COVID-19 疫苗聊天机器人进行了 LLM 模拟攻击和实际攻击测试。通过人工和 LLM 基于响应正确性和相关性的评估，我们证实了外部 OOD 检测器对于保持响应相关性至关重要。

> Ensuring safety and in-domain responses for Retrieval-Augmented Generation (RAG) systems is paramount in safety-critical applications, yet remains a significant challenge. To address this, we evaluate four methodologies for Out-Of-Domain (OOD) query detection: GPT-4o, regression-based, Principal Component Analysis (PCA)-based, and Neural Collapse (NC), to ensure the RAG system only responds to queries confined to the system's knowledge base. Specifically, our evaluation explores two novel dimensionality reduction and feature separation strategies: \textit{PCA}, where top components are selected using explained variance or OOD separability, and an adaptation of \textit{Neural Collapse Feature Separation}. We validate our approach on standard datasets (StackExchange and MSMARCO) and real-world applications (Substance Use and COVID-19), including tests against LLM-simulated and actual attacks on a COVID-19 vaccine chatbot. Through human and LLM-based evaluations of response correctness and relevance, we confirm that an external OOD detector is crucial for maintaining response relevance.

[Arxiv](https://arxiv.org/abs/2508.02296)