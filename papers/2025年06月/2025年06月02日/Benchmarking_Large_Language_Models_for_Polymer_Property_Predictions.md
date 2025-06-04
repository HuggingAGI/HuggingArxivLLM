# # 基准测试：大型语言模型在聚合物性质预测中的应用

发布时间：2025年06月02日

`LLM应用` `聚合物科学` `材料科学`

> Benchmarking Large Language Models for Polymer Property Predictions

# 摘要

> 机器学习为聚合物科学带来了革命性变化，实现了快速性质预测和生成设计。大型语言模型（LLMs）进一步推动了聚合物信息学的发展，通过简化传统上依赖大量标注数据、手工特征设计和复杂工程的工作流程。LLMs借助迁移学习处理自然语言输入，无需显式指纹法，大幅简化了训练过程。本研究中，我们在包含11,740条条目的精选数据集上，微调了开源的LLaMA-3-8B和商业化的GPT-3.5模型，用于预测玻璃化转变温度、熔点和分解温度等关键热性能。通过参数高效的微调和超参数优化，我们在单任务（ST）和多任务（MT）学习框架下，将这些模型与传统的指纹法基方法——Polymer Genome、polyGNN和polyBERT进行了对比测试。结果显示，虽然LLM基方法在性能上接近传统模型，但在预测准确性和效率上仍稍逊一筹。LLaMA-3在性能上持续领先于GPT-3.5，这可能得益于其灵活的开源架构。此外，单任务学习比多任务学习更有效，因为LLMs难以捕捉跨属性相关性，而这正是传统方法的核心优势。分子嵌入分析表明，通用LLMs在表征精细化学结构信息方面，与手工设计特征和领域特定嵌入相比仍存在局限性。这些发现揭示了分子嵌入与自然语言处理之间的相互作用，为聚合物信息学中选择适合的LLMs提供了重要参考。


> Machine learning has revolutionized polymer science by enabling rapid property prediction and generative design. Large language models (LLMs) offer further opportunities in polymer informatics by simplifying workflows that traditionally rely on large labeled datasets, handcrafted representations, and complex feature engineering. LLMs leverage natural language inputs through transfer learning, eliminating the need for explicit fingerprinting and streamlining training. In this study, we finetune general purpose LLMs -- open-source LLaMA-3-8B and commercial GPT-3.5 -- on a curated dataset of 11,740 entries to predict key thermal properties: glass transition, melting, and decomposition temperatures. Using parameter-efficient fine-tuning and hyperparameter optimization, we benchmark these models against traditional fingerprinting-based approaches -- Polymer Genome, polyGNN, and polyBERT -- under single-task (ST) and multi-task (MT) learning. We find that while LLM-based methods approach traditional models in performance, they generally underperform in predictive accuracy and efficiency. LLaMA-3 consistently outperforms GPT-3.5, likely due to its tunable open-source architecture. Additionally, ST learning proves more effective than MT, as LLMs struggle to capture cross-property correlations, a key strength of traditional methods. Analysis of molecular embeddings reveals limitations of general purpose LLMs in representing nuanced chemo-structural information compared to handcrafted features and domain-specific embeddings. These findings provide insight into the interplay between molecular embeddings and natural language processing, guiding LLM selection for polymer informatics.

[Arxiv](https://arxiv.org/abs/2506.02129)