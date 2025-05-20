# 重新审视 LLM 路由预测模型：简单 kNN 如何胜过复杂路由模型

发布时间：2025年05月18日

`LLM应用` `人工智能`

> Rethinking Predictive Modeling for LLM Routing: When Simple kNN Beats Complex Learned Routers

# 摘要

> 随着大型语言模型（LLMs）的规模和专业化程度不断提升，为输入选择最佳模型的路由已成为高效部署的关键。尽管现有方法依赖复杂的路由策略，但其对不同训练数据和评估设置的依赖性限制了比较和泛化能力。本研究从简洁性视角重新审视LLM路由问题，提出了一种经过优化的k-Nearest Neighbors (kNN)方法，不仅能够匹敌，甚至在多个任务中超越了现有的先进路由方案。为实现系统性评估，我们构建了一套标准化的路由基准测试，覆盖指令遵循、问答和推理任务，并推出了首个涉及视觉输入的多模态路由数据集。研究发现，模型在嵌入空间中的局部性能特性使得简单的非参数方法能够以更低的样本复杂度做出高效的路由决策。这一发现不仅挑战了日益复杂的架构趋势，还强调了在投入复杂解决方案前，全面评估简单基线的重要性。为支持可重复性和进一步研究，我们将在论文发表时开放所有基准测试和代码。

> As large language models (LLMs) grow in scale and specialization, routing--selecting the best model for a given input--has become essential for efficient and effective deployment. While recent methods rely on complex learned routing strategies, their dependence on disparate training data and evaluation setups makes comparison and generalization difficult. In this work, we revisit LLM routing through the lens of simplicity. We show that a well-tuned k-Nearest Neighbors (kNN) approach not only matches but often outperforms state-of-the-art learned routers across diverse tasks. To support systematic evaluation, we introduce a suite of standardized routing benchmarks spanning instruction-following, question-answering, and reasoning tasks, as well as the first multi-modal routing dataset involving visual inputs. Our findings reveal that the locality properties of model performance in embedding space enable simple non-parametric methods to achieve strong routing decisions with lower sample complexity than parametric approaches. This challenges the prevailing trend toward sophisticated architectures and highlights the importance of thoroughly evaluating simple baselines before investing in complex solutions. To support reproducibility and further exploration, we will release all benchmarks and code upon publication.

[Arxiv](https://arxiv.org/abs/2505.12601)