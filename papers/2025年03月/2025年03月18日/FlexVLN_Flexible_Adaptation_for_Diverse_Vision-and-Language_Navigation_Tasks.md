# FlexVLN：灵活应对多样化视觉-语言导航任务

发布时间：2025年03月18日

`Agent` `机器人` `智能体`

> FlexVLN: Flexible Adaptation for Diverse Vision-and-Language Navigation Tasks

# 摘要

> 长期以来，视觉语言导航（VLN）任务的目标是打造一个具备强大适应性的具身智能体，能够在不同任务间无缝迁移其导航能力。尽管近年来技术突飞猛进，但大多数现有方法仍受限于特定数据集的训练，难以实现跨不同指令类型的多样化数据集的泛化。大型语言模型（LLMs）凭借其卓越的推理与泛化能力，在机器人动作规划领域展现出了巨大潜力。本文提出了一种创新的分层方法——FlexVLN，它巧妙地将基于监督学习的指令跟随器的核心导航能力与LLM规划器的强大泛化能力相结合，从而实现了对多样化VLN数据集的有效泛化。此外，我们还设计了一套验证机制和多模型集成机制，旨在有效缓解LLM规划器的潜在幻觉问题，同时提升指令跟随器的执行精度。通过在REVERIE、SOON和CVDN-Target等域外数据集上的实验，我们发现FlexVLN的泛化性能远超现有方法，展现出显著优势。

> The aspiration of the Vision-and-Language Navigation (VLN) task has long been to develop an embodied agent with robust adaptability, capable of seamlessly transferring its navigation capabilities across various tasks. Despite remarkable advancements in recent years, most methods necessitate dataset-specific training, thereby lacking the capability to generalize across diverse datasets encompassing distinct types of instructions. Large language models (LLMs) have demonstrated exceptional reasoning and generalization abilities, exhibiting immense potential in robot action planning. In this paper, we propose FlexVLN, an innovative hierarchical approach to VLN that integrates the fundamental navigation ability of a supervised-learning-based Instruction Follower with the robust generalization ability of the LLM Planner, enabling effective generalization across diverse VLN datasets. Moreover, a verification mechanism and a multi-model integration mechanism are proposed to mitigate potential hallucinations by the LLM Planner and enhance execution accuracy of the Instruction Follower. We take REVERIE, SOON, and CVDN-target as out-of-domain datasets for assessing generalization ability. The generalization performance of FlexVLN surpasses that of all the previous methods to a large extent.

[Arxiv](https://arxiv.org/abs/2503.13966)