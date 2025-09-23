# RALLM-POI：检索增强大型语言模型（LLM）用于结合地理重排序的零样本下一个兴趣点（POI）推荐

发布时间：2025年09月21日

`RAG` `交通运输`

> RALLM-POI: Retrieval-Augmented LLM for Zero-shot Next POI Recommendation with Geographical Reranking

# 摘要

> 下一个兴趣点（POI）推荐旨在根据用户的历史移动轨迹预测其下一个目的地。传统模型需大量训练，而LLM虽能提供灵活且泛化能力强的零样本解决方案，但因缺乏轨迹与空间上下文，常生成泛化度过高或地理无关的结果。为此，我们提出RALLM-POI框架，将LLM与检索增强生成及自校正机制相结合。该框架首先通过历史轨迹检索器（HTR）获取相关历史轨迹作为上下文参考，并通过地理距离重排序器（GDR）对其重排序，从而优先筛选空间相关性强的轨迹。最后，我们设计了智能体LLM校正器（ALR），借助自我反思机制优化输出结果。在无需额外训练的情况下，RALLM-POI在三个真实世界的Foursquare数据集上均实现了显著的准确率提升，性能超过传统方法和基于LLM的基线模型。代码已发布于https://github.com/LKRcrocodile/RALLM-POI。

> Next point-of-interest (POI) recommendation predicts a user's next destination from historical movements. Traditional models require intensive training, while LLMs offer flexible and generalizable zero-shot solutions but often generate generic or geographically irrelevant results due to missing trajectory and spatial context. To address these issues, we propose RALLM-POI, a framework that couples LLMs with retrieval-augmented generation and self-rectification. We first propose a Historical Trajectory Retriever (HTR) that retrieves relevant past trajectories to serve as contextual references, which are then reranked by a Geographical Distance Reranker (GDR) for prioritizing spatially relevant trajectories. Lastly, an Agentic LLM Rectifier (ALR) is designed to refine outputs through self-reflection. Without additional training, RALLM-POI achieves substantial accuracy gains across three real-world Foursquare datasets, outperforming both conventional and LLM-based baselines. Code is released at https://github.com/LKRcrocodile/RALLM-POI.

[Arxiv](https://arxiv.org/abs/2509.17066)