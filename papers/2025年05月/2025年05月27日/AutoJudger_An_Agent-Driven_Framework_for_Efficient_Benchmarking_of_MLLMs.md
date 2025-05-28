# AutoJudger: 基于智能体驱动的多语言大规模语言模型高效基准测试框架

发布时间：2025年05月27日

`Agent

AutoJudger 是一个基于智能体的评估框架，主要创新点在于智能体的使用和评估策略的设计，因此归类为Agent。` `人工智能` `评估框架`

> AutoJudger: An Agent-Driven Framework for Efficient Benchmarking of MLLMs

# 摘要

> 评估多模态大语言模型（MLLMs）的成本日益增加，主要源于基准测试规模的扩大和跨模态复杂性带来的巨大评分需求。为应对这一挑战，我们推出了AutoJudger——一个基于智能体的高效自适应MLLM评估框架，旨在解决不断攀升的评估成本问题。AutoJudger采用项目反应理论（IRT）来评估问题难度，并借助自主评估代理根据模型的实时表现动态筛选最具价值的测试问题。具体而言，AutoJudger整合了两大核心组件：语义感知检索机制，确保所选问题覆盖视觉与语言模态中多样且具挑战性的场景；以及动态内存系统，记录先前评估问题的统计信息，以在整个评估过程中实现连贯且全局知情的问题选择。在四个典型多模态基准测试中的大量实验证明，我们的自适应框架大幅降低了评估成本：AutoJudger只需使用4%的数据，即可达到与完整基准测试相当的90%以上排名准确度，充分展现了其高效性与准确性。

> Evaluating multimodal large language models (MLLMs) is increasingly expensive, as the growing size and cross-modality complexity of benchmarks demand significant scoring efforts. To tackle with this difficulty, we introduce AutoJudger, an agent-driven framework for efficient and adaptive benchmarking of MLLMs that tackles this escalating cost. AutoJudger employs the Item Response Theory (IRT) to estimate the question difficulty and an autonomous evaluation agent to dynamically select the most informative test questions based on the model's real-time performance. Specifically, AutoJudger incorporates two pivotal components: a semantic-aware retrieval mechanism to ensure that selected questions cover diverse and challenging scenarios across both vision and language modalities, and a dynamic memory that maintains contextual statistics of previously evaluated questions to guide coherent and globally informed question selection throughout the evaluation process. Extensive experiments on four representative multimodal benchmarks demonstrate that our adaptive framework dramatically reduces evaluation expenses, i.e. AutoJudger uses only 4% of the data to achieve over 90% ranking accuracy with the full benchmark evaluation on MMT-Bench.

[Arxiv](https://arxiv.org/abs/2505.21389)