# Linq-Embed-Mistral 技术报告

发布时间：2024年12月04日

`LLM应用` `数据处理` `文本检索`

> Linq-Embed-Mistral Technical Report

# 摘要

> 本报告探究了运用先进的数据精炼技术提升文本检索性能。我们基于 E5-mistral 和 Mistral-7B-v0.1 模型开发了 Linq-Embed-Mistralootnote{url{https://huggingface.co/Linq-AI-Research/Linq-Embed-Mistral}} ，着重于复杂的数据处理、数据过滤和负样本挖掘方法，这些方法高度适配每个任务，应用于既有基准数据集和通过大型语言模型（LLMs）生成的高度定制化合成数据集。Linq-Embed-Mistral 在 MTEB 基准测试中表现出众（截至 2024 年 5 月 29 日），在 56 个数据集中平均得分 68.2，在 MTEB 排行榜的检索任务中所有模型里排名第一，性能得分 60.2。此成绩彰显了其在提高搜索精度和可靠性方面的超强能力。我们的贡献涵盖了能显著提升基准和合成数据集上模型性能的先进数据精炼方法、用于同质任务排序和混合任务微调以增强模型泛化和稳定性的技术，以及采用 4 位精度和轻量检索评估集的简化评估流程，在不损失准确性的前提下加快验证。

> This report explores the enhancement of text retrieval performance using advanced data refinement techniques. We develop Linq-Embed-Mistral\footnote{url{https://huggingface.co/Linq-AI-Research/Linq-Embed-Mistral}} by building on the E5-mistral and Mistral-7B-v0.1 models, focusing on sophisticated data crafting, data filtering, and negative mining methods, which are highly tailored to each task, applied to both existing benchmark dataset and highly tailored synthetic dataset generated via large language models (LLMs). Linq-Embed-Mistral excels in the MTEB benchmarks (as of May 29, 2024), achieving an average score of 68.2 across 56 datasets, and ranks 1st among all models for retrieval tasks on the MTEB leaderboard with a performance score of 60.2. This performance underscores its superior capability in enhancing search precision and reliability. Our contributions include advanced data refinement methods that significantly improve model performance on benchmark and synthetic datasets, techniques for homogeneous task ordering and mixed task fine-tuning to enhance model generalization and stability, and a streamlined evaluation process using 4-bit precision and a light retrieval evaluation set, which accelerates validation without sacrificing accuracy.

[Arxiv](https://arxiv.org/abs/2412.03223)