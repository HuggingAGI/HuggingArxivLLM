# 为多模式会话推荐蒸馏过渡模式到大型语言模型

发布时间：2025年04月13日

`LLM应用` `推荐系统` `多模态`

> Distilling Transitional Pattern to Large Language Models for Multimodal Session-based Recommendation

# 摘要

> 基于会话的推荐系统 (SBR) 通过分析匿名会话预测用户的下一个选择。传统方法主要依赖用户 ID 协同或辅助内容挖掘用户意图。针对数据稀疏和冷启动问题，近期的多模态 SBR (MSBR) 方法尝试通过预训练模型进行模态学习，但语义表达能力仍有不足。考虑到大型语言模型 (LLM) 的语义推理优势，本文提出了一种 LLM 增强的 MSBR 方法，通过利用 LLM 的认知能力生成更全面的多模态表示，从而提升推荐效果。这一方案面临两大挑战：如何让 LLM 同时理解迁移模式和多模态知识，以及如何将这些特征高效整合到统一的 LLM 模型中。为此，我们提出了一种名为 TPAD 的多模态增强框架，通过扩展蒸馏范式，解耦并优化迁移模式，从而提升 MSBR 的性能。TPAD 设计了并行的知识-多模态语言模型和迁移-多模态语言模型，前者专注于解析项目知识特征，后者则从会话中提取迁移感知特征。通过基于互信息估计的迁移模式对齐模块，TPAD 将两个 MLLM 有机结合，有效缓解了分布差异问题，并将迁移模式提炼到模态表示中。在真实数据集上的大量实验表明，我们的框架在提升推荐效果方面表现优异。


> Session-based recommendation (SBR) predicts the next item based on anonymous sessions. Traditional SBR explores user intents based on ID collaborations or auxiliary content. To further alleviate data sparsity and cold-start issues, recent Multimodal SBR (MSBR) methods utilize simplistic pre-trained models for modality learning but have limitations in semantic richness. Considering semantic reasoning abilities of Large Language Models (LLM), we focus on the LLM-enhanced MSBR scenario in this paper, which leverages LLM cognition for comprehensive multimodal representation generation, to enhance downstream MSBR. Tackling this problem faces two challenges: i) how to obtain LLM cognition on both transitional patterns and inherent multimodal knowledge, ii) how to align both features into one unified LLM, minimize discrepancy while maximizing representation utility. To this end, we propose a multimodal LLM-enhanced framework TPAD, which extends a distillation paradigm to decouple and align transitional patterns for promoting MSBR. TPAD establishes parallel Knowledge-MLLM and Transfer-MLLM, where the former interprets item knowledge-reflected features and the latter extracts transition-aware features underneath sessions. A transitional pattern alignment module harnessing mutual information estimation theory unites two MLLMs, alleviating distribution discrepancy and distilling transitional patterns into modal representations. Extensive experiments on real-world datasets demonstrate the effectiveness of our framework.

[Arxiv](https://arxiv.org/abs/2504.10538)