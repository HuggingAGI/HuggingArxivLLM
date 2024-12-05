# 评估预训练与提示适应的语言模型之间的性别偏见转移情况

发布时间：2024年12月04日

`LLM应用` `语言模型` `决策系统`

> Evaluating Gender Bias Transfer between Pre-trained and Prompt-Adapted Language Models

# 摘要

> 大型语言模型（LLMs）正日益被调整以具备任务特定性，从而能在现实世界的决策系统中得以部署。此前的一些工作通过研究微调适应策略对模型公平性的影响，对偏差转移假设（BTH）展开了探究，发现预训练的掩码语言模型中的公平性对于采用微调适应的模型公平性影响有限。在本研究中，我们把 BTH 的研究拓展到提示适应下的因果模型，毕竟提示是在现实世界系统中部署模型的一种便捷且计算高效的方式。与以往工作不同，我们借助代词共指解析任务证实，预训练的 Mistral、Falcon 和 Llama 模型中的内在偏差与相同模型在零样本和少样本提示时的偏差强相关（rho >= 0.94）。而且，我们发现即便 LLMs 被特别提示展现出公平或有偏差的行为（rho >= 0.92），以及少样本长度和刻板印象组成有所变化（rho >= 0.97），偏差转移仍高度相关。我们的发现凸显了确保预训练的 LLMs 公平性的重要性，尤其是当它们后续通过提示适应来执行下游任务时。

> Large language models (LLMs) are increasingly being adapted to achieve task-specificity for deployment in real-world decision systems. Several previous works have investigated the bias transfer hypothesis (BTH) by studying the effect of the fine-tuning adaptation strategy on model fairness to find that fairness in pre-trained masked language models have limited effect on the fairness of models when adapted using fine-tuning. In this work, we expand the study of BTH to causal models under prompt adaptations, as prompting is an accessible, and compute-efficient way to deploy models in real-world systems. In contrast to previous works, we establish that intrinsic biases in pre-trained Mistral, Falcon and Llama models are strongly correlated (rho >= 0.94) with biases when the same models are zero- and few-shot prompted, using a pronoun co-reference resolution task. Further, we find that bias transfer remains strongly correlated even when LLMs are specifically prompted to exhibit fair or biased behavior (rho >= 0.92), and few-shot length and stereotypical composition are varied (rho >= 0.97). Our findings highlight the importance of ensuring fairness in pre-trained LLMs, especially when they are later used to perform downstream tasks via prompt adaptation.

[Arxiv](https://arxiv.org/abs/2412.03537)