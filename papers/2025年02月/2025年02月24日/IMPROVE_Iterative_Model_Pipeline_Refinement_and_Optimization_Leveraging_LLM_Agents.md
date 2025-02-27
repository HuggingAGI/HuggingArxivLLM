# # IMPROVE：利用LLM代理进行迭代模型管道精炼与优化

发布时间：2025年02月24日

`LLM应用` `计算机视觉` `机器学习自动化`

> IMPROVE: Iterative Model Pipeline Refinement and Optimization Leveraging LLM Agents

# 摘要

> # 计算机视觉
计算机视觉在农业中的植物监测和数字系统中的手写分类等众多现实应用中扮演着关键角色。然而，传统上开发高性能计算机视觉模型需要机器学习（ML）专业知识和特定领域的知识，这使得过程昂贵、劳动密集且难以普及。大型语言模型（LLM）代理作为一种有前景的解决方案，旨在自动化这一流程，但现有方法普遍存在一个局限：它们试图在评估前一次性优化整个管道，使得难以将改进归因于具体更改。这种缺乏粒度的优化导致不稳定性和收敛速度减慢，限制了它们的有效性。为了解决这一问题，我们引入了迭代细化（Iterative Refinement），这是一种受人类ML专家逐步优化模型启发的LLM驱动ML管道设计新策略，专注于一次改进一个组件，而不是一次性进行广泛更改。通过根据实际训练反馈系统地更新各个组件，迭代细化提升了稳定性、可解释性和整体模型性能。我们在IMPROVE中实现了这一策略，IMPROVE是一个端到端的LLM代理框架，用于自动化和优化对象分类管道。通过在不同规模和领域（包括标准基准和Kaggle竞赛数据集）的数据集上进行广泛评估，我们证明了迭代细化使IMPROVE能够持续超越现有零-shot LLM基线方法的性能。这些发现确立了迭代细化作为LLM驱动ML自动化的有效新策略，并将IMPROVE定位为无需ML专业知识即可构建高质量计算机视觉模型的可及解决方案。

> Computer vision is a critical component in a wide range of real-world applications, including plant monitoring in agriculture and handwriting classification in digital systems. However, developing high-performance computer vision models traditionally demands both machine learning (ML) expertise and domain-specific knowledge, making the process costly, labor-intensive, and inaccessible to many. Large language model (LLM) agents have emerged as a promising solution to automate this workflow, but most existing methods share a common limitation: they attempt to optimize entire pipelines in a single step before evaluation, making it difficult to attribute improvements to specific changes. This lack of granularity leads to unstable optimization and slower convergence, limiting their effectiveness. To address this, we introduce Iterative Refinement, a novel strategy for LLM-driven ML pipeline design inspired by how human ML experts iteratively refine models, focusing on one component at a time rather than making sweeping changes all at once. By systematically updating individual components based on real training feedback, Iterative Refinement improves stability, interpretability, and overall model performance. We implement this strategy in IMPROVE, an end-to-end LLM agent framework for automating and optimizing object classification pipelines. Through extensive evaluations across datasets of varying sizes and domains, including standard benchmarks and Kaggle competition datasets, we demonstrate that Iterative Refinement enables IMPROVE to consistently achieve better performance over existing zero-shot LLM-based approaches. These findings establish Iterative Refinement as an effective new strategy for LLM-driven ML automation and position IMPROVE as an accessible solution for building high-quality computer vision models without requiring ML expertise.

[Arxiv](https://arxiv.org/abs/2502.18530)