# 多模态可解释时间序列预测与闭环中的LLM

发布时间：2025年03月02日

`LLM应用

摘要中提到的论文主要研究了如何利用大语言模型（LLMs）在时间序列预测中的应用，通过整合多模态数据和LLMs来提升预测的准确性和可解释性。虽然主要应用在时间序列分析领域，但核心是利用LLMs的能力来优化预测流程，因此属于LLM应用类别。`

> Explainable Multi-modal Time Series Prediction with LLM-in-the-Loop

# 摘要

> 时间序列分析为现实世界系统动态提供关键洞察，并为下游决策提供信息。然而，现有方法往往忽视了辅助模态中的丰富上下文信号。为填补这一空白，我们推出TimeXL——一个多模态预测框架，整合了基于原型的时间序列编码器与三个协作的大语言模型（LLMs），以实现更精准的预测和清晰的解释。

TimeXL的工作流程如下：首先，多模态原型编码器同时处理时间序列和文本数据，生成初步预测和案例分析。随后，预测LLM通过推理编码器的预测和解释来优化结果。接着，反思LLM对比预测值与真实值，识别文本中的不一致或噪声。基于此反馈，优化LLM迭代提升文本质量并触发编码器的重新训练。这种预测、反思、优化的闭环流程持续提升框架的性能和可解释性。

实证评估显示，TimeXL在四个真实数据集上实现了高达8.9%的AUC提升，并生成了以人类为中心的多模态解释，充分展现了大语言模型驱动推理在时间序列预测中的强大能力。

> Time series analysis provides essential insights for real-world system dynamics and informs downstream decision-making, yet most existing methods often overlook the rich contextual signals present in auxiliary modalities. To bridge this gap, we introduce TimeXL, a multi-modal prediction framework that integrates a prototype-based time series encoder with three collaborating Large Language Models (LLMs) to deliver more accurate predictions and interpretable explanations. First, a multi-modal prototype-based encoder processes both time series and textual inputs to generate preliminary forecasts alongside case-based rationales. These outputs then feed into a prediction LLM, which refines the forecasts by reasoning over the encoder's predictions and explanations. Next, a reflection LLM compares the predicted values against the ground truth, identifying textual inconsistencies or noise. Guided by this feedback, a refinement LLM iteratively enhances text quality and triggers encoder retraining. This closed-loop workflow -- prediction, critique (reflect), and refinement -- continuously boosts the framework's performance and interpretability. Empirical evaluations on four real-world datasets demonstrate that TimeXL achieves up to 8.9\% improvement in AUC and produces human-centric, multi-modal explanations, highlighting the power of LLM-driven reasoning for time series prediction.

[Arxiv](https://arxiv.org/abs/2503.01013)