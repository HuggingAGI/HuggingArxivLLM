# IntentionReasoner：借助意图推理与选择性查询优化助力自适应LLM安全防护

发布时间：2025年08月27日

`LLM应用` `基础理论`

> IntentionReasoner: Facilitating Adaptive LLM Safeguards through Intent Reasoning and Selective Query Refinement

# 摘要

> 大型语言模型（LLMs）的飞速发展推动其在各领域广泛应用，但其生成有害内容的能力也带来了严峻的安全挑战。尽管已有大量研究致力于减少有害输出，但这类方法常因过度拒绝无害提示而得不偿失。如何在安全性、过度拒绝与实用性之间找到平衡，仍是当前亟待解决的核心难题。为此，本研究提出新型安全防护机制IntentionReasoner，它借助专用防护模型，通过意图推理、多级安全分类与查询重写，有效中和边缘案例查询中的潜在有害意图。具体而言，我们首先构建了一个涵盖约163,000条查询的综合数据集，每条查询均标注了意图推理过程、安全标签及重写版本。接着通过监督微调，让防护模型掌握格式规范、意图分析与安全重写的基础能力。最后，我们采用定制化的多奖励优化策略，在强化学习框架中融合基于规则的启发式方法与奖励模型信号，进一步提升模型性能。大量实验结果显示，IntentionReasoner在多项安全防护基准测试、生成质量评估及越狱攻击场景中均表现突出，在显著提升安全性的同时，有效降低了过度拒绝率，并改善了响应质量。

> The rapid advancement of large language models (LLMs) has driven their adoption across diverse domains, yet their ability to generate harmful content poses significant safety challenges. While extensive research has focused on mitigating harmful outputs, such efforts often come at the cost of excessively rejecting harmless prompts. Striking a balance among safety, over-refusal, and utility remains a critical challenge. In this work, we introduce IntentionReasoner, a novel safeguard mechanism that leverages a dedicated guard model to perform intent reasoning, multi-level safety classification, and query rewriting to neutralize potentially harmful intent in edge-case queries. Specifically, we first construct a comprehensive dataset comprising approximately 163,000 queries, each annotated with intent reasoning, safety labels, and rewritten versions. Supervised fine-tuning is then applied to equip the guard model with foundational capabilities in format adherence, intent analysis, and safe rewriting. Finally, we apply a tailored multi-reward optimization strategy that integrates rule-based heuristics and reward model signals within a reinforcement learning framework to further enhance performance. Extensive experiments show that IntentionReasoner excels in multiple safeguard benchmarks, generation quality evaluations, and jailbreak attack scenarios, significantly enhancing safety while effectively reducing over-refusal rates and improving the quality of responses.

[Arxiv](https://arxiv.org/abs/2508.20151)