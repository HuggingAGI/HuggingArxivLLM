# 深入解析 LoRA 干扰机制：正交子空间实现稳健模型融合

发布时间：2025年05月28日

`LLM理论` `模型合并`

> Unraveling LoRA Interference: Orthogonal Subspaces for Robust Model Merging

# 摘要

> 针对特定任务微调大型语言模型（LMs）能够取得优异的性能，但在部署和存储方面成本高昂。近期的研究探索了模型合并技术，旨在将多个特定任务的模型整合成一个多功能的多任务模型，而无需额外的训练。然而，现有的模型合并方法在处理经过低秩适配（LoRA）微调的模型时常常效果不佳，导致性能大幅下降。本文中，我们揭示这一问题源于模型参数与数据分布之间一种先前被忽视的交互作用。为此，我们提出了一种名为正交子空间稳健模型合并（Orthogonal Subspaces for Robust Model Merging，OSRM）的方法，在微调之前对LoRA子空间进行约束，确保一个任务相关的更新不会对其他任务的输出产生不利影响。我们的方法能够无缝集成到大多数现有的模型合并算法中，从而减少任务之间的意外干扰。通过在八个数据集上的广泛实验，使用三种常用的LM和两种大型LM进行测试，结果表明我们的方法不仅提升了模型合并的性能，还保留了单任务的准确性。此外，我们的方法在合并超参数方面表现出更强的鲁棒性。这些结果突显了数据与参数交互在模型合并中的重要性，并为合并LoRA模型提供了一个即插即用的解决方案。

> Fine-tuning large language models (LMs) for individual tasks yields strong performance but is expensive for deployment and storage. Recent works explore model merging to combine multiple task-specific models into a single multi-task model without additional training. However, existing merging methods often fail for models fine-tuned with low-rank adaptation (LoRA), due to significant performance degradation. In this paper, we show that this issue arises from a previously overlooked interplay between model parameters and data distributions. We propose Orthogonal Subspaces for Robust model Merging (OSRM) to constrain the LoRA subspace *prior* to fine-tuning, ensuring that updates relevant to one task do not adversely shift outputs for others. Our approach can seamlessly integrate with most existing merging algorithms, reducing the unintended interference among tasks. Extensive experiments on eight datasets, tested with three widely used LMs and two large LMs, demonstrate that our method not only boosts merging performance but also preserves single-task accuracy. Furthermore, our approach exhibits greater robustness to the hyperparameters of merging. These results highlight the importance of data-parameter interaction in model merging and offer a plug-and-play solution for merging LoRA models.

[Arxiv](https://arxiv.org/abs/2505.22934)