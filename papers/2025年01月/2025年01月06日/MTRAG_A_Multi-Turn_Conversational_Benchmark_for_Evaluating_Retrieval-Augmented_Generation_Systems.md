# MTRAG: 多轮对话基准，专为评估检索增强生成系统而设计

发布时间：2025年01月06日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在多轮对话中的应用，并提出了一个名为MTRAG的基准测试来评估RAG流程。论文的核心内容围绕RAG系统的评估和改进，因此应归类为RAG。` `对话系统`

> MTRAG: A Multi-Turn Conversational Benchmark for Evaluating Retrieval-Augmented Generation Systems

# 摘要

> 检索增强生成（RAG）最近在大型语言模型（LLMs）中备受关注。在多轮RAG对话中评估模型，即在先前对话的上下文中生成响应，是一项重要但常被忽视的任务，且面临诸多挑战。我们推出了MTRAG：一个端到端的人工生成多轮RAG基准测试，涵盖多个真实世界属性，用于全面评估RAG流程。MTRAG包含110个对话，平均每个对话7.7轮，涉及四个领域，共计842个任务。我们还探索了通过合成数据和LLM-as-a-Judge评估的自动化路径。评估结果显示，即使是最先进的LLM RAG系统在MTRAG上也表现不佳。我们强调了需要强大的检索和生成系统来处理后续轮次、无法回答的问题、非独立问题以及多领域挑战。MTRAG可在https://github.com/ibm/mt-rag-benchmark获取。

> Retrieval-augmented generation (RAG) has recently become a very popular task for Large Language Models (LLMs). Evaluating them on multi-turn RAG conversations, where the system is asked to generate a response to a question in the context of a preceding conversation is an important and often overlooked task with several additional challenges. We present MTRAG: an end-to-end human-generated multi-turn RAG benchmark that reflects several real-world properties across diverse dimensions for evaluating the full RAG pipeline. MTRAG contains 110 conversations averaging 7.7 turns each across four domains for a total of 842 tasks. We also explore automation paths via synthetic data and LLM-as-a-Judge evaluation. Our human and automatic evaluations show that even state-of-the-art LLM RAG systems struggle on MTRAG. We demonstrate the need for strong retrieval and generation systems that can handle later turns, unanswerable questions, non-standalone questions, and multiple domains. MTRAG is available at https://github.com/ibm/mt-rag-benchmark.

[Arxiv](https://arxiv.org/abs/2501.03468)