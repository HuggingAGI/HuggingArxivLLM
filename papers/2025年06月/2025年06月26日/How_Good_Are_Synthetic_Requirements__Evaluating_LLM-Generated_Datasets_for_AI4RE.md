# 合成需求的质量如何？深度评估LLM生成的数据集在AI4RE中的应用

发布时间：2025年06月26日

`LLM应用` `需求工程` `人工智能`

> How Good Are Synthetic Requirements ? Evaluating LLM-Generated Datasets for AI4RE

# 摘要

> 公开可用的标注需求数据集短缺仍然是推动需求工程领域人工智能发展的主要障碍。尽管大型语言模型在合成数据生成方面展现出巨大潜力，但如何系统性地控制和优化生成需求的质量仍是一个未被充分探索的领域。本文介绍了Synthline v1，这是一种增强的产品线方法，用于生成合成需求数据，它在我们之前的v0版本基础上，引入了更先进的生成策略和数据整理技术。我们通过四个研究问题，评估了提示策略、自动提示优化以及生成后整理对四个分类任务数据质量的影响：缺陷检测、功能性与非功能性需求区分、质量与非质量需求区分、以及安全与非安全需求区分。我们的评估结果表明，与单样本生成相比，多样本提示策略在实用性和多样性方面均有显著提升，F1分数提高了6到44个百分点。使用PACE（提示Actor-Critic编辑器）进行自动提示优化会产生任务依赖的结果，虽然在功能性分类任务中提升了32.5个百分点，但在其他任务中表现有所下降。有趣的是，基于相似性的数据整理能够提升数据多样性，但往往会损害分类性能，这表明一定程度的冗余可能对机器学习模型有益。最重要的是，我们的研究发现，合成需求数据在特定任务中可以与甚至超越人工编写的高质量需求数据，特别是在安全需求分类（+7.8分）和缺陷分类（+15.4分）方面，合成数据表现更优。这些发现为需求工程领域的人工智能研究提供了实践启示，并为通过系统性合成数据生成缓解数据集稀缺问题指明了一条可行路径。

> The shortage of publicly available, labeled requirements datasets remains a major barrier to advancing Artificial Intelligence for Requirements Engineering (AI4RE). While Large Language Models offer promising capabilities for synthetic data generation, systematic approaches to control and optimize the quality of generated requirements remain underexplored. This paper presents Synthline v1, an enhanced Product Line approach for generating synthetic requirements data that extends our earlier v0 version with advanced generation strategies and curation techniques. We investigate four research questions assessing how prompting strategies, automated prompt optimization, and post-generation curation affect data quality across four classification tasks: defect detection, functional vs. non-functional, quality vs. non-quality, and security vs. non-security. Our evaluation shows that multi-sample prompting significantly boosts both utility and diversity over single-sample generation, with F1-score gains from 6 to 44 points. The use of PACE (Prompt Actor-Critic Editing) for automated prompt optimization yields task-dependent results, greatly improving functional classification (+32.5 points) but reducing performance on others. Interestingly, similarity-based curation improves diversity but often harms classification performance, indicating that some redundancy may help ML models. Most importantly, our results show that synthetic requirements can match or outperform human-authored ones for specific tasks, with synthetic data surpassing human data for security (+7.8 points) and defect classification (+15.4 points). These findings offer practical insights for AI4RE and chart a viable path to mitigating dataset scarcity through systematic synthetic generation.

[Arxiv](https://arxiv.org/abs/2506.21138)