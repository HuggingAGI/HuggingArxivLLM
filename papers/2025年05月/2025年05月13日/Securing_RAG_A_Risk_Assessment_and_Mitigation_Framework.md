# # 构建安全的 RAG：风险评估与缓解框架

发布时间：2025年05月13日

`RAG` `数据安全`

> Securing RAG: A Risk Assessment and Mitigation Framework

# 摘要

> 检索增强生成（RAG）已成为用户端NLP应用的事实上的行业标准，它无需重新训练或微调大型语言模型（LLMs），即可实现数据的无缝集成。这一特性不仅显著提升了响应的质量和准确性，同时也带来了新的安全与隐私挑战，特别是在处理敏感数据时。随着RAG技术的快速普及，确保数据和服务的安全已成为当务之急。

本文首先深入分析了RAG管道的潜在漏洞，并系统性地梳理了从数据预处理、存储管理到与LLMs集成的完整攻击面。随后，我们采用结构化方法，将识别出的安全风险与其对应的缓解措施一一匹配。在第二阶段，本文构建了一个创新框架，将RAG特有的安全考量与现有的通用安全指南、行业标准及最佳实践相结合。该框架旨在为构建稳健、合规、安全且值得信赖的RAG系统提供清晰的指导方向。

> Retrieval Augmented Generation (RAG) has emerged as the de facto industry standard for user-facing NLP applications, offering the ability to integrate data without re-training or fine-tuning Large Language Models (LLMs). This capability enhances the quality and accuracy of responses but also introduces novel security and privacy challenges, particularly when sensitive data is integrated. With the rapid adoption of RAG, securing data and services has become a critical priority. This paper first reviews the vulnerabilities of RAG pipelines, and outlines the attack surface from data pre-processing and data storage management to integration with LLMs. The identified risks are then paired with corresponding mitigations in a structured overview. In a second step, the paper develops a framework that combines RAG-specific security considerations, with existing general security guidelines, industry standards, and best practices. The proposed framework aims to guide the implementation of robust, compliant, secure, and trustworthy RAG systems.

[Arxiv](https://arxiv.org/abs/2505.08728)