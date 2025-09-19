# CodeFuse-CR-Bench：面向Python项目端到端代码审查评估的全面感知评测基准

发布时间：2025年09月18日

`LLM应用` `基础理论`

> CodeFuse-CR-Bench: A Comprehensiveness-aware Benchmark for End-to-End Code Review Evaluation in Python Projects

# 摘要

> 自动化代码审查（CR）是大型语言模型（LLMs）的关键应用，但进展受限于“现实差距”：现有基准仅通过简化、上下文匮乏的数据在孤立子任务上评估模型，完全无法反映现实世界代码审查中整体且上下文丰富的本质。为弥合这一鸿沟，我们推出了CodeFuse-CR-Bench——首个面向仓库级代码审查评估的“全面感知”基准。该基准包含来自70个Python项目的601个高质量实例，覆盖九个拉取请求（PR）问题领域，每个实例均提供丰富的多维度上下文——包括相关问题、PR详情和仓库状态，支持端到端评估。除表面指标外，我们还提出了一个新颖的评估框架，融合了基于规则的位置与语法检查，以及基于模型的审查质量判断。我们首次对最先进的LLMs在这一全面CR任务上展开大规模评估，结果不仅建立了关键基线，还揭示了三大发现：（1）没有任何单一LLM能主导代码审查的所有方面；（2）Gemini 2.5 Pro综合性能最优；（3）不同LLM对冗余上下文的鲁棒性差异显著。这些发现凸显了整体、多维度评估的必要性，并为打造真正智能且实用的代码审查助手提供了切实可行的方向。

> Automated code review (CR) is a key application for Large Language Models (LLMs), but progress is hampered by a "reality gap": existing benchmarks evaluate models on isolated sub-tasks using simplified, context-poor data. This fails to reflect the holistic context-rich nature of real-world CR. To bridge this gap, we introduce CodeFuse-CR-Bench, the first comprehensiveness-aware benchmark for repository-level CR evaluation. CodeFuse-CR-Bench comprises 601 high-quality instances from 70 Python projects covering nine Pull-Request (PR) problem domains, where each instance provides rich, multi-faceted context including the associated issue, PR details, and repository state, enabling end-to-end evaluation. Beyond superficial metrics, we also propose a novel evaluation framework that combines rule-based checks for location and syntax with model-based judgments of review quality. We present the first large-scale assessment of state-of-the-art LLMs on this comprehensive CR task. Our results establish crucial baselines and reveal that (1) no single LLM dominates all aspects of CR; (2) Gemini 2.5 Pro achieves the highest comprehensive performance; and (3) different LLMs exhibit varying robustness to redundant context. These findings highlight the necessity of holistic, multi-dimensional evaluation and provide actionable insights for advancing truly intelligent yet practical CR assistants.

[Arxiv](https://arxiv.org/abs/2509.14856)