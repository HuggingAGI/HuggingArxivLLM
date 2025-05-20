# # 重新审视大型语言模型路由的预测建模：为何简单的kNN超越了复杂的路由算法

发布时间：2025年05月18日

`LLM理论` `软件工程` `人工智能`

> Rethinking Predictive Modeling for LLM Routing: When Simple kNN Beats Complex Learned Routers

# 摘要

> 随着大型语言模型（LLMs）规模的扩大和专业化程度的提升，为给定输入选择最佳模型的路由技术已成为高效部署的关键。尽管近期方法依赖于复杂的基于学习的路由策略，但这些方法对不同训练数据和评估设置的依赖使得比较和泛化变得困难。在本研究中，我们从简洁性的角度重新审视了LLM路由问题。我们发现，经过良好调优的k-近邻（kNN）方法不仅能够匹敌，而且经常超越现有最先进的基于学习的路由算法，在多样化任务中表现出更优性能。

为了支持系统的评估，我们引入了一套标准化的路由基准测试，涵盖指令遵循、问答和推理任务，并首次推出了一个涉及视觉输入的多模态路由数据集。我们的研究发现，模型在嵌入空间中的局部性能特性使简单的非参数方法能够以比参数化方法更低的样本复杂度实现强大的路由决策。这一发现挑战了当前向复杂架构发展的趋势，并强调了在投入复杂解决方案之前，彻底评估简单基线方法的重要性。

为了支持可重复性和进一步探索，我们将在论文发表时公开所有基准测试和代码。


> As large language models (LLMs) grow in scale and specialization, routing--selecting the best model for a given input--has become essential for efficient and effective deployment. While recent methods rely on complex learned routing strategies, their dependence on disparate training data and evaluation setups makes comparison and generalization difficult. In this work, we revisit LLM routing through the lens of simplicity. We show that a well-tuned k-Nearest Neighbors (kNN) approach not only matches but often outperforms state-of-the-art learned routers across diverse tasks. To support systematic evaluation, we introduce a suite of standardized routing benchmarks spanning instruction-following, question-answering, and reasoning tasks, as well as the first multi-modal routing dataset involving visual inputs. Our findings reveal that the locality properties of model performance in embedding space enable simple non-parametric methods to achieve strong routing decisions with lower sample complexity than parametric approaches. This challenges the prevailing trend toward sophisticated architectures and highlights the importance of thoroughly evaluating simple baselines before investing in complex solutions. To support reproducibility and further exploration, we will release all benchmarks and code upon publication.

[Arxiv](https://arxiv.org/abs/2505.12601)