# 大型语言模型能否引发旅行行为建模的范式转变？在旅行满意度建模中的应用与经验

发布时间：2025年05月29日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在旅行满意度建模中的应用，分析了其在实际问题中的表现和挑战，并提出了基于LLMs的小样本建模方法。研究重点在于LLMs的应用和实际效果，属于LLM应用类别。` `人工智能`

> Can Large Language Models Trigger a Paradigm Shift in Travel Behavior Modeling? Experiences with Modeling Travel Satisfaction

# 摘要

> 作为主观幸福感的重要领域，旅行满意度近年来备受研究关注。传统研究主要依赖统计模型和机器学习模型探索其决定因素，但这些方法都对数据量和统计假设提出了较高要求。大型语言模型（LLMs）的出现为这一领域带来了革新，其强大的上下文理解和泛化能力显著降低了对海量特定数据和严格统计假设的依赖。然而，LLMs在应用中面临与人类行为不一致的挑战。本研究基于上海家庭调查的旅行满意度数据，深入探讨了这一不一致现象的成因，并提出了解决方案。研究发现，零样本LLM的预测精度相对较低，但通过少量样本学习，模型在MSE和MAPE指标上显著超越传统方法。这种差距源于LLMs的通用知识与特定数据集独特特征之间的鸿沟。为此，我们提出了一种基于LLMs的小样本建模方法，为旅行行为研究提供了新思路。本研究不仅揭示了LLMs在旅行满意度建模中的潜力，更为广泛旅行行为研究开辟了新方向。

> As a specific domain of subjective well-being, travel satisfaction has attracted much research attention recently. Previous studies primarily use statistical models and, more recently, machine learning models to explore the determinants of travel satisfaction. Both approaches require data from sufficient sample sizes and correct prior statistical assumptions. The emergence of Large Language Models (LLMs) offers a new modeling approach that can overcome the shortcomings of the existing methods. Pre-trained on extensive datasets, LLMs have strong capabilities in contextual understanding and generalization, significantly reducing their dependence on large quantities of task-specific data and stringent statistical assumptions. The primary challenge in applying LLMs lies in addressing the behavioral misalignment between LLMs and human behavior. Using data on travel satisfaction from a household survey in shanghai, this study identifies the existence and source of misalignment and develop methods to address the misalignment issue. We find that the zero-shot LLM exhibits behavioral misalignment, resulting in relatively low prediction accuracy. However, few-shot learning, even with a limited number of samples, allows the model to outperform baseline models in MSE and MAPE metrics. This misalignment can be attributed to the gap between the general knowledge embedded in LLMs and the specific, unique characteristics of the dataset. On these bases, we propose an LLM-based modeling approach that can be applied to model travel behavior using samples of small sizes. This study highlights the potential of LLMs for modeling not only travel satisfaction but also broader aspects of travel behavior.

[Arxiv](https://arxiv.org/abs/2505.23262)