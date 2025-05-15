# LLM 推理机制的统计建模方法与不确定性评估

发布时间：2025年05月14日

`LLM应用` `人工智能` `系统性能优化`

> Statistical Modeling and Uncertainty Estimation of LLM Inference Systems

# 摘要

> 大型语言模型（LLM）推理系统在统计性能分析方面面临多重挑战，包括动态工作负载变化、多样化的硬件架构，以及模型规模、批处理和吞吐量需求之间的复杂交互。精确的统计分析对提升大规模AI部署效率至关重要，它能够优化工作负载调度、实现自适应资源供给和成本敏感的推理优化。传统解析模型虽具有可解释性，但无法涵盖现实世界工作负载的多样性，因此无法预先为所有场景建立基准。机器学习（ML）方法能有效预测非基准场景的性能，但在超出训练数据范围时表现乏力。为克服这些局限性，我们针对LLM推理系统提出了一种结合解析建模与机器学习的增强框架（ALA），旨在实现LLM推理工作负载的稳健统计预测和不确定性评估。我们的方法基于针对基准工作负载的解析吞吐量模型，通过机器学习预测扩展至未观测配置。我们引入模拟退火技术，挖掘工作负载数据点组合的子集，并开发误差预测器。最终，我们基于新旧工作负载在向量空间中的相似性量化不确定性，以确保稳健的泛化能力。通过在多样化LLM推理工作负载上的广泛实验，我们验证了我们的框架在保持对新推理场景适应性的同时，实现了较低的中位误差。

> Large Language Model (LLM) inference systems present significant challenges in statistical performance characterization due to dynamic workload variations, diverse hardware architectures, and complex interactions between model size, batch processing, and throughput requirements. Accurate statistical characterization enables better workload scheduling, adaptive resource provisioning, and cost-aware inference optimization, making it crucial for improving efficiency in large-scale AI deployments. Traditional analytical models provide explainability but cannot cover the vast diversity of real-world workloads, making it impossible to benchmark every scenario in advance. Machine learning (ML) approaches effectively predict performance for non-benchmarked cases but struggle when extrapolating beyond their observed training space. To address these limitations for LLM inference systems, we propose an Analytical with Learning Augmentation (ALA) framework that bridges analytical modeling with \ml for robust statistical prediction and uncertainty estimation in LLM inference workloads. Our method employs an analytical throughput model with parameters estimated for benchmarked workloads, then extends to unobserved configurations using \ml predictions. We enhance this with simulated annealing to exploit subsets of the workload data point combinations and develop an error predictor. Finally, we quantify uncertainty based on vector space similarity between new and observed workloads to ensure robust generalization. Through extensive experimentation on diverse LLM inference workloads, we demonstrate that our framework achieves low median errors while maintaining adaptability to new inference scenarios.

[Arxiv](https://arxiv.org/abs/2505.09319)