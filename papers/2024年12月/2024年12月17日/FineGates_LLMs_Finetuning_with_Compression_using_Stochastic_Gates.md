# FineGates：通过使用随机门压缩来对大型语言模型进行微调

发布时间：2024年12月17日

`LLM应用` `计算机` `人工智能`

> FineGates: LLMs Finetuning with Compression using Stochastic Gates

# 摘要

> 大型语言模型（LLMs）拥有数十亿参数，因其计算需求高、内存要求高以及在众多实际应用中难以操作，所以对其进行全面微调颇具挑战。在计算资源有限或数据集较小时，更新全部模型参数常会导致过拟合。为此，诸如学习低秩适配层之类的轻量级微调技术应运而生。这些方法旨在仅训练与冻结的基础模型相结合的少量额外参数，以减少资源消耗和降低过拟合风险。在本研究中，我们提出了一种基于随机门的适配模型，能同时针对特定任务对冻结的基础模型进行稀疏化处理。我们的方法可训练参数少，能在保证准确率有竞争力的情况下加快基础模型的推理速度。我们通过为其配备额外的低秩参数，并与几个近期的基线进行比较，在其他变体中对其进行了评估。结果表明，所提方法相较于几个基线提高了微调模型的准确率，且允许去除多达 20 - 40％而不会有显著的准确率损失。

> Large Language Models (LLMs), with billions of parameters, present significant challenges for full finetuning due to the high computational demands, memory requirements, and impracticality of many real-world applications. When faced with limited computational resources or small datasets, updating all model parameters can often result in overfitting. To address this, lightweight finetuning techniques have been proposed, like learning low-rank adapter layers. These methods aim to train only a few additional parameters combined with the base model, which remains frozen, reducing resource usage and mitigating overfitting risks. In this work, we propose an adaptor model based on stochastic gates that simultaneously sparsify the frozen base model with task-specific adaptation. Our method comes with a small number of trainable parameters and allows us to speed up the base model inference with competitive accuracy. We evaluate it in additional variants by equipping it with additional low-rank parameters and comparing it to several recent baselines. Our results show that the proposed method improves the finetuned model accuracy comparatively to the several baselines and allows the removal of up to 20-40\% without significant accuracy loss.

[Arxiv](https://arxiv.org/abs/2412.12951)