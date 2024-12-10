# 生成式人工智能能否解决您的上下文学习难题？从鞅的视角来看

发布时间：2024年12月08日

`LLM应用`

> Can Generative AI Solve Your In-Context Learning Problem? A Martingale Perspective

# 摘要

> 这项工作旨在估计条件生成模型（CGM）何时能解决上下文学习（ICL）问题。ICL 问题涵盖了 CGM、数据集以及预测任务。CGM 可能是多模态基础模型；数据集可能是患者病史、测试结果和记录诊断的集合；预测任务是向新患者传达诊断。对 ICL 的贝叶斯解释假定 CGM 会在定义潜在解释与可观测数据联合分布的未知贝叶斯模型上计算后验预测分布。从这一视角出发，贝叶斯模型批评是评估给定 CGM 对 ICL 问题适用性的合理手段。然而，诸如后验预测检查（PPCs）这类方法通常假定我们能从贝叶斯模型所定义的似然和后验中采样，可对于当代 CGM 而言，这些并非明确给出的。为解决此问题，我们展示了从 CGM 的预测分布进行祖先采样何时等同于从假定贝叶斯模型的后验预测中采样数据集。接着，我们开发了生成预测$p$-值，这使得当代 CGM 能够运用 PPCs 及其相关方法。生成预测$p$-值随后可用于统计决策过程，以判定模型何时适用于 ICL 问题。我们的方法仅需从 CGM 生成查询和响应，并评估其响应的对数概率。我们运用大型语言模型在合成表格、成像和自然语言 ICL 任务上对我们的方法进行了实证评估。

> This work is about estimating when a conditional generative model (CGM) can solve an in-context learning (ICL) problem. An in-context learning (ICL) problem comprises a CGM, a dataset, and a prediction task. The CGM could be a multi-modal foundation model; the dataset, a collection of patient histories, test results, and recorded diagnoses; and the prediction task to communicate a diagnosis to a new patient. A Bayesian interpretation of ICL assumes that the CGM computes a posterior predictive distribution over an unknown Bayesian model defining a joint distribution over latent explanations and observable data. From this perspective, Bayesian model criticism is a reasonable approach to assess the suitability of a given CGM for an ICL problem. However, such approaches -- like posterior predictive checks (PPCs) -- often assume that we can sample from the likelihood and posterior defined by the Bayesian model, which are not explicitly given for contemporary CGMs. To address this, we show when ancestral sampling from the predictive distribution of a CGM is equivalent to sampling datasets from the posterior predictive of the assumed Bayesian model. Then we develop the generative predictive $p$-value, which enables PPCs and their cousins for contemporary CGMs. The generative predictive $p$-value can then be used in a statistical decision procedure to determine when the model is appropriate for an ICL problem. Our method only requires generating queries and responses from a CGM and evaluating its response log probability. We empirically evaluate our method on synthetic tabular, imaging, and natural language ICL tasks using large language models.

[Arxiv](https://arxiv.org/abs/2412.06033)