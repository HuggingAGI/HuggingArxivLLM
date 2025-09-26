# CLaw：大型语言模型中文法律知识基准测评——细粒度语料库及推理分析

发布时间：2025年09月25日

`LLM应用` `法律科技`

> CLaw: Benchmarking Chinese Legal Knowledge in Large Language Models - A Fine-grained Corpus and Reasoning Analysis

# 摘要

> 大型语言模型（LLMs）越来越多地被用于分析法律文本和引用相关法规，但其可靠性常受限于通用预训练——这种预训练虽摄入法律文本却缺乏专门关注，从而掩盖了它们法律知识的真实深度。本文提出CLaw，一种新型基准，专门用于细致评估LLMs的中国法律知识及其在推理中的应用。CLaw包含两大核心部分：（1）一个全面、细粒度的语料库，涵盖全部306部中国国家法规，精确分割至款级，并纳入准确的历史修订时间戳，可支持严格的召回评估（共64,849条条目）；（2）254个具有挑战性的基于案例的推理实例，源自中国最高法院的精选材料，用于评估法律知识的实际应用能力。实证评估显示，大多数当代LLMs在准确再现法律条款方面表现不佳。由于法律条款的准确检索与引用是法律推理的基础，这种缺陷严重影响了它们回应的可靠性。我们认为，要让LLMs实现可信的法律推理，需将准确的知识检索（可通过监督微调（SFT）或检索增强生成（RAG）加以提升）与强大的通用推理能力紧密结合。这项工作为推动特定领域（尤其是复杂法律领域）的LLM推理研究提供了重要基准和关键见解。

> Large Language Models (LLMs) are increasingly tasked with analyzing legal texts and citing relevant statutes, yet their reliability is often compromised by general pre-training that ingests legal texts without specialized focus, obscuring the true depth of their legal knowledge. This paper introduces CLaw, a novel benchmark specifically engineered to meticulously evaluate LLMs on Chinese legal knowledge and its application in reasoning. CLaw comprises two key components: (1) a comprehensive, fine-grained corpus of all 306 Chinese national statutes, segmented to the subparagraph level and incorporating precise historical revision timesteps for rigorous recall evaluation (64,849 entries), and (2) a challenging set of 254 case-based reasoning instances derived from China Supreme Court curated materials to assess the practical application of legal knowledge. Our empirical evaluation reveals that most contemporary LLMs significantly struggle to faithfully reproduce legal provisions. As accurate retrieval and citation of legal provisions form the basis of legal reasoning, this deficiency critically undermines the reliability of their responses. We contend that achieving trustworthy legal reasoning in LLMs requires a robust synergy of accurate knowledge retrieval--potentially enhanced through supervised fine-tuning (SFT) or retrieval-augmented generation (RAG)--and strong general reasoning capabilities. This work provides an essential benchmark and critical insights for advancing domain-specific LLM reasoning, particularly within the complex legal sphere.

[Arxiv](https://arxiv.org/abs/2509.21208)