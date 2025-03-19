# RAG-KG-IL：融合RAG与增量知识图谱学习的多智能体混合框架，有效降低幻觉并提升大语言模型推理能力

发布时间：2025年03月14日

`LLM应用` `智能系统`

> RAG-KG-IL: A Multi-Agent Hybrid Framework for Reducing Hallucinations and Enhancing LLM Reasoning through RAG and Incremental Knowledge Graph Learning Integration

# 摘要

> 本文提出了一种名为 RAG-KG-IL 的新型多智能体混合框架，专为增强大型语言模型 (LLMs) 的推理能力而设计。该框架结合了检索增强生成 (RAG)、知识图谱 (KG) 和增量学习 (IL) 方法，旨在解决 LLMs 在处理结构化数据推理、应对知识动态演进以及抑制幻觉现象方面的挑战，特别是在关键任务领域。我们的 RAG-KG-IL 框架采用多智能体架构，能够实现持续的知识更新、整合结构化知识，并通过自主智能体提升可解释性和推理能力。框架利用 RAG 确保生成的响应基于可验证的信息，同时知识图谱提供结构化的领域知识，以提高一致性和理解深度。增量学习方法使知识库能够动态更新，无需全面重新训练，从而显著降低计算开销并提升模型的适应能力。我们通过涉及健康相关查询的真实案例研究对框架进行了评估，并将其与 GPT-4o 和仅 RAG 的基线等最先进的模型进行了比较。实验结果表明，我们的方法显著降低了幻觉率，提高了答案的完整性和推理准确性。结果突显了将 RAG、知识图谱和多智能体系统相结合的潜力，能够创建智能、可适应的系统，能够在复杂领域实现实时知识整合和推理。

> This paper presents RAG-KG-IL, a novel multi-agent hybrid framework designed to enhance the reasoning capabilities of Large Language Models (LLMs) by integrating Retrieval-Augmented Generation (RAG) and Knowledge Graphs (KGs) with an Incremental Learning (IL) approach. Despite recent advancements, LLMs still face significant challenges in reasoning with structured data, handling dynamic knowledge evolution, and mitigating hallucinations, particularly in mission-critical domains. Our proposed RAG-KG-IL framework addresses these limitations by employing a multi-agent architecture that enables continuous knowledge updates, integrates structured knowledge, and incorporates autonomous agents for enhanced explainability and reasoning. The framework utilizes RAG to ensure the generated responses are grounded in verifiable information, while KGs provide structured domain knowledge for improved consistency and depth of understanding. The Incremental Learning approach allows for dynamic updates to the knowledge base without full retraining, significantly reducing computational overhead and improving the model's adaptability. We evaluate the framework using real-world case studies involving health-related queries, comparing it to state-of-the-art models like GPT-4o and a RAG-only baseline. Experimental results demonstrate that our approach significantly reduces hallucination rates and improves answer completeness and reasoning accuracy. The results underscore the potential of combining RAG, KGs, and multi-agent systems to create intelligent, adaptable systems capable of real-time knowledge integration and reasoning in complex domains.

[Arxiv](https://arxiv.org/abs/2503.13514)