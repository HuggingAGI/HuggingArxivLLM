# # 脑图基础模型：预训练与提示微调，灵活适应各类图谱及脑部疾病

发布时间：2025年05月31日

`其他` `神经科学` `脑科学`

> A Brain Graph Foundation Model: Pre-Training and Prompt-Tuning for Any Atlas and Disorder

# 摘要

> 随着大型语言模型（LLMs）在AI研究领域掀起革命，构建大规模脑基础模型以推动神经科学研究已成为热门方向。不同于现有模型主要基于时间序列信号或ROI特征，我们提出了一种全新的基于图的预训练范式，用于构建脑图基础模型。本文介绍的BrainGFM模型是一个统一框架，通过图对比学习和图掩码自编码器实现基于fMRI数据的大规模预训练。BrainGFM采用多种不同分区的脑图谱进行预训练，显著扩展了预训练数据范围，提升了模型对异质fMRI脑表征的泛化能力。为了支持高效灵活的下游迁移，我们创新性地将图提示与语言提示相结合，使BrainGFM能够适应多种图谱、神经与精神疾病及任务设置。此外，通过元学习优化图提示，BrainGFM在语言引导提示下，实现了对未知疾病在少样本和零样本条件下的强泛化能力。BrainGFM基于涵盖25种常见神经与精神疾病的27个神经影像数据集进行预训练，涉及功能和解剖两种脑图谱，跨越8种常用分区方法，覆盖超过25,000名受试者、60,000次fMRI扫描，以及所有图谱和分区下总计400,000个图样本。代码已开源：https://github.com/weixinxu666/BrainGFM

> As large language models (LLMs) continue to revolutionize AI research, there is a growing interest in building large-scale brain foundation models to advance neuroscience. While most existing brain foundation models are pre-trained on time-series signals or region-of-interest (ROI) features, we propose a novel graph-based pre-training paradigm for constructing a brain graph foundation model. In this paper, we introduce the Brain Graph Foundation Model, termed BrainGFM, a unified framework that leverages graph contrastive learning and graph masked autoencoders for large-scale fMRI-based pre-training. BrainGFM is pre-trained on a diverse mixture of brain atlases with varying parcellations, significantly expanding the pre-training corpus and enhancing the model's ability to generalize across heterogeneous fMRI-derived brain representations. To support efficient and versatile downstream transfer, we integrate both graph prompts and language prompts into the model design, enabling BrainGFM to flexibly adapt to a wide range of atlases, neurological and psychiatric disorders, and task settings. Furthermore, we employ meta-learning to optimize the graph prompts, facilitating strong generalization to previously unseen disorders under both few-shot and zero-shot learning conditions via language-guided prompting. BrainGFM is pre-trained on 27 neuroimaging datasets spanning 25 common neurological and psychiatric disorders, encompassing 2 types of brain atlases (functional and anatomical) across 8 widely-used parcellations, and covering over 25,000 subjects, 60,000 fMRI scans, and a total of 400,000 graph samples aggregated across all atlases and parcellations. The code is available at: https://github.com/weixinxu666/BrainGFM

[Arxiv](https://arxiv.org/abs/2506.02044)