# C-PATH：医疗系统中对话式患者协助与分诊

发布时间：2025年06月07日

`LLM应用` `人工智能`

> C-PATH: Conversational Patient Assistance and Triage in Healthcare System

# 摘要

> 医疗系统的复杂性常常让患者感到困惑和不知所措，阻碍了他们及时获得适当的医疗服务。本文介绍了一款名为C-PATH（对话式患者协助与分诊系统）的全新对话式AI系统，该系统基于大型语言模型（LLMs），旨在通过自然、多轮对话帮助患者识别症状并推荐合适的医疗科室。C-PATH采用基于LLaMA3架构的多阶段管道，对医学知识、对话数据和临床摘要进行了微调。本研究的核心贡献在于提出了一种基于GPT的数据增强框架，能够将结构化的临床知识（来自DDXPlus）转化为易于理解的日常对话，从而更好地与患者沟通规范保持一致。此外，我们还实现了一种可扩展的对话历史管理策略，以确保对话的长期连贯性。通过GPTScore的评估，C-PATH在清晰度、信息量和推荐准确性等多个维度上表现优异。定量基准测试表明，C-PATH在经过GPT重写的对话数据集上取得了显著优于领域特定基线模型的性能。C-PATH标志着在开发以用户为中心、易于访问且精准的AI工具方面迈出了重要一步，这些工具将为数字医疗辅助和分诊提供强大支持。


> Navigating healthcare systems can be complex and overwhelming, creating barriers for patients seeking timely and appropriate medical attention. In this paper, we introduce C-PATH (Conversational Patient Assistance and Triage in Healthcare), a novel conversational AI system powered by large language models (LLMs) designed to assist patients in recognizing symptoms and recommending appropriate medical departments through natural, multi-turn dialogues. C-PATH is fine-tuned on medical knowledge, dialogue data, and clinical summaries using a multi-stage pipeline built on the LLaMA3 architecture. A core contribution of this work is a GPT-based data augmentation framework that transforms structured clinical knowledge from DDXPlus into lay-person-friendly conversations, allowing alignment with patient communication norms. We also implement a scalable conversation history management strategy to ensure long-range coherence. Evaluation with GPTScore demonstrates strong performance across dimensions such as clarity, informativeness, and recommendation accuracy. Quantitative benchmarks show that C-PATH achieves superior performance in GPT-rewritten conversational datasets, significantly outperforming domain-specific baselines. C-PATH represents a step forward in the development of user-centric, accessible, and accurate AI tools for digital health assistance and triage.

[Arxiv](https://arxiv.org/abs/2506.06737)