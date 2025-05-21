# 知或不知：评估知识库外鲁棒性的工具库

发布时间：2025年05月18日

`RAG` `高风险应用` `政策问答`

> Know Or Not: a library for evaluating out-of-knowledge base robustness

# 摘要

> 尽管大型语言模型的能力已取得显著提升，但其在高风险应用场景中的使用仍受限制，主要原因是模型存在生成不实信息的风险。减少此类问题的一个关键方法是检索增强生成 (RAG)，但即使在 RAG 设置下，模型面对超出知识库范围的问题时仍可能生成不实信息。在高风险应用中，这种行为是不可接受的，因为模型在这种情况下应避免回答缺乏足够上下文的问题。本文提出了一种全新的方法，用于在 RAG 设置下系统性评估 LLM 的知识库外 (OOKB) 鲁棒性（即模型是否了解特定内容），且无需手动标注标准答案。我们通过一个开源库 knowornot 实现了这一方法，该库使用户能够开发自己的定制化评估数据和 OOKB 鲁棒性评估流程。knowornot 具备以下四个主要功能：首先，提供了一个统一的高级 API，简化了设置和运行鲁棒性基准测试的过程；其次，模块化架构强调了可扩展性和灵活性，允许用户轻松集成自己的 LLM 客户端和 RAG 设置；第三，严格的数据建模设计确保了实验的可重复性、可靠性和可追溯性；最后，提供了一套全面的工具，供用户自定义其工作流程。我们通过开发一个具有挑战性的基准测试 PolicyBench 来展示 knowornot 的实用性，该基准测试涵盖了四个政府政策相关的问答 (QA) 聊天机器人，并分析了其 OOKB 鲁棒性。knowornot 的源代码可在 https://github.com/govtech-responsibleai/KnowOrNot 获取。

> While the capabilities of large language models (LLMs) have progressed significantly, their use in high-stakes applications have been limited due to risks of hallucination. One key approach in reducing hallucination is retrieval-augmented generation (RAG), but even in such setups, LLMs may still hallucinate when presented with questions outside of the knowledge base. Such behavior is unacceptable in high-stake applications where LLMs are expected to abstain from answering queries it does not have sufficient context on. In this work, we present a novel methodology for systematically evaluating out-of-knowledge base (OOKB) robustness of LLMs (whether LLMs know or do not know) in the RAG setting, without the need for manual annotation of gold standard answers. We implement our methodology in knowornot, an open-source library that enables users to develop their own customized evaluation data and pipelines for OOKB robustness. knowornot comprises four main features. Firstly, it provides a unified, high-level API that streamlines the process of setting up and running robustness benchmarks. Secondly, its modular architecture emphasizes extensibility and flexibility, allowing users to easily integrate their own LLM clients and RAG settings. Thirdly, its rigorous data modeling design ensures experiment reproducibility, reliability and traceability. Lastly, it implements a comprehensive suite of tools for users to customize their pipelines. We demonstrate the utility of knowornot by developing a challenging benchmark, PolicyBench, which spans four Question-Answer (QA) chatbots on government policies, and analyze its OOKB robustness. The source code of knowornot is available https://github.com/govtech-responsibleai/KnowOrNot.

[Arxiv](https://arxiv.org/abs/2505.13545)