# 超越交互：为推荐系统生成节点级别的图结构

发布时间：2025年07月28日

`其他` `推荐系统` `信息检索`

> Beyond Interactions: Node-Level Graph Generation for Knowledge-Free Augmentation in Recommender Systems

# 摘要

> 最近的研究进展表明，推荐系统主要依赖知识图谱或大型语言模型等外部资源来提升推荐效果，但这种依赖外部数据和计算资源的方式在实际应用中存在局限性。虽然无知识模型能够通过直接操作边来增强推荐效果，但缺乏数据增强原语使其难以有效弥合语义和结构上的差距，无法成为高质量的替代方案。与现有基于扩散的用户-物品交互重模方法不同，本研究提出了一种开创性的无知识增强框架NodeDiffRec。该框架通过扩散方式实现细粒度的节点级图生成推荐，并扩展受限增强原语的范围。通过合成与潜在分布相契合的伪物品及其交互进行注入，并通过去噪偏好建模过程进一步优化用户偏好，NodeDiffRec无需外部知识即可显著提升语义多样性和结构连通性。在多种数据集和推荐算法上的广泛实验表明，NodeDiffRec实现了State-of-the-Art（SOTA）性能，与所选基线相比，在Recall@5指标上平均性能提升高达98.6%，在NDCG@5指标上提升84.0%。

> Recent advances in recommender systems rely on external resources such as knowledge graphs or large language models to enhance recommendations, which limit applicability in real-world settings due to data dependency and computational overhead. Although knowledge-free models are able to bolster recommendations by direct edge operations as well, the absence of augmentation primitives drives them to fall short in bridging semantic and structural gaps as high-quality paradigm substitutes. Unlike existing diffusion-based works that remodel user-item interactions, this work proposes NodeDiffRec, a pioneering knowledge-free augmentation framework that enables fine-grained node-level graph generation for recommendations and expands the scope of restricted augmentation primitives via diffusion. By synthesizing pseudo-items and corresponding interactions that align with the underlying distribution for injection, and further refining user preferences through a denoising preference modeling process, NodeDiffRec dramatically enhances both semantic diversity and structural connectivity without external knowledge. Extensive experiments across diverse datasets and recommendation algorithms demonstrate the superiority of NodeDiffRec, achieving State-of-the-Art (SOTA) performance, with maximum average performance improvement 98.6% in Recall@5 and 84.0% in NDCG@5 over selected baselines.

[Arxiv](https://arxiv.org/abs/2507.20578)