# BixBench：计算生物学领域首个全面评估基于大语言模型智能体的基准测试平台。

发布时间：2025年02月28日

`Agent` `生物信息学` `科学研究`

> BixBench: a Comprehensive Benchmark for LLM-based Agents in Computational Biology

# 摘要

> 大型语言模型（LLMs）及其驱动的智能体在加速科学研究方面展现出巨大潜力。现有的评估这一潜力并指导未来发展的基准测试，正在从单纯的回忆和死记硬背任务，逐步转向更具实用价值的工作，例如文献综述和实验规划。生物信息学是一个有望实现完全自主AI驱动发现的领域，但迄今为止尚未有全面的基准测试来衡量相关进展。因此，我们提出了生物信息学基准测试（BixBench），这是一个包含超过50个真实世界生物数据分析场景的数据集，每个场景配有近300个开放性问题，旨在评估LLM驱动的智能体在探索生物数据集、执行长周期多步骤分析路径以及解读分析结果细微差别方面的能力。我们采用开源的定制智能体框架，对两款前沿大型语言模型（GPT-4o和Claude 3.5 Sonnet）进行了性能评估。结果发现，即使是最前沿的模型，在开放性回答任务中也仅能达到17%的准确率，而在多项选择题中表现甚至不如随机猜测。通过揭示前沿模型当前的局限性，我们希望BixBench能够推动具备严谨生物信息学分析能力的智能体开发，并加速科学研究进程。

> Large Language Models (LLMs) and LLM-based agents show great promise in accelerating scientific research. Existing benchmarks for measuring this potential and guiding future development continue to evolve from pure recall and rote knowledge tasks, towards more practical work such as literature review and experimental planning. Bioinformatics is a domain where fully autonomous AI-driven discovery may be near, but no extensive benchmarks for measuring progress have been introduced to date. We therefore present the Bioinformatics Benchmark (BixBench), a dataset comprising over 50 real-world scenarios of practical biological data analysis with nearly 300 associated open-answer questions designed to measure the ability of LLM-based agents to explore biological datasets, perform long, multi-step analytical trajectories, and interpret the nuanced results of those analyses. We evaluate the performance of two frontier LLMs (GPT-4o and Claude 3.5 Sonnet) using a custom agent framework we open source. We find that even the latest frontier models only achieve 17% accuracy in the open-answer regime, and no better than random in a multiple-choice setting. By exposing the current limitations of frontier models, we hope BixBench can spur the development of agents capable of conducting rigorous bioinformatic analysis and accelerate scientific discovery.

[Arxiv](https://arxiv.org/abs/2503.00096)