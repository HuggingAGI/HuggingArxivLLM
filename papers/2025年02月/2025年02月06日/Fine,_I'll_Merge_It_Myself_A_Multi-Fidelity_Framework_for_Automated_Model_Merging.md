# 自己动手，丰衣足食：自动化模型合并的多保真度框架

发布时间：2025年02月06日

`LLM理论

解释：这篇论文主要讨论了如何通过自动化模型合并框架来提升LLMs的推理能力，而不需要重新训练模型。这涉及到对LLMs的理论研究和优化方法的探索，因此归类为LLM理论。` `人工智能` `模型优化`

> Fine, I'll Merge It Myself: A Multi-Fidelity Framework for Automated Model Merging

# 摘要

> 推理能力是LLMs的关键前沿，但其开发需要大量专有数据和计算资源。模型合并是一种高效补充能力的方式，它无需重新训练即可组合多个模型。然而，现有合并方法依赖手动设计的超参数策略，限制了模型组合的探索，且耗费大量人力。我们提出了一个自动化模型合并框架，支持精细探索合并策略，并通过多保真度近似降低成本。该框架支持单目标和多目标优化，并引入了分层融合（LFS）和深度集成（DIS）两个新搜索空间。在多个基准测试中，我们发现搜索自主找到了1）即使在已微调任务上也能提升单目标性能的合并，以及2）跨任务优化多目标前沿的合并。这些有效合并可在有限计算资源下实现，例如在不到500个搜索步骤内完成。

> Reasoning capabilities represent a critical frontier for large language models (LLMs), but developing them requires extensive proprietary datasets and computational resources. One way to efficiently supplement capabilities with is by model merging, which offers a promising alternative by combining multiple models without retraining. However, current merging approaches rely on manually-designed strategies for merging hyperparameters, limiting the exploration of potential model combinations and requiring significant human effort. We propose an Automated Model Merging Framework that enables fine-grained exploration of merging strategies while reducing costs through multi-fidelity approximations. We support both single and multi-objective optimization and introduce two novel search spaces: layerwise fusion (LFS) and depth-wise integration (DIS). Evaluating across a number of benchmarks, we find that the search autonomously finds 1) Merges that further boost single-objective performance, even on tasks the model has already been finetuned on, and 2) Merges that optimize multi-objective frontiers across tasks. Effective merges are found with limited compute, e.g. within less than 500 search steps.

[Arxiv](https://arxiv.org/abs/2502.04030)