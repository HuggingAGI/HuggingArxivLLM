# CiTrus：从低数据生物信号的迁移学习中榨取额外性能

发布时间：2024年12月16日

`其他` `生物信号` `转移学习`

> CiTrus: Squeezing Extra Performance out of Low-data Bio-signal Transfer Learning

# 摘要

> 对于生物信号而言，转移学习近来已成为一项重要技术，能在小生物信号数据集的下游任务中提升预测性能。近期研究显示，在大型数据集（如脑电图）上以自监督任务对神经网络模型进行预训练，将自监督头部换成线性分类头部，再在不同的下游生物信号数据集（如肌电图或心电图）上对模型微调，能大幅提升这些数据集上的性能。在本文中，我们提出一种用于低数据生物信号转移学习的带有掩码自编码的新卷积-变压器混合模型架构，引入基于频率的掩码自编码任务，采用更全面的评估框架，并评估（多模态）预训练在多大程度上以及何时能提高微调性能。我们还引入一种效果显著更优的方法，将具有不同时间长度和采样率的下游数据集与原始预训练数据集对齐。我们发现，我们混合模型中的仅卷积部分在一些低数据下游任务中能达到顶尖性能。使用完整模型，性能通常会进一步提升。对于基于变压器的模型，我们发现预训练尤其能提高下游数据集的性能，多模态预训练通常会进一步增加这种增益，并且我们基于频率的预训练在最低和最高数据情况下平均表现最佳。

> Transfer learning for bio-signals has recently become an important technique to improve prediction performance on downstream tasks with small bio-signal datasets. Recent works have shown that pre-training a neural network model on a large dataset (e.g. EEG) with a self-supervised task, replacing the self-supervised head with a linear classification head, and fine-tuning the model on different downstream bio-signal datasets (e.g., EMG or ECG) can dramatically improve the performance on those datasets. In this paper, we propose a new convolution-transformer hybrid model architecture with masked auto-encoding for low-data bio-signal transfer learning, introduce a frequency-based masked auto-encoding task, employ a more comprehensive evaluation framework, and evaluate how much and when (multimodal) pre-training improves fine-tuning performance. We also introduce a dramatically more performant method of aligning a downstream dataset with a different temporal length and sampling rate to the original pre-training dataset. Our findings indicate that the convolution-only part of our hybrid model can achieve state-of-the-art performance on some low-data downstream tasks. The performance is often improved even further with our full model. In the case of transformer-based models we find that pre-training especially improves performance on downstream datasets, multimodal pre-training often increases those gains further, and our frequency-based pre-training performs the best on average for the lowest and highest data regimes.

[Arxiv](https://arxiv.org/abs/2412.11695)