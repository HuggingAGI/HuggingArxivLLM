# LLM驱动的处理效应估计：推理时文本混杂下的因果分析

发布时间：2025年07月03日

`LLM应用` `人工智能`

> LLM-Driven Treatment Effect Estimation Under Inference Time Text Confounding

# 摘要

> 治疗效果的估计对于医疗领域的个性化决策至关重要，但在临床实践中这一任务面临着独特的挑战。在模型训练阶段，用于估计治疗效果的模型通常基于结构良好且包含详细患者信息的医疗数据集进行训练。然而，在推理阶段，模型往往只能根据文本描述（如患者自述症状）进行预测，这仅能部分反映原始患者信息。

本研究主要贡献如下：
(1) 我们发现，训练阶段与推理阶段可用数据之间的差异可能导致治疗效果估计出现偏差。我们将这一问题形式化为一个推理时间文本混杂问题，其中混杂因素在训练阶段可以完全观察到，但在推理阶段仅能通过文本部分获取。
(2) 为解决这一问题，我们提出了一种新的框架，用于显式考虑推理时间文本混杂的治疗效果估计。我们的框架结合了大型语言模型与定制的双重稳健学习器，以缓解推理时间文本混杂带来的偏见。
(3) 通过一系列实验，我们展示了我们的框架在现实世界应用中的有效性。

> Estimating treatment effects is crucial for personalized decision-making in medicine, but this task faces unique challenges in clinical practice. At training time, models for estimating treatment effects are typically trained on well-structured medical datasets that contain detailed patient information. However, at inference time, predictions are often made using textual descriptions (e.g., descriptions with self-reported symptoms), which are incomplete representations of the original patient information. In this work, we make three contributions. (1) We show that the discrepancy between the data available during training time and inference time can lead to biased estimates of treatment effects. We formalize this issue as an inference time text confounding problem, where confounders are fully observed during training time but only partially available through text at inference time. (2) To address this problem, we propose a novel framework for estimating treatment effects that explicitly accounts for inference time text confounding. Our framework leverages large language models together with a custom doubly robust learner to mitigate biases caused by the inference time text confounding. (3) Through a series of experiments, we demonstrate the effectiveness of our framework in real-world applications.

[Arxiv](https://arxiv.org/abs/2507.02843)