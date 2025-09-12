# 迈向自适应机器学习基准：网络智能体驱动构建、领域扩展与指标优化

发布时间：2025年09月11日

`Agent` `基础理论`

> Towards Adaptive ML Benchmarks: Web-Agent-Driven Construction, Domain Expansion, and Metric Optimization

# 摘要

> 大型语言模型（LLMs）的最新进展催生了通用智能体，能够自动化端到端机器学习（ML）工作流，包括数据分析、特征工程、模型训练及竞赛解题。然而，现有基准在任务覆盖、领域多样性、难度建模和评估严谨性方面仍有不足，无法全面展现这类智能体在真实场景中的能力。为此，我们提出TAM Bench——一个多样化、贴近真实且结构化的基准，用于评估基于LLM的智能体在端到端ML任务上的表现。TAM Bench有三大核心创新：（1）基于浏览器自动化和LLM的任务采集系统，可自动从Kaggle、AIcrowd、Biendata等平台采集并结构化ML挑战，覆盖表格、文本、图像、图、音频等多种任务类型与数据模态；（2）基于排行榜的难度建模机制，通过参与者数量和分数分布估算任务复杂度，实现可扩展且客观的任务校准；（3）多维度评估框架，涵盖性能、格式合规性、约束遵守度及任务泛化能力。基于150个精选AutoML任务，我们构建了三个不同规模的基准子集——精简版（Lite）、标准版（Medium）和完整版（Full），分别适配不同评估场景。其中精简版（Lite）含18个任务，在模态和难度上覆盖均衡，是日常基准测试与比较研究的实用测试平台。

> Recent advances in large language models (LLMs) have enabled the emergence of general-purpose agents for automating end-to-end machine learning (ML) workflows, including data analysis, feature engineering, model training, and competition solving. However, existing benchmarks remain limited in task coverage, domain diversity, difficulty modeling, and evaluation rigor, failing to capture the full capabilities of such agents in realistic settings. We present TAM Bench, a diverse, realistic, and structured benchmark for evaluating LLM-based agents on end-to-end ML tasks. TAM Bench features three key innovations: (1) A browser automation and LLM-based task acquisition system that automatically collects and structures ML challenges from platforms such as Kaggle, AIcrowd, and Biendata, spanning multiple task types and data modalities (e.g., tabular, text, image, graph, audio); (2) A leaderboard-driven difficulty modeling mechanism that estimates task complexity using participant counts and score dispersion, enabling scalable and objective task calibration; (3) A multi-dimensional evaluation framework incorporating performance, format compliance, constraint adherence, and task generalization. Based on 150 curated AutoML tasks, we construct three benchmark subsets of different sizes -- Lite, Medium, and Full -- designed for varying evaluation scenarios. The Lite version, with 18 tasks and balanced coverage across modalities and difficulty levels, serves as a practical testbed for daily benchmarking and comparative studies.

[Arxiv](https://arxiv.org/abs/2509.09321)