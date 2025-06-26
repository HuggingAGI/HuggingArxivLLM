# 标准适用性判定与跨司法管辖区推理：基于RAG的医疗器械合规性框架

发布时间：2025年06月23日

`RAG` `医疗器械` `监管科学`

> Standard Applicability Judgment and Cross-jurisdictional Reasoning: A RAG-based Framework for Medical Device Compliance

# 摘要

> 在医疗器械合规性领域，识别适用的监管标准是一个关键但研究不足的挑战，通常需要专家对不同司法管辖区的零散且异质化的文档进行解释。为了解决这一挑战，我们引入了一个模块化的AI系统，该系统利用检索增强生成（RAG）流水线来自动化标准适用性判断。对于自由文本形式的设备描述，我们的系统从经过整理的语料库中检索候选标准，并使用大型语言模型推断特定于管辖区的适用性，分为强制性、推荐性和不适用，并附有可追溯的说明。我们构建了一个包含专家标注标准映射的国际医疗器械描述基准数据集，并将我们的系统与仅检索、零样本和基于规则的基线方法进行对比评估。所提出的方案实现了73%的分类准确率和87%的Top-5检索召回率，证明了其在识别相关监管标准方面的有效性。我们推出了首个用于标准适用性推理的端到端系统，支持可扩展且可解释的人工智能辅助监管科学。值得注意的是，我们的区域感知RAG代理能够在美国和中国标准之间进行跨司法管辖区推理，支持在不同监管框架下的冲突解决和适用性说明。

> Identifying the appropriate regulatory standard applicability remains a critical yet understudied challenge in medical device compliance, frequently necessitating expert interpretation of fragmented and heterogeneous documentation across different jurisdictions. To address this challenge, we introduce a modular AI system that leverages a retrieval-augmented generation (RAG) pipeline to automate standard applicability determination. Given a free-text device description, our system retrieves candidate standards from a curated corpus and uses large language models to infer jurisdiction-specific applicability, classified as Mandatory, Recommended, or Not Applicable, with traceable justifications. We construct an international benchmark dataset of medical device descriptions with expert-annotated standard mappings, and evaluate our system against retrieval-only, zero-shot, and rule-based baselines. The proposed approach attains a classification accuracy of 73% and a Top-5 retrieval recall of 87%, demonstrating its effectiveness in identifying relevant regulatory standards. We introduce the first end-to-end system for standard applicability reasoning, enabling scalable and interpretable AI-supported regulatory science. Notably, our region-aware RAG agent performs cross-jurisdictional reasoning between Chinese and U.S. standards, supporting conflict resolution and applicability justification across regulatory frameworks.

[Arxiv](https://arxiv.org/abs/2506.18511)