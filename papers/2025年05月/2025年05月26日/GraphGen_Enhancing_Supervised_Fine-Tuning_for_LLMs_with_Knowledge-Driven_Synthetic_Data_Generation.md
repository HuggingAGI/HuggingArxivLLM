# GraphGen —— 一种通过知识驱动的合成数据生成，优化针对大型语言模型的监督微调的方法

发布时间：2025年05月26日

`LLM应用` `知识图谱` `问答系统`

> GraphGen: Enhancing Supervised Fine-Tuning for LLMs with Knowledge-Driven Synthetic Data Generation

# 摘要

> LLMs的微调通常需要大量高质量的监督数据，获取成本高且耗时。虽然合成数据生成技术已崭露头角，但现有方法仍存在事实不准确、长尾覆盖不足、知识结构简单及输出同质化等问题。为解决这些难题，我们推出了GraphGen——一个基于知识图谱的框架，专为原子QA、聚合QA和多跳QA三大场景设计。GraphGen首先构建细粒度知识图谱，然后通过预期校准误差指标识别LLMs的知识缺口，优先生成针对高价值长尾知识的QA对。此外，它还采用多跳邻域采样捕捉复杂关联信息，并借助风格控制生成多样化QA数据。在闭书设置下的知识密集型任务中，GraphGen超越传统合成数据方法，为监督微调中的数据稀缺性难题提供了更可靠、全面的解决方案。代码和数据已开源，详情请访问https://github.com/open-sciencelab/GraphGen。

> Fine-tuning for large language models (LLMs) typically requires substantial amounts of high-quality supervised data, which is both costly and labor-intensive to acquire. While synthetic data generation has emerged as a promising solution, existing approaches frequently suffer from factual inaccuracies, insufficient long-tail coverage, simplistic knowledge structures, and homogenized outputs. To address these challenges, we introduce GraphGen, a knowledge graph-guided framework designed for three key question-answering (QA) scenarios: atomic QA, aggregated QA, and multi-hop QA. It begins by constructing a fine-grained knowledge graph from the source text. It then identifies knowledge gaps in LLMs using the expected calibration error metric, prioritizing the generation of QA pairs that target high-value, long-tail knowledge. Furthermore, GraphGen incorporates multi-hop neighborhood sampling to capture complex relational information and employs style-controlled generation to diversify the resulting QA data. Experimental results on knowledge-intensive tasks under closed-book settings demonstrate that GraphGen outperforms conventional synthetic data methods, offering a more reliable and comprehensive solution to the data scarcity challenge in supervised fine-tuning. The code and data are publicly available at https://github.com/open-sciencelab/GraphGen.

[Arxiv](https://arxiv.org/abs/2505.20416)