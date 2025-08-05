# 临床记录驱动的智能体特征生成与结果预测

发布时间：2025年08月03日

`LLM应用

摘要中描述了使用大型语言模型（LLMs）来处理电子健康记录中的非结构化临床笔记，生成结构化特征以提升预测建模的效果。虽然提到了多智能体系统，但核心贡献在于LLM的应用，因此归类为LLM应用。`

> Agent-Based Feature Generation from Clinical Notes for Outcome Prediction

# 摘要

> 电子健康记录（EHRs）中的非结构化临床笔记蕴含丰富信息，可提升预测建模效果。然而，提取这些笔记中的有效特征仍具挑战。当前方法从劳动密集型的手动临床特征生成（CFG），到完全自动化的表征特征生成（RFG），但后者缺乏可解释性和临床相关性。我们介绍了一种基于大型语言模型（LLMs）的模块化多智能体系统——SNOW（可扩展的笔记到结果工作流），它能自主从非结构化笔记中生成结构化临床特征，无需人工干预。

在对147名斯坦福医疗患者的5年前列腺癌复发预测任务中，SNOW的表现令人瞩目。虽然手动CFG达到了最佳性能（AUC-ROC: 0.771），但SNOW在无需任何临床专业知识的情况下，以0.761的优异成绩紧随其后，显著超越仅使用基线特征（0.691）和所有RFG方法。基于LLM的临床专家引导方法虽表现不俗（0.732），但仍需专家参与。SNOW通过其专用智能体完成特征发现、提取、验证、后处理和聚合，生成可解释特征，精准捕捉通常仅能通过手动审查获得的复杂临床信息。本研究证明，自主LLM系统可在大规模上实现专家级特征工程，同时保持临床部署所需的可解释性，这可能彻底改变临床ML模型利用非结构化EHR数据的方式。

> Electronic health records (EHRs) contain rich unstructured clinical notes that could enhance predictive modeling, yet extracting meaningful features from these notes remains challenging. Current approaches range from labor-intensive manual clinician feature generation (CFG) to fully automated representational feature generation (RFG) that lack interpretability and clinical relevance. Here we introduce SNOW (Scalable Note-to-Outcome Workflow), a modular multi-agent system powered by large language models (LLMs) that autonomously generates structured clinical features from unstructured notes without human intervention. We evaluated SNOW against manual CFG, clinician-guided LLM approaches, and RFG methods for predicting 5-year prostate cancer recurrence in 147 patients from Stanford Healthcare. While manual CFG achieved the highest performance (AUC-ROC: 0.771), SNOW matched this performance (0.761) without requiring any clinical expertise, significantly outperforming both baseline features alone (0.691) and all RFG approaches. The clinician-guided LLM method also performed well (0.732) but still required expert input. SNOW's specialized agents handle feature discovery, extraction, validation, post-processing, and aggregation, creating interpretable features that capture complex clinical information typically accessible only through manual review. Our findings demonstrate that autonomous LLM systems can replicate expert-level feature engineering at scale, potentially transforming how clinical ML models leverage unstructured EHR data while maintaining the interpretability essential for clinical deployment.

[Arxiv](https://arxiv.org/abs/2508.01956)