# 混合型人工智能用于响应式多轮在线对话，结合新颖的动态路由与反馈适应机制。

发布时间：2025年06月02日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统在企业级对话式AI中的应用和优化，提出了一个结合RAG和基于意图的预设响应的混合框架。虽然提到了基于LLM的聊天机器人，但核心内容是关于RAG系统的改进和应用，因此归类到RAG。` `对话式AI` `企业级应用`

> Hybrid AI for Responsive Multi-Turn Online Conversations with Novel Dynamic Routing and Feedback Adaptation

# 摘要

> 检索增强生成（RAG）系统和基于LLM的聊天机器人通过将生成能力与外部知识检索相结合，显著推动了对话式AI的发展。然而，企业级部署面临多样化的用户查询、高延迟、幻觉问题以及难以整合频繁更新的领域特定知识等关键挑战。本文提出了一种新型混合框架，将RAG与基于意图的预设响应相结合。该框架利用预先定义的高置信度响应提高效率，同时动态将复杂或模糊的查询路由到RAG管道。我们的框架采用对话上下文管理器，确保多轮交互的一致性，并引入反馈循环来优化意图识别、动态调整置信阈值并随着时间扩展响应覆盖范围。实验结果表明，所提出的框架在高精度（95%）和低延迟（180ms）之间实现了平衡，优于RAG和基于意图的系统在多种查询类型上的表现。这使其成为企业级对话式AI应用的可扩展和自适应解决方案。


> Retrieval-Augmented Generation (RAG) systems and large language model (LLM)-powered chatbots have significantly advanced conversational AI by combining generative capabilities with external knowledge retrieval. Despite their success, enterprise-scale deployments face critical challenges, including diverse user queries, high latency, hallucinations, and difficulty integrating frequently updated domain-specific knowledge. This paper introduces a novel hybrid framework that integrates RAG with intent-based canned responses, leveraging predefined high-confidence responses for efficiency while dynamically routing complex or ambiguous queries to the RAG pipeline. Our framework employs a dialogue context manager to ensure coherence in multi-turn interactions and incorporates a feedback loop to refine intents, dynamically adjust confidence thresholds, and expand response coverage over time. Experimental results demonstrate that the proposed framework achieves a balance of high accuracy (95\%) and low latency (180ms), outperforming RAG and intent-based systems across diverse query types, positioning it as a scalable and adaptive solution for enterprise conversational AI applications.

[Arxiv](https://arxiv.org/abs/2506.02097)