# PUMA：通过层剪枝实现高效统一多模态检索与模态自适应学习的语言模型

发布时间：2025年07月10日

`LLM应用

摘要中提到的研究主要关注多模态大型语言模型（MLLMs）在统一多模态检索（UMR）任务中的应用，并提出了优化方法以提高效率和降低资源消耗。这属于LLM在具体任务中的应用和优化，因此归类为LLM应用。` `信息检索` `多媒体`

> PUMA: Layer-Pruned Language Model for Efficient Unified Multimodal Retrieval with Modality-Adaptive Learning

# 摘要

> 随着多媒体内容的蓬勃发展，统一多模态检索（UMR）在实际应用中的需求日益迫切。近期研究利用多模态大型语言模型（MLLMs）来解决这一任务。然而，这些模型庞大的参数规模导致了高昂的训练成本和较低的推理效率。为了解决这一问题，我们提出了PUMA：一种基于模态自适应学习的高效统一多模态检索分层剪枝语言模型。我们的方法从结构和学习两个角度改进了UMR。 (1) 从结构上看，我们提出了层剪枝自蒸馏方法，仅保留浅层结构并对被剪枝的深层特征进行蒸馏作为教师信号，从而减少了参数量并保留了表示能力。 (2) 在学习方面，我们引入了模态自适应对比学习损失（MAC-Loss），根据目标模态将批次内的负样本划分为更难的同模态组和更易的跨模态组，并采用不同的温度策略以提高学习效率。实验表明，我们的方法在保持高性能的同时显著降低了资源消耗。

> As multimedia content expands, the demand for unified multimodal retrieval (UMR) in real-world applications increases. Recent work leverages multimodal large language models (MLLMs) to tackle this task. However, their large parameter size results in high training costs and low inference efficiency. To address this, we propose PUMA: a Layer-Pruned Language Model for Efficient Unified Multimodal Retrieval with Modality-Adaptive Learning. Our approach improves UMR from both structural and learning perspectives. (1) Structurally, we propose Layer-Pruned Self-Distillation, which prunes MLLMs by keeping only shallow layers while distilling features from dropped deep layers as teacher signals. This reduces parameters and preserves representation capability. (2) On the learning side, we introduce Modality-Adaptive Contrastive Learning Loss (MAC-Loss), which separates in-batch negatives into harder intra-modality and easier inter-modality groups based on the target modality, assigning different temperature strategies to enhance learning efficiency. Experiments show our method significantly reduces resource usage while maintaining strong performance.

[Arxiv](https://arxiv.org/abs/2507.08064)