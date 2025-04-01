# SPIO: 基于 LLM 的多智能体规划实现自动化数据科学中的集成与选择性策略

发布时间：2025年03月30日

`LLM应用` `机器学习` `数据分析`

> SPIO: Ensemble and Selective Strategies via LLM-Based Multi-Agent Planning in Automated Data Science

# 摘要

> 大型语言模型（LLMs）凭借其强大的动态推理能力，正在彻底改变自动化数据分析和机器学习领域。然而，尽管现有方法通过多智能体系统实现了多阶段流水线的优化，但其 rigid、single-path 的工作流设计限制了多样化策略的探索和整合，往往导致预测效果不尽如人意。为了解决这一难题，我们提出了 SPIO（Sequential Plan Integration and Optimization）框架，该框架创新性地利用 LLM 驱动决策-making，协调数据预处理、特征工程、建模和超参数调整四大核心模块的多智能体规划。在每个模块中，专用规划智能体独立生成候选策略，并将其传递至后续阶段，从而实现全面的策略探索。同时，计划优化智能体通过提出多个优化方案进一步完善这些策略。我们还开发了两种变体：SPIO-S 根据 LLM 的判断选择最优解决方案路径；SPIO-E 则选择前 k 个候选计划并进行集成，以最大化预测性能。实验结果表明，SPIO 在 Kaggle 和 OpenML 数据集上显著超越现有方法，为自动化数据科学任务提供了强大且可扩展的解决方案。

> Large Language Models (LLMs) have revolutionized automated data analytics and machine learning by enabling dynamic reasoning and adaptability. While recent approaches have advanced multi-stage pipelines through multi-agent systems, they typically rely on rigid, single-path workflows that limit the exploration and integration of diverse strategies, often resulting in suboptimal predictions. To address these challenges, we propose SPIO (Sequential Plan Integration and Optimization), a novel framework that leverages LLM-driven decision-making to orchestrate multi-agent planning across four key modules: data preprocessing, feature engineering, modeling, and hyperparameter tuning. In each module, dedicated planning agents independently generate candidate strategies that cascade into subsequent stages, fostering comprehensive exploration. A plan optimization agent refines these strategies by suggesting several optimized plans. We further introduce two variants: SPIO-S, which selects a single best solution path as determined by the LLM, and SPIO-E, which selects the top k candidate plans and ensembles them to maximize predictive performance. Extensive experiments on Kaggle and OpenML datasets demonstrate that SPIO significantly outperforms state-of-the-art methods, providing a robust and scalable solution for automated data science task.

[Arxiv](https://arxiv.org/abs/2503.23314)