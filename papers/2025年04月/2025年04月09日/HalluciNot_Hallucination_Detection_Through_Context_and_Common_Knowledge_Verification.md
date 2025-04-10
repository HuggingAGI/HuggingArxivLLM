# # HalluciNot：基于上下文与常识验证的幻觉检测

发布时间：2025年04月09日

`LLM应用

LLM应用` `人工智能`

> HalluciNot: Hallucination Detection Through Context and Common Knowledge Verification

# 摘要

> 本文提出了一套用于企业环境中检测大型语言模型（LLM）输出幻觉现象的全面系统。我们针对企业应用中的LLM幻觉响应，提出了一种新型分类法，将其分为基于上下文、常识、企业特定和无害陈述四大类。我们的幻觉检测模型HDM-2能够从上下文和普遍已知事实（常识）两个维度验证LLM的输出。它不仅提供幻觉评分，还支持词级标注，从而实现对问题内容的精准定位。为了评估基于上下文和常识的幻觉检测效果，我们构建了一个全新的数据集HDMBench。实验结果表明，HDM-2在RagTruth、TruthfulQA和HDMBench数据集上的表现均优于现有方法。本研究重点解决了企业部署中的三大挑战：计算效率、领域专精和细粒度错误识别。我们的评估数据集、模型权重和推理代码均已公开发布。

> This paper introduces a comprehensive system for detecting hallucinations in large language model (LLM) outputs in enterprise settings. We present a novel taxonomy of LLM responses specific to hallucination in enterprise applications, categorizing them into context-based, common knowledge, enterprise-specific, and innocuous statements. Our hallucination detection model HDM-2 validates LLM responses with respect to both context and generally known facts (common knowledge). It provides both hallucination scores and word-level annotations, enabling precise identification of problematic content. To evaluate it on context-based and common-knowledge hallucinations, we introduce a new dataset HDMBench. Experimental results demonstrate that HDM-2 out-performs existing approaches across RagTruth, TruthfulQA, and HDMBench datasets. This work addresses the specific challenges of enterprise deployment, including computational efficiency, domain specialization, and fine-grained error identification. Our evaluation dataset, model weights, and inference code are publicly available.

[Arxiv](https://arxiv.org/abs/2504.07069)