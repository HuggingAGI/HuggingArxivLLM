# # C3PO：关键层、核心专家与协同路径优化，实现测试时的专家重混合

发布时间：2025年04月10日

`LLM理论` `人工智能`

> C3PO: Critical-Layer, Core-Expert, Collaborative Pathway Optimization for Test-Time Expert Re-Mixing

# 摘要

> 混合专家模型（MoE）大型语言模型（LLMs）存在严重次优的专家路径——我们的研究表明，简单专家选择方法竟然留下了一个令人惊讶的10-20%的准确性提升空间。基于这一发现，我们开发了一类全新的测试时优化方法，旨在为每个测试样本重新加权或“重新混合”不同层中的专家。由于测试样本的真实标签未知，我们建议通过优化由参考样本集中的“成功邻居”定义的替代目标来实现这一目标。我们引入了三种基于模态查找、核回归和相似参考样本/任务平均损失的替代方法和算法。为了降低优化整个路径的成本，我们将算法仅应用于关键层中核心专家的混合权重，这种方法性能相似但节省了大量计算资源。这引出了“关键层、核心专家、协作路径优化（C3PO）”。我们将C3PO应用于两个近期的MoE LLM，并在六个广泛使用的基准测试中进行评估。它始终将基线模型的准确性提高了7-15%，并且显著超越了广泛使用的测试时学习基线方法，如上下文学习和提示/前缀调整。此外，C3PO使具有1-3B活跃参数的MoE LLM能够超越7-9B参数的LLMs，从而提升了MoE在效率方面的优势。我们彻底的消融研究进一步为实现MoE的测试时改进提供了新的见解。

> Mixture-of-Experts (MoE) Large Language Models (LLMs) suffer from severely sub-optimal expert pathways-our study reveals that naive expert selection learned from pretraining leaves a surprising 10-20% accuracy gap for improvement. Motivated by this observation, we develop a novel class of test-time optimization methods to re-weight or "re-mixing" the experts in different layers jointly for each test sample. Since the test sample's ground truth is unknown, we propose to optimize a surrogate objective defined by the sample's "successful neighbors" from a reference set of samples. We introduce three surrogates and algorithms based on mode-finding, kernel regression, and the average loss of similar reference samples/tasks. To reduce the cost of optimizing whole pathways, we apply our algorithms merely to the core experts' mixing weights in critical layers, which enjoy similar performance but save significant computation. This leads to "Critical-Layer, Core-Expert, Collaborative Pathway Optimization (C3PO)". We apply C3PO to two recent MoE LLMs and examine it on six widely-used benchmarks. It consistently improves the base model by 7-15% in accuracy and outperforms widely used test-time learning baselines, e.g., in-context learning and prompt/prefix tuning, by a large margin. Moreover, C3PO enables MoE LLMs with 1-3B active parameters to outperform LLMs of 7-9B parameters, hence improving MoE's advantages on efficiency. Our thorough ablation study further sheds novel insights on achieving test-time improvement on MoE.

[Arxiv](https://arxiv.org/abs/2504.07964)