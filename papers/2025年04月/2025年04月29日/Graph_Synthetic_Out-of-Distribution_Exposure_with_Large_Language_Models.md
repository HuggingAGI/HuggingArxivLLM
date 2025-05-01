# 基于大型语言模型的图生成分布外暴露方法

发布时间：2025年04月29日

`LLM应用

理由：该论文探讨了如何利用零样本LLM生成合成数据来解决图模型中的OOD检测问题，属于LLM的应用场景。` `人工智能` `机器学习`

> Graph Synthetic Out-of-Distribution Exposure with Large Language Models

# 摘要

> 图模型中的分布外（OOD）检测对于确保开放世界和安全敏感应用中的模型鲁棒性至关重要。现有的方法通常使用仅 ID 数据训练 ID 分类器，再应用后验 OOD 评分技术。尽管 OOD 曝露在提高检测性能方面已被证明有效，但大多数图方法假设可以获得真实 OOD 节点，这在实践中往往难以实现。本文提出 GOE-LLM，一种无需真实 OOD 节点的框架，通过零样本 LLM 注释识别伪 OOD 节点，并生成语义丰富的合成 OOD 节点，用于正则化 ID 分类器训练，提升 OOD 感知能力。实验表明，GOE-LLM 在多个基准数据集上显著优于未使用 OOD 曝露的方法，并与依赖真实 OOD 数据的方法性能相当。

> Out-of-distribution (OOD) detection in graphs is critical for ensuring model robustness in open-world and safety-sensitive applications. Existing approaches to graph OOD detection typically involve training an in-distribution (ID) classifier using only ID data, followed by the application of post-hoc OOD scoring techniques. Although OOD exposure - introducing auxiliary OOD samples during training - has proven to be an effective strategy for enhancing detection performance, current methods in the graph domain generally assume access to a set of real OOD nodes. This assumption, however, is often impractical due to the difficulty and cost of acquiring representative OOD samples. In this paper, we introduce GOE-LLM, a novel framework that leverages Large Language Models (LLMs) for OOD exposure in graph OOD detection without requiring real OOD nodes. GOE-LLM introduces two pipelines: (1) identifying pseudo-OOD nodes from the initially unlabeled graph using zero-shot LLM annotations, and (2) generating semantically informative synthetic OOD nodes via LLM-prompted text generation. These pseudo-OOD nodes are then used to regularize the training of the ID classifier for improved OOD awareness. We evaluate our approach across multiple benchmark datasets, showing that GOE-LLM significantly outperforms state-of-the-art graph OOD detection methods that do not use OOD exposure and achieves comparable performance to those relying on real OOD data.

[Arxiv](https://arxiv.org/abs/2504.21198)