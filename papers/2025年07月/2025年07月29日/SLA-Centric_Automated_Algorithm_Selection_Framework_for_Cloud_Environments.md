# # 面向云计算环境的以SLA为中心的自动化算法选择框架

发布时间：2025年07月29日

`其他` `云计算` `资源管理`

> SLA-Centric Automated Algorithm Selection Framework for Cloud Environments

# 摘要

> 云计算提供按需资源访问，通过服务级别协议（SLA）来规范消费者与云服务提供商（CSP）之间的关系。然而，SLA违规可能影响效率和云服务提供商的盈利能力。为此，我们提出了一种针对资源受限云环境中组合优化问题的SLA感知自动化算法选择框架。该框架利用机器学习模型的集成来预测性能，并根据SLA约束对算法-硬件配对进行排序。我们还将该框架应用于0-1背包问题。我们整理了一个数据集，其中包括6种算法的实例特定特征、内存使用情况、运行时间和最优性差距。作为经验基准，我们在分类和回归任务上评估了该框架。我们的消融研究探讨了超参数、学习方法以及大型语言模型在回归中的有效性，以及基于SHAP的可解释性。

> Cloud computing offers on-demand resource access, regulated by Service-Level Agreements (SLAs) between consumers and Cloud Service Providers (CSPs). SLA violations can impact efficiency and CSP profitability. In this work, we propose an SLA-aware automated algorithm-selection framework for combinatorial optimization problems in resource-constrained cloud environments. The framework uses an ensemble of machine learning models to predict performance and rank algorithm-hardware pairs based on SLA constraints. We also apply our framework to the 0-1 knapsack problem. We curate a dataset comprising instance specific features along with memory usage, runtime, and optimality gap for 6 algorithms. As an empirical benchmark, we evaluate the framework on both classification and regression tasks. Our ablation study explores the impact of hyperparameters, learning approaches, and large language models effectiveness in regression, and SHAP-based interpretability.

[Arxiv](https://arxiv.org/abs/2507.21963)