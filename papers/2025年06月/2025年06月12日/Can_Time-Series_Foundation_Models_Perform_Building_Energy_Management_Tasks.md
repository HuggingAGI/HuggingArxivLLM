# 时间序列基础模型能否胜任楼宇能源管理任务？

发布时间：2025年06月12日

`LLM应用` `能源管理`

> Can Time-Series Foundation Models Perform Building Energy Management Tasks?

# 摘要

> 楼宇能源管理（BEM）任务需要处理和学习多种时间序列数据。现有解决方案依赖于特定任务和数据定制的模型，这限制了它们的广泛应用。受大型语言模型（LLMs）成功转型的启发，基于多样化数据集训练的时间序列基础模型（TSFMs）有可能改变这一现状。如果TSFMs能够达到类似LLMs的跨任务和跨场景泛化能力，它们将从根本上解决BEM中普遍存在的可扩展性挑战。

为了了解TSFMs目前的发展状况，我们从四个维度进行了评估：（1）零样本单变量预测的泛化能力，（2）用于热行为建模的协变量预测，（3）针对分类任务的零样本表示学习，（4）对性能指标和不同运行条件的鲁棒性。

研究结果表明，TSFMs的泛化能力有限。在未见过的数据集和单变量预测模态上，它们仅比统计模型略胜一筹。加入协变量并未带来性能提升，且TSFMs的表现仍劣于利用协变量的传统模型。尽管TSFMs能为下游分类任务生成有效的零样本表示，但在统计模型进行测试时拟合的情况下，它们在预测方面仍可能劣于统计模型。此外，TSFMs的预测性能对评估指标敏感，在更复杂的楼宇环境中与统计模型相比表现挣扎。

这些发现凸显了在TSFM设计方面进行针对性改进的必要性，特别是在处理协变量以及将上下文和时间动态纳入预测机制方面，以开发更灵活和可扩展的BEM解决方案。

> Building energy management (BEM) tasks require processing and learning from a variety of time-series data. Existing solutions rely on bespoke task- and data-specific models to perform these tasks, limiting their broader applicability. Inspired by the transformative success of Large Language Models (LLMs), Time-Series Foundation Models (TSFMs), trained on diverse datasets, have the potential to change this. Were TSFMs to achieve a level of generalizability across tasks and contexts akin to LLMs, they could fundamentally address the scalability challenges pervasive in BEM. To understand where they stand today, we evaluate TSFMs across four dimensions: (1) generalizability in zero-shot univariate forecasting, (2) forecasting with covariates for thermal behavior modeling, (3) zero-shot representation learning for classification tasks, and (4) robustness to performance metrics and varying operational conditions. Our results reveal that TSFMs exhibit \emph{limited} generalizability, performing only marginally better than statistical models on unseen datasets and modalities for univariate forecasting. Similarly, inclusion of covariates in TSFMs does not yield performance improvements, and their performance remains inferior to conventional models that utilize covariates. While TSFMs generate effective zero-shot representations for downstream classification tasks, they may remain inferior to statistical models in forecasting when statistical models perform test-time fitting. Moreover, TSFMs forecasting performance is sensitive to evaluation metrics, and they struggle in more complex building environments compared to statistical models. These findings underscore the need for targeted advancements in TSFM design, particularly their handling of covariates and incorporating context and temporal dynamics into prediction mechanisms, to develop more adaptable and scalable solutions for BEM.

[Arxiv](https://arxiv.org/abs/2506.11250)