# # MoDoMoDo：跨领域数据融合，助力多模态大语言模型强化学习

发布时间：2025年05月30日

`LLM应用` `多模态模型` `计算机视觉`

> MoDoMoDo: Multi-Domain Data Mixtures for Multimodal LLM Reinforcement Learning

# 摘要

> 强化学习与可验证奖励（Reinforcement Learning with Verifiable Rewards, RLVR）已成为一种强大的后训练范式，尤其在涉及结构化、可验证答案的任务中，其性能已达到当前最优水平。将其应用于多模态大语言模型（MLLMs）虽具潜力，但视觉-语言任务的广泛异质性及对复杂视觉、逻辑和空间能力的需求，使其面临诸多挑战。因此，尽管在多数据集上使用RLVR训练MLLMs可能带来益处，但不同数据集间的交互冲突目标也凸显了寻找最优数据集混合策略以提升泛化和推理能力的必要性。我们提出了一种系统化的多模态LLM RLVR后训练框架，包含严谨的数据混合问题建模和基准实现。具体而言，(1) 我们通过整合包含多种可验证视觉-语言问题的数据集，构建了一个多模态RLVR框架，并实现了基于不同可验证奖励的多领域在线RL学习；(2) 我们提出了一种数据混合策略，能够从数据混合分布中预测RL微调结果，并进而优化最佳混合方案。实验证明，结合混合预测策略的多领域RLVR训练可显著提升MLLM的通用推理能力。我们的最优混合方案相比均匀数据混合的同模型后训练，使模型在分布外基准上的准确率平均提升了5.24%；相比预微调基线，总提升幅度达20.74%。

> Reinforcement Learning with Verifiable Rewards (RLVR) has recently emerged as a powerful paradigm for post-training large language models (LLMs), achieving state-of-the-art performance on tasks with structured, verifiable answers. Applying RLVR to Multimodal LLMs (MLLMs) presents significant opportunities but is complicated by the broader, heterogeneous nature of vision-language tasks that demand nuanced visual, logical, and spatial capabilities. As such, training MLLMs using RLVR on multiple datasets could be beneficial but creates challenges with conflicting objectives from interaction among diverse datasets, highlighting the need for optimal dataset mixture strategies to improve generalization and reasoning. We introduce a systematic post-training framework for Multimodal LLM RLVR, featuring a rigorous data mixture problem formulation and benchmark implementation. Specifically, (1) We developed a multimodal RLVR framework for multi-dataset post-training by curating a dataset that contains different verifiable vision-language problems and enabling multi-domain online RL learning with different verifiable rewards; (2) We proposed a data mixture strategy that learns to predict the RL fine-tuning outcome from the data mixture distribution, and consequently optimizes the best mixture. Comprehensive experiments showcase that multi-domain RLVR training, when combined with mixture prediction strategies, can significantly boost MLLM general reasoning capacities. Our best mixture improves the post-trained model's accuracy on out-of-distribution benchmarks by an average of 5.24% compared to the same model post-trained with uniform data mixture, and by a total of 20.74% compared to the pre-finetuning baseline.

[Arxiv](https://arxiv.org/abs/2505.24871)