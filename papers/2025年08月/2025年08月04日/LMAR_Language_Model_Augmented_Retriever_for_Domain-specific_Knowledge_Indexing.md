# # **LMAR：为领域知识索引增强的语言模型检索器**

发布时间：2025年08月04日

`RAG` `信息检索`

> LMAR: Language Model Augmented Retriever for Domain-specific Knowledge Indexing

# 摘要

> 检索增强生成（RAG）系统在处理领域特定知识时面临两大挑战：预训练嵌入性能下降和基于大型语言模型（LLM）的检索器带来的高昂计算成本。虽然微调数据增强嵌入模型提供了一种解决方案，但其有效性受限于高质量训练数据和可靠上下文完整性保持的分块策略。为应对这些挑战，我们提出了一种模型不可知的框架——LMAR（语言模型增强检索器），通过结合LLM引导的数据合成、对比嵌入适配和高效文本聚类，为领域特定知识的处理提供了新思路。

LMAR采用两阶段流水线设计：首先是三元组采样和合成数据增强，LLMs在此过程中同时承担标签生成器和验证器的角色，确保整个流水线的高质量监督。实验结果表明，LMAR在多个领域特定基准数据集上表现出色，性能超越多个基线模型，同时保持了适度的硬件要求和低延迟。其模型不可知的特性使其能够无缝集成到新兴的RAG架构和文本嵌入模型中，为持续改进提供了可能，而无需对现有流水线进行重新设计。LMAR的成功展示了其作为可扩展领域特定适应的实用且经济有效的解决方案的潜力。

> Retrieval Augmented Generation (RAG) systems often struggle with domain-specific knowledge due to performance deterioration of pre-trained embeddings and prohibitive computational costs of large language model (LLM)-based retrievers. While fine-tuning data augmentation embedding models offers a promising direction, its effectiveness is limited by the need for high-quality training data and reliable chunking strategies that preserve contextual integrity. We propose LMAR (Language Model Augmented Retriever), a model-agnostic framework that addresses these challenges by combining LLM-guided data synthesis with contrastive embedding adaptation and efficient text clustering. LMAR consists of a two-stage pipeline: (1) Triplet sampling and synthetic data augmentation, where LLMs act as both labeler and validator to ensure high-fidelity supervision throughout the pipeline. Experimental results across multiple domain-specific benchmark datasets demonstrate that LMAR outperforms multiple baseline models, while maintaining moderate hardware requirements and low latency. Its model-agnostic nature further enables seamless integration with emerging RAG architectures and text embedding models, ensuring continual improvements without redesigning the pipeline. These results highlight LMAR as a practical and cost-effective solution for scalable domain-specific adaptation.

[Arxiv](https://arxiv.org/abs/2508.05672)