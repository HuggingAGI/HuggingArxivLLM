# SEMMA: 语义感知知识图谱基础模型

发布时间：2025年05月26日

`LLM应用` `知识图谱`

> SEMMA: A Semantic Aware Knowledge Graph Foundation Model

# 摘要

> 知识图谱基础模型（KGFMs）在零样本推理中展现出潜力，但现有模型多依赖图结构，忽视了文本属性中的语义信息。我们提出SE MMA，一种双模块知识图谱基础模型，系统地结合了可迁移的文本语义与结构。SE MMA利用大型语言模型（LLMs）丰富关系标识符，生成语义嵌入，形成文本关系图并与结构部分融合。在54个知识图谱上，SE MMA优于仅基于结构的基线模型如ULTRA。尤其在测试时关系词汇完全未见的更具挑战性泛化设置中，结构方法失效，而SE MMA的效果是其两倍。这表明，在结构单独失效的场景下，文本语义对泛化至关重要，强调了融合结构和语言信号在知识推理中的基础模型的必要性。

> Knowledge Graph Foundation Models (KGFMs) have shown promise in enabling zero-shot reasoning over unseen graphs by learning transferable patterns. However, most existing KGFMs rely solely on graph structure, overlooking the rich semantic signals encoded in textual attributes. We introduce SEMMA, a dual-module KGFM that systematically integrates transferable textual semantics alongside structure. SEMMA leverages Large Language Models (LLMs) to enrich relation identifiers, generating semantic embeddings that subsequently form a textual relation graph, which is fused with the structural component. Across 54 diverse KGs, SEMMA outperforms purely structural baselines like ULTRA in fully inductive link prediction. Crucially, we show that in more challenging generalization settings, where the test-time relation vocabulary is entirely unseen, structural methods collapse while SEMMA is 2x more effective. Our findings demonstrate that textual semantics are critical for generalization in settings where structure alone fails, highlighting the need for foundation models that unify structural and linguistic signals in knowledge reasoning.

[Arxiv](https://arxiv.org/abs/2505.20422)