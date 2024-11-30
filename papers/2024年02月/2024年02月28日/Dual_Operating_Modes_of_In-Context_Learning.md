# ICL 的双重工作模式解读

发布时间：2024年02月28日

`LLM理论`

> Dual Operating Modes of In-Context Learning

# 摘要

> ICL技术具有任务学习与任务检索两种运作机制，前者能从上下文示例中习得新技能，后者则能定位并激活预先训练好的相关技能。尽管当前已有多种数学模型尝试解析ICL，但它们往往只能逐一阐述这两种运作模式。为此，我们提出了一种全新的概率模型，能够同步解析ICL的双重运作机理。聚焦于线性函数的上下文学习，我们在现有预训练数据模型基础上进一步扩展，引入多任务组和依赖于任务的输入分布。我们深入探究了在平方损失优化下的最优预训练模型行为，即基于上下文示例给出标签的最佳估计。通过将预训练任务分布视为先验知识，而上下文示例作为观测值，我们成功地推导出任务后验分布的封闭形式表达，进而对ICL的两种运作模式有了清晰且量化的理解。此外，对于实际应用中出现的一个尚未明确的现象，即在某些情况下，随着上下文示例增多，ICL的风险起初会上升随后下降，我们的模型提供了一个有说服力的解释：少量的上下文样本可能导致选取了错误的技能，从而使风险增大，但随着更多的上下文样本参与任务学习，该风险最终会逐渐消减。我们同样对带有偏见标签的ICL场景进行了理论分析，比如零次学习，其中上下文示例被随机分配标签。最后，我们通过一系列涉及Transformer和大型语言模型的实验证明了我们的研究成果及其预测准确性。

> In-context learning (ICL) exhibits dual operating modes: task learning, i.e., acquiring a new skill from in-context samples, and task retrieval, i.e., locating and activating a relevant pretrained skill. Recent theoretical work investigates various mathematical models to analyze ICL, but existing models explain only one operating mode at a time. We introduce a probabilistic model, with which one can explain the dual operating modes of ICL simultaneously. Focusing on in-context learning of linear functions, we extend existing models for pretraining data by introducing multiple task groups and task-dependent input distributions. We then analyze the behavior of the optimally pretrained model under the squared loss, i.e., the MMSE estimator of the label given in-context examples. Regarding pretraining task distribution as prior and in-context examples as the observation, we derive the closed-form expression of the task posterior distribution. With the closed-form expression, we obtain a quantitative understanding of the two operating modes of ICL. Furthermore, we shed light on an unexplained phenomenon observed in practice: under certain settings, the ICL risk initially increases and then decreases with more in-context examples. Our model offers a plausible explanation for this "early ascent" phenomenon: a limited number of in-context samples may lead to the retrieval of an incorrect skill, thereby increasing the risk, which will eventually diminish as task learning takes effect with more in-context samples. We also theoretically analyze ICL with biased labels, e.g., zero-shot ICL, where in-context examples are assigned random labels. Lastly, we validate our findings and predictions via experiments involving Transformers and large language models.

[Arxiv](https://arxiv.org/abs/2402.18819)