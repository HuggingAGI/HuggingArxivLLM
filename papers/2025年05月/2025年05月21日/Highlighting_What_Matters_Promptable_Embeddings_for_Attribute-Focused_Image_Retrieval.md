# 聚焦关键：用于属性导向图像检索的提示式嵌入

发布时间：2025年05月21日

`其他` `计算机视觉` `图像检索`

> Highlighting What Matters: Promptable Embeddings for Attribute-Focused Image Retrieval

# 摘要

> 虽然“一幅图像胜过千言万语”，但对于特定任务来说，只有少数图像提供了关键信息，因此需要重点关注。基于此，理想的文本到图像 (T2I) 检索器应优先考虑与查询相关的特定视觉属性。为了评估现有检索器在处理以属性为中心的查询方面的表现，我们构建了COCO-Facet基准，一个包含9,112个关于各种感兴趣属性的查询的基于COCO的数据集。我们发现，尽管CLIP类检索器由于其效率和零样本能力而被广泛采用，但它们的表现不佳且不平衡，这可能是因为它们的图像嵌入专注于全局语义和主体，而忽略了其他细节。值得注意的是，即使是最新的基于多模态大型语言模型 (MLLM) 的更强检索器，尽管具有更大的输出维度，也难以克服这一限制。因此，我们假设使用通用图像嵌入进行检索对于此类查询来说并非最优。作为解决方案，我们提出利用这些多模态检索器支持的可提示图像嵌入，通过突出显示所需属性来提升性能。我们的嵌入提取管道在查询类型、图像池和基础检索器架构之间具有良好的泛化能力。为了增强现实世界中的适用性，我们提供了两种加速策略：预处理可提示嵌入和使用线性近似。我们发现，当提示预先定义时，前者在Recall@5指标上提升了15%，而当提示仅在推理时可用时，后者实现了8%的提升。

> While an image is worth more than a thousand words, only a few provide crucial information for a given task and thus should be focused on. In light of this, ideal text-to-image (T2I) retrievers should prioritize specific visual attributes relevant to queries. To evaluate current retrievers on handling attribute-focused queries, we build COCO-Facet, a COCO-based benchmark with 9,112 queries about diverse attributes of interest. We find that CLIP-like retrievers, which are widely adopted due to their efficiency and zero-shot ability, have poor and imbalanced performance, possibly because their image embeddings focus on global semantics and subjects while leaving out other details. Notably, we reveal that even recent Multimodal Large Language Model (MLLM)-based, stronger retrievers with a larger output dimension struggle with this limitation. Hence, we hypothesize that retrieving with general image embeddings is suboptimal for performing such queries. As a solution, we propose to use promptable image embeddings enabled by these multimodal retrievers, which boost performance by highlighting required attributes. Our pipeline for deriving such embeddings generalizes across query types, image pools, and base retriever architectures. To enhance real-world applicability, we offer two acceleration strategies: Pre-processing promptable embeddings and using linear approximations. We show that the former yields a 15% improvement in Recall@5 when prompts are predefined, while the latter achieves an 8% improvement when prompts are only available during inference.

[Arxiv](https://arxiv.org/abs/2505.15877)