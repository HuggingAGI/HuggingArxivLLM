# MedRep：为通用电子健康记录基础模型提供医学概念表示

发布时间：2025年04月11日

`LLM应用` `知识图谱`

> MedRep: Medical Concept Representation for General Electronic Health Record Foundation Models

# 摘要

> 电子健康记录（EHR）基础模型在多种医疗任务中表现出色，一直是研究热点。尽管如此，处理词汇表外的未见医学代码仍是其核心挑战，限制了模型的通用性和跨词汇表整合能力。为此，我们提出了一种基于OMOP通用数据模型（CDM）的MedRep方法，为患者轨迹提供综合的医学概念表示和基础数据增强策略。在概念表示学习方面，我们通过大型语言模型（LLM）提示为每个概念添加最小定义，丰富其信息，并通过OMOP词汇图谱增强文本表示。轨迹增强则随机将选定的概念替换为具有密切相关表示的其他相似概念，使模型能够练习处理词汇表外的概念。最后，我们证明了使用MedRep训练的EHR基础模型在外部数据集上能更好地保持预测性能。我们的代码实现已公开发布于https://github.com/kicarussays/MedRep。

> Electronic health record (EHR) foundation models have been an area ripe for exploration with their improved performance in various medical tasks. Despite the rapid advances, there exists a fundamental limitation: Processing unseen medical codes out of the vocabulary. This problem limits the generality of EHR foundation models and the integration of models trained with different vocabularies. To deal with this problem, we propose MedRep for EHR foundation models based on the observational medical outcome partnership (OMOP) common data model (CDM), providing the integrated medical concept representations and the basic data augmentation strategy for patient trajectories. For concept representation learning, we enrich the information of each concept with a minimal definition through large language model (LLM) prompts and enhance the text-based representations through graph ontology of OMOP vocabulary. Trajectory augmentation randomly replaces selected concepts with other similar concepts that have closely related representations to let the model practice with the concepts out-of-vocabulary. Finally, we demonstrate that EHR foundation models trained with MedRep better maintain the prediction performance in external datasets. Our code implementation is publicly available at https://github.com/kicarussays/MedRep.

[Arxiv](https://arxiv.org/abs/2504.08329)