# # 多智能体推理在心血管成像表型分析中的应用

发布时间：2025年07月04日

`Agent` `医疗AI`

> Multi-Agent Reasoning for Cardiovascular Imaging Phenotype Analysis

# 摘要

> 理解疾病机制并优化诊断与预后模型，关键在于揭示医学影像表型与疾病风险因素及预后之间的关联。然而，传统方法依赖人为假设检验，往往忽视了影像表型与其他多模态数据间复杂的非线性关系。为此，我们提出了一种名为MESHAgents的多智能体探索协同框架，该框架基于大型语言模型，通过动态提取、揭示和决定关联研究中的混杂因素和表型，以心血管成像作为概念验证。具体而言，我们组建了一支跨学科的AI智能体团队，涵盖心脏病学、生物力学、统计学和临床研究领域，这些智能体通过迭代的自我组织推理，自发生成并聚合见解。该框架将统计相关性与多专家共识动态整合，为表型组关联研究（PheWAS）提供了一条自动化的流水线。我们通过一项基于人群的心脏和主动脉影像表型研究展示了该系统的功能。MESHAgents自主揭示了影像表型与一系列非影像因素之间的相关性，并识别出超越标准人口统计学因素的额外混杂变量。在诊断任务上的验证表明，MESHAgents发现的表型在性能上与专家选择的表型相当，疾病分类任务的平均AUC差异仅为-0.004。值得注意的是，6种疾病类型的召回分数有所提高。我们的框架提供了具有透明推理过程的临床相关影像表型，为专家驱动的方法提供了一种可扩展的替代方案。

> Identifying the associations between imaging phenotypes and disease risk factors and outcomes is essential for understanding disease mechanisms and improving diagnosis and prognosis models. However, traditional approaches rely on human-driven hypothesis testing and selection of association factors, often overlooking complex, non-linear dependencies among imaging phenotypes and other multi-modal data. To address this, we introduce a Multi-agent Exploratory Synergy for the Heart (MESHAgents) framework that leverages large language models as agents to dynamically elicit, surface, and decide confounders and phenotypes in association studies, using cardiovascular imaging as a proof of concept. Specifically, we orchestrate a multi-disciplinary team of AI agents -- spanning cardiology, biomechanics, statistics, and clinical research -- which spontaneously generate and converge on insights through iterative, self-organizing reasoning. The framework dynamically synthesizes statistical correlations with multi-expert consensus, providing an automated pipeline for phenome-wide association studies (PheWAS). We demonstrate the system's capabilities through a population-based study of imaging phenotypes of the heart and aorta. MESHAgents autonomously uncovered correlations between imaging phenotypes and a wide range of non-imaging factors, identifying additional confounder variables beyond standard demographic factors. Validation on diagnosis tasks reveals that MESHAgents-discovered phenotypes achieve performance comparable to expert-selected phenotypes, with mean AUC differences as small as -0.004 on disease classification tasks. Notably, the recall score improves for 6 out of 9 disease types. Our framework provides clinically relevant imaging phenotypes with transparent reasoning, offering a scalable alternative to expert-driven methods.

[Arxiv](https://arxiv.org/abs/2507.03460)