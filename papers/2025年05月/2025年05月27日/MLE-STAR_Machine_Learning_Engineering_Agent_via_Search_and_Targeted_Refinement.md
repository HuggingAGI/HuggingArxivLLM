# MLE-STAR：基于搜索与针对性优化的机器学习工程代理

发布时间：2025年05月27日

`Agent` `人工智能` `数据科学竞赛`

> MLE-STAR: Machine Learning Engineering Agent via Search and Targeted Refinement

# 摘要

> 基于大型语言模型（LLMs）的机器学习工程（MLE）智能体能够通过代码生成自动实现ML模型。然而，现有方法在构建此类智能体时，往往过分依赖LLMs的固有知识，并采用一次性修改整个代码结构的粗放探索策略。这使得它们难以在特定任务中选择有效模型，也无法在特定组件中进行深入探索，例如在特征工程选项上进行广泛实验。为了解决这些问题，我们提出了MLE-STAR——一种全新的构建MLE智能体的方法。MLE-STAR首先通过搜索引擎从网络中检索有效模型，形成初始解决方案，然后通过迭代探索针对特定ML组件的各种策略进行优化。这种探索由消融实验引导，分析单个代码块的影响。此外，我们还引入了一种基于MLE-STAR建议的有效策略的新型集成方法。实验结果表明，MLE-STAR在MLE-bench上的Kaggle竞赛中获得了44%的奖牌，显著优于最佳替代方案。

> Agents based on large language models (LLMs) for machine learning engineering (MLE) can automatically implement ML models via code generation. However, existing approaches to build such agents often rely heavily on inherent LLM knowledge and employ coarse exploration strategies that modify the entire code structure at once. This limits their ability to select effective task-specific models and perform deep exploration within specific components, such as experimenting extensively with feature engineering options. To overcome these, we propose MLE-STAR, a novel approach to build MLE agents. MLE-STAR first leverages external knowledge by using a search engine to retrieve effective models from the web, forming an initial solution, then iteratively refines it by exploring various strategies targeting specific ML components. This exploration is guided by ablation studies analyzing the impact of individual code blocks. Furthermore, we introduce a novel ensembling method using an effective strategy suggested by MLE-STAR. Our experimental results show that MLE-STAR achieves medals in 44% of the Kaggle competitions on the MLE-bench, significantly outperforming the best alternative.

[Arxiv](https://arxiv.org/abs/2506.15692)