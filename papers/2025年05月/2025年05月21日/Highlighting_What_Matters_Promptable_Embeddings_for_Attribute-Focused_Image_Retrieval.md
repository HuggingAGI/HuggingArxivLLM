# 突出关键点：用于属性聚焦图像检索的可提示嵌入

发布时间：2025年05月21日

`LLM应用` `计算机视觉`

> Highlighting What Matters: Promptable Embeddings for Attribute-Focused Image Retrieval

# 摘要

> 虽然“一张图片胜过千言万语”，但其中仅有少数图像能提供特定任务的关键信息，因此需要重点关注。基于此，理想的文本到图像 (T2I) 检索器应优先关注与查询相关的特定视觉属性。为了评估现有检索器在处理属性聚焦型查询方面的表现，我们构建了基于COCO的COCO-Facet基准数据集，包含9,112个关于各种感兴趣属性的查询。我们发现，由于效率和零样本能力而被广泛应用的类似CLIP的检索器表现不佳且不均衡，可能是因为它们的图像嵌入关注全局语义和主体，而忽略了其他细节。值得注意的是，我们发现即使是基于近期更强大的多模态大语言模型 (MLLM)、具有更大输出维度的检索器也难以突破这一限制。因此，我们假设使用通用图像嵌入进行检索在处理此类查询时效果不佳。作为解决方案，我们提出利用这些多模态检索器生成的可提示图像嵌入，通过强调所需属性来提升性能。我们推导此类嵌入的pipeline在不同查询类型、图像池和基础检索器架构之间具有良好的泛化性。为了提升实际应用性，我们提供了两种加速策略：预处理可提示嵌入和使用线性近似。我们发现，当提示预定义时，前者在Recall@5指标上提升了15%，而后者在仅推理阶段提供提示时提升了8%。
    

> While an image is worth more than a thousand words, only a few provide crucial information for a given task and thus should be focused on. In light of this, ideal text-to-image (T2I) retrievers should prioritize specific visual attributes relevant to queries. To evaluate current retrievers on handling attribute-focused queries, we build COCO-Facet, a COCO-based benchmark with 9,112 queries about diverse attributes of interest. We find that CLIP-like retrievers, which are widely adopted due to their efficiency and zero-shot ability, have poor and imbalanced performance, possibly because their image embeddings focus on global semantics and subjects while leaving out other details. Notably, we reveal that even recent Multimodal Large Language Model (MLLM)-based, stronger retrievers with a larger output dimension struggle with this limitation. Hence, we hypothesize that retrieving with general image embeddings is suboptimal for performing such queries. As a solution, we propose to use promptable image embeddings enabled by these multimodal retrievers, which boost performance by highlighting required attributes. Our pipeline for deriving such embeddings generalizes across query types, image pools, and base retriever architectures. To enhance real-world applicability, we offer two acceleration strategies: Pre-processing promptable embeddings and using linear approximations. We show that the former yields a 15% improvement in Recall@5 when prompts are predefined, while the latter achieves an 8% improvement when prompts are only available during inference.

[Arxiv](https://arxiv.org/abs/2505.15877)