# DMGIN：多模态LLMs如何增强大型推荐模型以捕捉用户长期点击后行为

发布时间：2025年08月29日

`LLM应用` `零售与电商`

> DMGIN: How Multimodal LLMs Enhance Large Recommendation Models for Lifelong User Post-click Behaviors

# 摘要

> 基于用户长期行为序列构建用户兴趣模型，对提升点击率（CTR）预测效果至关重要。然而，冗长的点击后行为序列本身存在严重的性能瓶颈：海量数据不仅推高了计算成本，还降低了模型训练与推理的效率。传统方法虽采用两阶段策略应对，但因未能充分利用完整序列上下文，模型效果大打折扣。更关键的是，将多模态嵌入融入现有大型推荐模型（LRM）时挑战重重：这类嵌入不仅加重计算负担，还与LRM架构难以兼容。

为解决上述问题并提升模型的效率与精度，我们提出深度多模态群体兴趣网络（DMGIN）。我们观察到，用户点击后行为序列中存在大量行为和时间戳各异的重复项目。因此，DMGIN借助多模态LLM（MLLM）进行分组，以更高效地重组完整的长期点击后行为序列，且几乎不增加额外计算开销——这与直接引入多模态嵌入的方式截然不同。

为减少分组可能造成的信息损失，我们采取了两项核心策略。其一，通过兴趣统计与组内Transformer分析各组行为，精准捕捉群体特征；其二，将组间Transformer应用于按时间排序的组，以捕捉用户群体兴趣的动态演变。

我们在工业与公共数据集上的大量实验验证了DMGIN的高效性与有效性。在LBS广告系统中的A/B测试显示，DMGIN使CTR提升4.7%，每英里收入增长2.3%。

> Modeling user interest based on lifelong user behavior sequences is crucial for enhancing Click-Through Rate (CTR) prediction. However, long post-click behavior sequences themselves pose severe performance issues: the sheer volume of data leads to high computational costs and inefficiencies in model training and inference. Traditional methods address this by introducing two-stage approaches, but this compromises model effectiveness due to incomplete utilization of the full sequence context. More importantly, integrating multimodal embeddings into existing large recommendation models (LRM) presents significant challenges: These embeddings often exacerbate computational burdens and mismatch with LRM architectures. To address these issues and enhance the model's efficiency and accuracy, we introduce Deep Multimodal Group Interest Network (DMGIN). Given the observation that user post-click behavior sequences contain a large number of repeated items with varying behaviors and timestamps, DMGIN employs Multimodal LLMs(MLLM) for grouping to reorganize complete lifelong post-click behavior sequences more effectively, with almost no additional computational overhead, as opposed to directly introducing multimodal embeddings. To mitigate the potential information loss from grouping, we have implemented two key strategies. First, we analyze behaviors within each group using both interest statistics and intra-group transformers to capture group traits. Second, apply inter-group transformers to temporally ordered groups to capture the evolution of user group interests. Our extensive experiments on both industrial and public datasets confirm the effectiveness and efficiency of DMGIN. The A/B test in our LBS advertising system shows that DMGIN improves CTR by 4.7% and Revenue per Mile by 2.3%.

[Arxiv](https://arxiv.org/abs/2508.21801)