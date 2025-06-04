# KARE-RAG：知识增强的精炼与提升方法

发布时间：2025年06月03日

`RAG` `知识图谱` `生成模型`

> KARE-RAG: Knowledge-Aware Refinement and Enhancement for RAG

# 摘要

> # 检索增强生成（RAG）的改进方向

检索增强生成（RAG）使大型语言模型（LLMs）能够访问更广泛的知识来源，但因检索到的文档中存在噪声，事实上的不一致仍然存在——即使采用先进的检索方法。我们证明，提升生成模型处理噪声内容的能力对于实现稳健性能同样至关重要。

本文中，我们介绍了KARE-RAG（知识感知的精炼与增强），它通过三项关键创新改进了知识的利用：（1）结构化的知识表示，有助于训练过程中发现错误；（2）密集直接偏好优化（DDPO），这是一种优化的训练目标，优先纠正关键错误；（3）对比数据生成管道，在修正事实错误的同时保持语义一致性。

实验表明，我们的方法显著提升了标准RAG流水线在不同模型规模下的性能，同时在域内和域外任务上均实现了性能提升，而未影响模型的通用能力。值得注意的是，这些改进是在仅使用少量训练数据的情况下实现的，表明通过针对性的学习策略，数据高效优化是可行的。

我们的研究结果为RAG的改进指明了一个新方向：通过改进模型处理检索内容的学习方式，我们可以提升其在各种推理范式中的性能。所有数据和代码将在Github上公开可用。

> Retrieval-Augmented Generation (RAG) enables large language models (LLMs) to access broader knowledge sources, yet factual inconsistencies persist due to noise in retrieved documents-even with advanced retrieval methods. We demonstrate that enhancing generative models' capacity to process noisy content is equally critical for robust performance. In this paper, we present KARE-RAG (Knowledge-Aware Refinement and Enhancement for RAG), which improves knowledge utilization through three key innovations: (1) structured knowledge representations that facilitate error detection during training, (2) Dense Direct Preference Optimization (DDPO)-a refined training objective that prioritizes correction of critical errors, and (3) a contrastive data generation pipeline that maintains semantic consistency while rectifying factual inaccuracies. Experiments show our method significantly enhances standard RAG pipelines across model scales, improving both in-domain and out-of-domain task performance without compromising general capabilities. Notably, these gains are achieved with modest training data, suggesting data-efficient optimization is possible through targeted learning strategies. Our findings establish a new direction for RAG improvement: by improving how models learn to process retrieved content, we can enhance performance across diverse inference paradigms. All data and code will be publicly available on Github.

[Arxiv](https://arxiv.org/abs/2506.02503)