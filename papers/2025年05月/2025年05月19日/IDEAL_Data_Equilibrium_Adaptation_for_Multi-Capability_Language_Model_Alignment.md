# IDEAL: 通过数据均衡适配实现多能力语言模型对齐

发布时间：2025年05月19日

`LLM理论

摘要中讨论了大型语言模型（LLMs）的训练方法，特别是如何通过优化混合训练数据集的组成来提升模型的多能力对齐性和性能。这涉及到模型训练策略和数据集优化，属于LLM的理论研究。` `人工智能`

> IDEAL: Data Equilibrium Adaptation for Multi-Capability Language Model Alignment

# 摘要

> 大型语言模型（LLMs）在监督微调（SFT）上的多样化指令数据集上取得了令人瞩目的性能。然而，当同时训练多个能力时，混合训练数据集的组成方式对最终模型性能的影响至关重要。与许多专注于提升训练数据质量的研究不同，我们探讨了混合训练数据集的组成数量与大型语言模型的新兴能力之间的复杂关系。在高质量多领域训练数据集的基础上，理解每个领域数据对模型整体能力的影响对于准备SFT数据并训练一个在多样化领域中表现优异的均衡模型至关重要。为此，我们提出了IDEAL框架，这是一个创新的数据均衡适配框架，旨在优化混合SFT数据集中不同领域数据的量，从而提升模型在多能力上的对齐性和性能。IDEAL采用基于梯度的方法，迭代优化多领域SFT训练数据集中的数据量，从而提升模型在多能力上的对齐性和性能。通过这一自适应机制，IDEAL确保了数据集组成的均衡性，使模型能够在多样化任务中实现稳健的泛化和一致的熟练度。实验结果表明，IDEAL超越了传统的均匀数据分配策略，在多任务评估分数上实现了全面提升，平均提升约7%。

> Large Language Models (LLMs) have achieved impressive performance through Supervised Fine-tuning (SFT) on diverse instructional datasets. When training on multiple capabilities simultaneously, the mixture training dataset, governed by volumes of data from different domains, is a critical factor that directly impacts the final model's performance. Unlike many studies that focus on enhancing the quality of training datasets through data selection methods, few works explore the intricate relationship between the compositional quantity of mixture training datasets and the emergent capabilities of LLMs. Given the availability of a high-quality multi-domain training dataset, understanding the impact of data from each domain on the model's overall capabilities is crucial for preparing SFT data and training a well-balanced model that performs effectively across diverse domains. In this work, we introduce IDEAL, an innovative data equilibrium adaptation framework designed to effectively optimize volumes of data from different domains within mixture SFT datasets, thereby enhancing the model's alignment and performance across multiple capabilities. IDEAL employs a gradient-based approach to iteratively refine the training data distribution, dynamically adjusting the volumes of domain-specific data based on their impact on downstream task performance. By leveraging this adaptive mechanism, IDEAL ensures a balanced dataset composition, enabling the model to achieve robust generalization and consistent proficiency across diverse tasks. Experiments across different capabilities demonstrate that IDEAL outperforms conventional uniform data allocation strategies, achieving a comprehensive improvement of approximately 7% in multi-task evaluation scores.

[Arxiv](https://arxiv.org/abs/2505.12762)