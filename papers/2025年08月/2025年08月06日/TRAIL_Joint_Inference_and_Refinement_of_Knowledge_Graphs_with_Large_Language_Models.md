# TRAIL：基于大语言模型的知识图谱联合推理与优化

发布时间：2025年08月06日

`LLM理论` `知识图谱` `问答系统`

> TRAIL: Joint Inference and Refinement of Knowledge Graphs with Large Language Models

# 摘要

> 大型语言模型（LLMs）的最新进展释放了强大的推理与决策能力，但其固有的静态参数内存依赖性却在知识密集型场景中带来了适应性、事实准确性和可解释性的瓶颈。知识图谱（KGs）作为显式关系知识的结构化存储库，为增强大型语言模型提供了有前景的外部可解释记忆解决方案。然而，现有结合LLMs与KGs的方法大多将推理与知识更新割裂开来，导致新信息利用率低下，阻碍了实时更新的实现。

在此，我们提出TRAIL：一种全新的统一框架，整合思考、推理与增量学习，将联合推理与动态知识图谱优化与大型语言模型相结合。TRAIL赋予LLM代理在推理过程中迭代探索、更新和优化知识图谱的能力，采用信心驱动机制实现新事实的生成、验证与修剪。其即插即用的架构支持与各类大型语言模型无缝对接，无需重新训练即可实现持续适应。

在多个基准上的广泛实验表明，TRAIL在性能上超越了现有知识图谱增强与检索增强的LLM基线模型，提升幅度达3%到13%。更重要的是，这一成果标志着向开发具备持续学习能力、可靠且透明推理的自适应增强记忆语言模型迈出了重要一步。


> Recent advances in large language models (LLMs) have unlocked powerful reasoning and decision-making capabilities. However, their inherent dependence on static parametric memory fundamentally limits their adaptability, factual accuracy, and interpretability in knowledge-intensive scenarios. Knowledge graphs (KGs), as structured repositories of explicit relational knowledge, offer a promising approach for augmenting LLMs with external, interpretable memory. Nevertheless, most existing methods that combine LLMs with KGs treat reasoning and knowledge updating as separate processes, resulting in suboptimal utilization of new information and hindering real-time updates. In this work, we propose TRAIL: a novel, unified framework for Thinking, Reasoning, And Incremental Learning that couples joint inference and dynamic KG refinement with large language models. TRAIL enables LLM agents to iteratively explore, update, and refine knowledge graphs during the reasoning process, employing a confidence-driven mechanism for the generation, validation, and pruning of new facts. This plug-and-play architecture facilitates seamless integration with various LLMs, supporting continual adaptation without the need for retraining. Extensive experiments on multiple benchmarks demonstrate that TRAIL outperforms existing KG-augmented and retrieval-augmented LLM baselines by 3% to 13%. More importantly, these results represent a significant step toward developing adaptive, memory-augmented language models capable of continual learning and reliable, transparent reasoning.

[Arxiv](https://arxiv.org/abs/2508.04474)