# Middo：模型感知动态数据优化——借助闭环学习提升LLM微调效果

发布时间：2025年08月29日

`LLM应用` `基础理论`

> Middo: Model-Informed Dynamic Data Optimization for Enhanced LLM Fine-Tuning via Closed-Loop Learning

# 摘要

> 监督微调（SFT）大型语言模型（LLM）的核心在于高质量训练数据。尽管数据选择与合成是提升数据质量的两大常用策略，但现有方法在静态数据集构建中存在局限，难以适应模型能力的持续进化。本文提出Middo——一个自进化的模型感知动态数据优化框架，它结合模型感知的数据选择与上下文保留的数据优化机制。不同于传统的一次性过滤/合成方法，我们的框架构建了闭环优化系统：(1) 自指诊断模块通过三轴模型信号主动识别次优样本：损失模式（复杂度）、嵌入簇动态（多样性）及自对齐分数（质量）；(2) 自适应优化引擎进而将次优样本转化为教学价值训练样本，同时保留语义完整性；(3) 整个优化过程基于动态学习原理，随模型能力提升而持续进化。多基准实验表明，我们的方法在维持原始数据集规模的前提下，持续提升种子数据质量与LLM性能，平均准确率提高7.15%。这项研究通过数据与模型的动态人机协同进化，为LLM的可持续训练开辟了新范式。相关数据集、模型及代码即将发布。

> Supervised Fine-Tuning (SFT) Large Language Models (LLM) fundamentally rely on high-quality training data. While data selection and data synthesis are two common strategies to improve data quality, existing approaches often face limitations in static dataset curation that fail to adapt to evolving model capabilities. In this paper, we introduce Middo, a self-evolving Model-informed dynamic data optimization framework that uses model-aware data selection and context-preserving data refinement. Unlike conventional one-off filtering/synthesis methods, our framework establishes a closed-loop optimization system: (1) A self-referential diagnostic module proactively identifies suboptimal samples through tri-axial model signals - loss patterns (complexity), embedding cluster dynamics (diversity), and self-alignment scores (quality); (2) An adaptive optimization engine then transforms suboptimal samples into pedagogically valuable training points while preserving semantic integrity; (3) This optimization process continuously evolves with model capability through dynamic learning principles. Experiments on multiple benchmarks demonstrate that our \method consistently enhances the quality of seed data and boosts LLM's performance with improving accuracy by 7.15% on average while maintaining the original dataset scale. This work establishes a new paradigm for sustainable LLM training through dynamic human-AI co-evolution of data and models. Our datasets, models, and code are coming soon.

[Arxiv](https://arxiv.org/abs/2508.21589)