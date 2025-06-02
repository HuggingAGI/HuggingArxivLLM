# # 优化知识图谱与大语言模型的交互，提升复杂推理能力

发布时间：2025年05月30日

`LLM应用` `知识图谱` `问答系统`

> Optimizing the Interface Between Knowledge Graphs and LLMs for Complex Reasoning

# 摘要

> 大型语言模型（LLMs）与知识图谱（KGs）的结合催生出复杂的系统，这些系统中的超参数直接影响性能表现。尽管此类系统在检索增强生成领域日益普及，但系统性超参数优化的重要性仍未得到充分挖掘。本文以Cognee框架为研究对象，该框架用于端到端的知识图谱构建与检索。我们针对HotPotQA、TwoWikiMultiHop 和 MuSiQue三个多跳问答基准数据集，优化了分块、图构建、检索和提示相关的参数。每个配置均采用精确匹配、F1 和 DeepEval 的基于LLM的正确性指标进行评分。我们的实验结果表明，通过有针对性的调整可以实现显著的性能提升。尽管提升效果总体一致，但具体表现因数据集和指标而异。这种差异不仅凸显了超参数调优的价值，也揭示了标准评估指标的局限性。本文不仅展示了超参数调优的即时潜力，还指出未来进展不仅需要架构上的突破，还需更清晰的优化和评估框架，尤其是在复杂模块化系统中。

> Integrating Large Language Models (LLMs) with Knowledge Graphs (KGs) results in complex systems with numerous hyperparameters that directly affect performance. While such systems are increasingly common in retrieval-augmented generation, the role of systematic hyperparameter optimization remains underexplored. In this paper, we study this problem in the context of Cognee, a modular framework for end-to-end KG construction and retrieval. Using three multi-hop QA benchmarks (HotPotQA, TwoWikiMultiHop, and MuSiQue) we optimize parameters related to chunking, graph construction, retrieval, and prompting. Each configuration is scored using established metrics (exact match, F1, and DeepEval's LLM-based correctness metric). Our results demonstrate that meaningful gains can be achieved through targeted tuning. While the gains are consistent, they are not uniform, with performance varying across datasets and metrics. This variability highlights both the value of tuning and the limitations of standard evaluation measures. While demonstrating the immediate potential of hyperparameter tuning, we argue that future progress will depend not only on architectural advances but also on clearer frameworks for optimization and evaluation in complex, modular systems.

[Arxiv](https://arxiv.org/abs/2505.24478)