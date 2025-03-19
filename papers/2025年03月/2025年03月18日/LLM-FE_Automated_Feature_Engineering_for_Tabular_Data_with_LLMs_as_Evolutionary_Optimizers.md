# LLM-FE：以大型语言模型为进化优化器的表格数据自动特征工程

发布时间：2025年03月18日

`LLM应用

摘要中提到，论文将大型语言模型（LLMs）应用于自动化特征工程，提出了一种结合进化搜索与LLMs的框架，以提升表格学习任务的预测性能。这一研究属于将LLMs应用到具体任务中的范畴，因此归类为LLM应用。` `特征工程` `数据分析`

> LLM-FE: Automated Feature Engineering for Tabular Data with LLMs as Evolutionary Optimizers

# 摘要

> 自动化特征工程是提升表格学习任务预测模型性能的关键。传统方法受限于固定搜索空间和预定义变换，往往忽视领域知识。得益于大型语言模型（LLMs）的最新进展，我们能够将领域知识融入特征工程。然而，现有基于LLMs的方法要么依赖直接提示，要么仅依靠验证分数选择特征，未能充分利用以往特征发现的洞察或在特征生成与性能之间建立有效推理。为解决这些挑战，我们提出LLM-FE框架，结合进化搜索与LLMs的领域知识及推理能力，自动发现有效特征。LLM-FE将特征工程视为程序搜索问题，LLMs迭代生成新特征变换，数据反馈则引导搜索方向。实验结果表明，LLM-FE在各类分类和回归基准上均显著超越现有最佳方法，大幅提升了表格预测模型的性能。

> Automated feature engineering plays a critical role in improving predictive model performance for tabular learning tasks. Traditional automated feature engineering methods are limited by their reliance on pre-defined transformations within fixed, manually designed search spaces, often neglecting domain knowledge. Recent advances using Large Language Models (LLMs) have enabled the integration of domain knowledge into the feature engineering process. However, existing LLM-based approaches use direct prompting or rely solely on validation scores for feature selection, failing to leverage insights from prior feature discovery experiments or establish meaningful reasoning between feature generation and data-driven performance. To address these challenges, we propose LLM-FE, a novel framework that combines evolutionary search with the domain knowledge and reasoning capabilities of LLMs to automatically discover effective features for tabular learning tasks. LLM-FE formulates feature engineering as a program search problem, where LLMs propose new feature transformation programs iteratively, and data-driven feedback guides the search process. Our results demonstrate that LLM-FE consistently outperforms state-of-the-art baselines, significantly enhancing the performance of tabular prediction models across diverse classification and regression benchmarks.

[Arxiv](https://arxiv.org/abs/2503.14434)