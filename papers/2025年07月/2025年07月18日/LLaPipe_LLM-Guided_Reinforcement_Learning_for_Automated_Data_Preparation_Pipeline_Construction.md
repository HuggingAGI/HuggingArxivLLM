# LLaPipe：LLM引导的强化学习，助力自动化数据准备管道构建

发布时间：2025年07月18日

`LLM应用` `机器学习` `数据科学`

> LLaPipe: LLM-Guided Reinforcement Learning for Automated Data Preparation Pipeline Construction

# 摘要

> 自动化数据准备是实现机器学习民主化的关键，但现有基于强化学习（RL）的方法在庞大的预处理流水线空间中探索效率低下。为此，我们提出了LLaPipe——一个全新的框架，通过将大型语言模型（LLMs）作为智能策略顾问，有效突破这一探索瓶颈。与传统方法仅依赖统计特征和盲目试错不同，LLaPipe创新性地利用LLMs的语义理解能力，提供上下文相关的探索指导。框架的核心创新包括：（1）LLM策略顾问，通过分析数据集语义和流水线历史，建议有前景的预处理操作；（2）经验蒸馏机制，从过去的流水线中挖掘成功模式，并迁移这些知识以指导未来的探索；（3）自适应顾问触发策略（Advisor	extsuperscript{+}），动态确定LLM干预的最佳时机，在平衡探索效果与计算成本之间取得优化。通过在涵盖多个领域的18个多样化数据集上的广泛实验，我们证明了LLaPipe相较于最先进的RL基方法，在流水线质量上实现了高达22.4%的提升，收敛速度提高了2.3倍，同时通过选择性地使用LLM保持了计算效率（平均仅占总探索步骤的19.0%）。

> Automated data preparation is crucial for democratizing machine learning, yet existing reinforcement learning (RL) based approaches suffer from inefficient exploration in the vast space of possible preprocessing pipelines. We present LLaPipe, a novel framework that addresses this exploration bottleneck by integrating Large Language Models (LLMs) as intelligent policy advisors. Unlike traditional methods that rely solely on statistical features and blind trial-and-error, LLaPipe leverages the semantic understanding capabilities of LLMs to provide contextually relevant exploration guidance. Our framework introduces three key innovations: (1) an LLM Policy Advisor that analyzes dataset semantics and pipeline history to suggest promising preprocessing operations, (2) an Experience Distillation mechanism that mines successful patterns from past pipelines and transfers this knowledge to guide future exploration, and (3) an Adaptive Advisor Triggering strategy (Advisor\textsuperscript{+}) that dynamically determines when LLM intervention is most beneficial, balancing exploration effectiveness with computational cost. Through extensive experiments on 18 diverse datasets spanning multiple domains, we demonstrate that LLaPipe achieves up to 22.4\% improvement in pipeline quality and 2.3$\times$ faster convergence compared to state-of-the-art RL-based methods, while maintaining computational efficiency through selective LLM usage (averaging only 19.0\% of total exploration steps).

[Arxiv](https://arxiv.org/abs/2507.13712)