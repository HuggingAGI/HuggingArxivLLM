# 管理者：整合单模态专家见解于双塔VLM与多语言LLMs

发布时间：2025年06月13日

`LLM理论` `视觉-语言模型` `多模态大规模语言模型`

> Manager: Aggregating Insights from Unimodal Experts in Two-Tower VLMs and MLLMs

# 摘要

> 双塔视觉-语言模型（VLMs）在视觉语言任务中表现优异。然而，尽管BridgeTower通过跨编码器连接提升了性能，但它仍存在三大局限：单模态表示的逐层利用效率低、单模态语义知识的灵活挖掘受限、以及仅限于传统低分辨率数据集的双塔架构评估。为此，我们提出了一种轻量、高效的Manager插件，它能自适应整合多级预训练单模态专家的见解，助力更全面的视觉语言对齐与融合。在双塔架构下，我们创新性地提出了ManagerTower，它在每个跨模态层引入管理器角色。无论是否经过预训练，ManagerTower均超越了现有强基线，并在4项下游任务中表现优异。进一步地，我们将研究扩展至最新的多模态大规模语言模型（MLLM）架构。实验表明，LLaVA-OV-Manager显著提升了LLaVA-OV在20个数据集上的零样本性能，无论是否启用多网格算法。深入分析显示，我们的管理器与多网格算法均能从深度和广度两个视角优化视觉表示，协同工作以缓解语义歧义并提升性能。代码与模型已开源，欢迎访问https://github.com/LooperXX/ManagerTower。

> Two-Tower Vision--Language Models (VLMs) have demonstrated strong performance across various downstream VL tasks. While BridgeTower further enhances performance by building bridges between encoders, it \textit{(i)} suffers from ineffective layer-by-layer utilization of unimodal representations, \textit{(ii)} restricts the flexible exploitation of different levels of unimodal semantic knowledge, and \textit{(iii)} is limited to the evaluation on traditional low-resolution datasets only with the Two-Tower VLM architecture. In this work, we propose Manager, a lightweight, efficient and effective plugin that adaptively aggregates insights from different levels of pre-trained unimodal experts to facilitate more comprehensive VL alignment and fusion. First, under the Two-Tower VLM architecture, we introduce ManagerTower, a novel VLM that introduces the manager in each cross-modal layer. Whether with or without VL pre-training, ManagerTower outperforms previous strong baselines and achieves superior performance on 4 downstream VL tasks. Moreover, we extend our exploration to the latest Multimodal Large Language Model (MLLM) architecture. We demonstrate that LLaVA-OV-Manager significantly boosts the zero-shot performance of LLaVA-OV across different categories of capabilities, images, and resolutions on 20 downstream datasets, whether the multi-grid algorithm is enabled or not. In-depth analysis reveals that both our manager and the multi-grid algorithm can be viewed as a plugin that improves the visual representation by capturing more diverse visual details from two orthogonal perspectives (depth and width). Their synergy can mitigate the semantic ambiguity caused by the multi-grid algorithm and further improve performance. Code and models are available at https://github.com/LooperXX/ManagerTower.

[Arxiv](https://arxiv.org/abs/2506.11515)