# 超越模板：基于可行性探索的推理展示动态调整

发布时间：2025年05月27日

`LLM理论` `模型迁移`

> Beyond Templates: Dynamic Adaptation of Reasoning Demonstrations via Feasibility-Aware Exploration

# 摘要

> 大型语言模型（LLMs）展现出了非凡的推理能力，但将其能力迁移至小型语言模型（SLMs）却面临挑战，这主要是因为分布不匹配和模型容量的限制。现有的推理数据集多为强大的LLMs量身定制，直接应用于较弱的模型时往往效果不佳。我们提出了动态推理轨迹适应（DART），一个全新的数据适应框架，旨在弥合专家推理轨迹与多样化SLMs之间的能力鸿沟。与传统统一模仿专家步骤的方法不同，DART采用基于分步适应性评估的有选择性模仿策略，通过解决方案模拟实现。当专家步骤超出学生模型的容量——由模仿差距信号指示时，学生会自主探索替代推理路径，同时确保结果一致性。我们在多个推理基准测试和不同规模的模型上验证了DART，结果表明，与静态微调相比，它在通用性和数据效率方面均有显著提升。通过将训练信号与学生的推理能力对齐，DART提高了监督质量，为资源受限模型的推理对齐提供了一种可扩展的解决方案。

> Large language models (LLMs) have shown remarkable reasoning capabilities, yet aligning such abilities to small language models (SLMs) remains a challenge due to distributional mismatches and limited model capacity. Existing reasoning datasets, typically designed for powerful LLMs, often lead to degraded performance when directly applied to weaker models. In this work, we introduce Dynamic Adaptation of Reasoning Trajectories (DART), a novel data adaptation framework that bridges the capability gap between expert reasoning trajectories and diverse SLMs. Instead of uniformly imitating expert steps, DART employs a selective imitation strategy guided by step-wise adaptability estimation via solution simulation. When expert steps surpass the student's capacity -- signaled by an Imitation Gap -- the student autonomously explores alternative reasoning paths, constrained by outcome consistency. We validate DART across multiple reasoning benchmarks and model scales, demonstrating that it significantly improves generalization and data efficiency over static fine-tuning. Our method enhances supervision quality by aligning training signals with the student's reasoning capabilities, offering a scalable solution for reasoning alignment in resource-constrained models.

[Arxiv](https://arxiv.org/abs/2505.20700)