# LLM 化身 HPC 专家：扩展 RAG 架构，驾驭 HPC 数据

发布时间：2024年12月08日

`RAG

理由：这篇论文提出了一种名为假设命令嵌入（HyCE）的新方法，通过整合实时、用户特定的HPC数据，扩展了检索增强生成（RAG）的能力。论文的核心内容围绕如何利用RAG技术来提升HPC系统的易用性，并且通过自动RAG评估框架对HyCE进行测试。因此，这篇论文主要属于RAG分类。` `高性能计算` `人工智能`

> LLM as HPC Expert: Extending RAG Architecture for HPC Data

# 摘要

> 高性能计算（HPC）在执行复杂计算任务中至关重要，但其复杂性常常让用户，尤其是那些不熟悉HPC命令和工作流程的用户感到头疼。本文提出了一种名为假设命令嵌入（HyCE）的新方法，通过整合实时、用户特定的HPC数据，扩展了检索增强生成（RAG）的能力，从而提升了HPC系统的易用性。HyCE通过实时、用户特定的HPC信息增强了大型语言模型（LLM），弥补了在这些数据上微调模型的不足。我们采用自动RAG评估框架对HyCE进行测试，LLM从HPC数据中生成合成问题并充当评估者，评估扩展RAG在HPC任务相关指标上的表现。此外，我们还解决了在HPC环境中部署LLM时面临的关键安全问题，如数据隐私和命令执行风险。这一解决方案为HPC集群提供了一种灵活且可扩展的方式，使LLM能够充当HPC专家，帮助用户更好地驾驭复杂的HPC系统。

> High-Performance Computing (HPC) is crucial for performing advanced computational tasks, yet their complexity often challenges users, particularly those unfamiliar with HPC-specific commands and workflows. This paper introduces Hypothetical Command Embeddings (HyCE), a novel method that extends Retrieval-Augmented Generation (RAG) by integrating real-time, user-specific HPC data, enhancing accessibility to these systems. HyCE enriches large language models (LLM) with real-time, user-specific HPC information, addressing the limitations of fine-tuned models on such data. We evaluate HyCE using an automated RAG evaluation framework, where the LLM itself creates synthetic questions from the HPC data and serves as a judge, assessing the efficacy of the extended RAG with the evaluation metrics relevant for HPC tasks. Additionally, we tackle essential security concerns, including data privacy and command execution risks, associated with deploying LLMs in HPC environments. This solution provides a scalable and adaptable approach for HPC clusters to leverage LLMs as HPC expert, bridging the gap between users and the complex systems of HPC.

[Arxiv](https://arxiv.org/abs/2501.14733)