# LREF：专为电子商务设计的新型基于LLM相关性框架

发布时间：2025年03月12日

`LLM应用`

> LREF: A Novel LLM-based Relevance Framework for E-commerce

# 摘要

> 查询与产品相关性预测是提升电商搜索体验的核心技术。传统方法主要依赖BERT模型评估语义相关性，但其判别能力有限，难以全面理解查询与产品的关联。随着大型语言模型（LLMs）的突破，研究者开始探索其在工业搜索中的应用，因其拥有丰富知识和灵活的推理能力。然而，直接应用LLMs进行相关性预测面临数据质量要求高、推理过程优化复杂以及易过度召回等挑战。为此，我们提出了一种名为LREF（基于LLM的相关性框架）的创新方案，旨在提升电商搜索的相关性。该框架包含三个核心阶段：带数据选择的监督微调（SFT）、多链式思维（Multi-CoT）调优，以及用于去偏的直接偏好优化（DPO）。通过大规模真实数据集的离线实验和线上A/B测试，我们验证了该框架的有效性，结果显示其在离线和在线指标上均有显著提升。最终，该方案成功应用于某知名电商平台，产生了可观的商业价值。

> Query and product relevance prediction is a critical component for ensuring a smooth user experience in e-commerce search. Traditional studies mainly focus on BERT-based models to assess the semantic relevance between queries and products. However, the discriminative paradigm and limited knowledge capacity of these approaches restrict their ability to comprehend the relevance between queries and products fully. With the rapid advancement of Large Language Models (LLMs), recent research has begun to explore their application to industrial search systems, as LLMs provide extensive world knowledge and flexible optimization for reasoning processes. Nonetheless, directly leveraging LLMs for relevance prediction tasks introduces new challenges, including a high demand for data quality, the necessity for meticulous optimization of reasoning processes, and an optimistic bias that can result in over-recall. To overcome the above problems, this paper proposes a novel framework called the LLM-based RElevance Framework (LREF) aimed at enhancing e-commerce search relevance. The framework comprises three main stages: supervised fine-tuning (SFT) with Data Selection, Multiple Chain of Thought (Multi-CoT) tuning, and Direct Preference Optimization (DPO) for de-biasing. We evaluate the performance of the framework through a series of offline experiments on large-scale real-world datasets, as well as online A/B testing. The results indicate significant improvements in both offline and online metrics. Ultimately, the model was deployed in a well-known e-commerce application, yielding substantial commercial benefits.

[Arxiv](https://arxiv.org/abs/2503.09223)