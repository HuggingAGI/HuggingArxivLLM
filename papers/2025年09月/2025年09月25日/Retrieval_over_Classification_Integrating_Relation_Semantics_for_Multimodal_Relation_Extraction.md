# 检索优于分类：整合关系语义以实现多模态关系抽取

发布时间：2025年09月25日

`LLM应用` `基础理论`

> Retrieval over Classification: Integrating Relation Semantics for Multimodal Relation Extraction

# 摘要

> 关系抽取（RE）旨在识别非结构化文本中实体间的语义关系。尽管近年研究已将传统RE扩展到多模态场景，但多数方法仍沿用基于分类的范式，借助融合的多模态特征将关系表示为离散标签。这种范式存在两个明显局限：（1）忽略了实体类型、位置线索等结构约束；（2）在细粒度关系理解上缺乏语义表达能力。为此，我们提出Retrieval Over Classification（ROC）——一种新颖框架，将多模态RE重构为由关系语义驱动的检索任务。ROC通过多模态编码器整合实体类型与位置信息，利用大型语言模型将关系标签扩展为自然语言描述，并借助基于语义相似度的对比学习对齐实体-关系对。实验表明，该方法在MNRE和MORE基准数据集上取得了最先进的性能，并展现出更强的鲁棒性和可解释性。

> Relation extraction (RE) aims to identify semantic relations between entities in unstructured text. Although recent work extends traditional RE to multimodal scenarios, most approaches still adopt classification-based paradigms with fused multimodal features, representing relations as discrete labels. This paradigm has two significant limitations: (1) it overlooks structural constraints like entity types and positional cues, and (2) it lacks semantic expressiveness for fine-grained relation understanding. We propose \underline{R}etrieval \underline{O}ver \underline{C}lassification (ROC), a novel framework that reformulates multimodal RE as a retrieval task driven by relation semantics. ROC integrates entity type and positional information through a multimodal encoder, expands relation labels into natural language descriptions using a large language model, and aligns entity-relation pairs via semantic similarity-based contrastive learning. Experiments show that our method achieves state-of-the-art performance on the benchmark datasets MNRE and MORE and exhibits stronger robustness and interpretability.

[Arxiv](https://arxiv.org/abs/2509.21151)