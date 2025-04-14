# **TP-RAG**：用于时空感知旅行规划的检索增强型大型语言模型智能体基准测试

发布时间：2025年04月11日

`LLM应用

理由：这篇论文探讨了大型语言模型在旅行规划中的应用，特别是通过RAG（检索增强生成）方法来提升规划的时空合理性和兴趣点的合理性。研究中提出的EvoRAG框架结合了多样化的检索轨迹与LLMs的推理能力，旨在优化旅行规划的效率和质量。因此，这篇论文主要属于LLM在实际应用中的研究，即LLM应用类别。` `旅行规划` `人工智能`

> TP-RAG: Benchmarking Retrieval-Augmented Large Language Model Agents for Spatiotemporal-Aware Travel Planning

# 摘要

> 大型语言模型（LLMs）在旅行规划自动化方面潜力巨大，但往往难以应对复杂的时空合理性问题。现有基准测试虽然关注基本计划的有效性，却忽视了路线效率、兴趣点吸引力及实时适应性等关键因素。本文推出首个专为检索增强型、时空感知旅行规划设计的基准——TP-RAG。我们的数据集包含2,348个真实旅行查询、85,575个细粒度标注的兴趣点以及18,784个高质量旅行轨迹参考，均源自在线旅游文档，支持动态且情境感知的规划。实验结果表明，整合参考轨迹显著提升了旅行计划的空间效率和兴趣点合理性，但在普遍性和鲁棒性方面仍面临挑战，主要源于相互冲突的参考和噪声数据。为此，我们提出了EvoRAG框架，该框架能够有效结合多样检索轨迹与LLMs的内在推理能力，实现最先进的性能。相比从零开始和检索增强的基线方法，EvoRAG在时空合规性方面表现更优，常识违背情况显著减少。我们的研究凸显了将Web知识与LLM驱动优化相结合的潜力，为构建更可靠和自适应的旅行规划代理铺平了道路。

> Large language models (LLMs) have shown promise in automating travel planning, yet they often fall short in addressing nuanced spatiotemporal rationality. While existing benchmarks focus on basic plan validity, they neglect critical aspects such as route efficiency, POI appeal, and real-time adaptability. This paper introduces TP-RAG, the first benchmark tailored for retrieval-augmented, spatiotemporal-aware travel planning. Our dataset includes 2,348 real-world travel queries, 85,575 fine-grain annotated POIs, and 18,784 high-quality travel trajectory references sourced from online tourist documents, enabling dynamic and context-aware planning. Through extensive experiments, we reveal that integrating reference trajectories significantly improves spatial efficiency and POI rationality of the travel plan, while challenges persist in universality and robustness due to conflicting references and noisy data. To address these issues, we propose EvoRAG, an evolutionary framework that potently synergizes diverse retrieved trajectories with LLMs' intrinsic reasoning. EvoRAG achieves state-of-the-art performance, improving spatiotemporal compliance and reducing commonsense violation compared to ground-up and retrieval-augmented baselines. Our work underscores the potential of hybridizing Web knowledge with LLM-driven optimization, paving the way for more reliable and adaptive travel planning agents.

[Arxiv](https://arxiv.org/abs/2504.08694)