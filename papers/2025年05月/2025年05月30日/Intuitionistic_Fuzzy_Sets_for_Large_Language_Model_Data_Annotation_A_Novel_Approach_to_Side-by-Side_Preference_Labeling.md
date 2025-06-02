# 直觉模糊集在大型语言模型数据标注中的应用：一种新型的并排偏好标注方法

发布时间：2025年05月30日

`LLM应用

摘要中讨论了如何改进人类偏好数据的标注方法，这对训练和评估大型语言模型（LLMs）具有实际应用价值。提出的新框架和方法旨在提高数据质量，从而提升模型性能，属于LLM的应用研究。` `人工智能`

> Intuitionistic Fuzzy Sets for Large Language Model Data Annotation: A Novel Approach to Side-by-Side Preference Labeling

# 摘要

> 人类偏好数据的质量对训练和评估大型语言模型（LLMs）至关重要，尤其在基于人类反馈的强化学习（RLHF）和直接偏好优化（DPO）场景中。传统并排（SBS）标注方法常面临不确定性和标注者意见分歧等问题。本文提出了一种基于直觉模糊集（IFS）的新框架，用于建模和聚合LLM数据标注中的人类偏好。通过隶属度、非隶属度和犹豫度，我们的方法不仅捕捉偏好的程度，还反映了人类判断中的不确定性和犹豫。我们开发了基于IFS的标注协议和聚合方法，以实现更细致的偏好建模，并引入了质量指标来评估偏好数据。实验结果表明，与传统方法相比，我们的方法显著提升了标注一致性和数据质量，减少了标注时间，并在下游任务中提升了模型性能。与基线模型相比，胜率提高了12.3%，标注时间减少了15.7%。我们的框架为处理人类偏好标注中的不确定性提供了原则性方法，并为大规模LLM训练带来了实际优势。


> The quality of human preference data is crucial for training and evaluating large language models (LLMs), particularly in reinforcement learning from human feedback (RLHF) and direct preference optimization (DPO) scenarios. Traditional side-by-side (SBS) annotation approaches often struggle with inherent uncertainty, annotator disagreement, and the complexity of preference judgments. This paper introduces a novel framework based on intuitionistic fuzzy sets (IFS) for modeling and aggregating human preferences in LLM data annotation tasks. Our approach captures not only the degree of preference but also the uncertainty and hesitation inherent in human judgment through membership, non-membership, and hesitation degrees. We propose an IFS-based annotation protocol that enables more nuanced preference modeling, develops aggregation methods for handling annotator disagreement, and introduces quality metrics for preference data assessment. Experimental validation on multiple datasets demonstrates that our IFS-based approach significantly improves annotation consistency, reduces annotator fatigue, and produces higher-quality preference data compared to traditional binary and Likert-scale methods. The resulting preference datasets lead to improved model performance in downstream tasks, with 12.3\% improvement in win-rate against baseline models and 15.7\% reduction in annotation time. Our framework provides a principled approach to handling uncertainty in human preference annotation and offers practical benefits for large-scale LLM training.

[Arxiv](https://arxiv.org/abs/2505.24199)