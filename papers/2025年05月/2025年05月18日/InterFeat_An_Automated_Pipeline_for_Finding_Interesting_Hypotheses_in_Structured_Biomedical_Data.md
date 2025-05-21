# InterFeat：从结构化生物医学数据中挖掘有趣假设的自动化工具

发布时间：2025年05月18日

`LLM应用` `生物医学` `医学研究`

> InterFeat: An Automated Pipeline for Finding Interesting Hypotheses in Structured Biomedical Data

# 摘要

> 科学发现的核心在于寻找有趣的现象，但这一过程却充满挑战，因为它既繁琐又难以明确界定。我们提出了一种集成管道，用于在结构化生物医学数据中自动发现有趣的简单假设（即特征与目标的关系，包括效应方向及潜在机制）。该管道巧妙结合了机器学习、知识图谱、文献检索和大型语言模型的力量。我们定义“有趣性”为新颖性、实用性和合理性的结合。在来自英国生物银行的8种主要疾病数据中，我们的管道系统能够稳定地发现风险因素，这些因素往往在文献中出现前几年就被识别出来。与基于SHAP的基线方法相比，我们的前40%-53%的候选假设被验证为有趣，而基线方法仅为0%-7%。总体而言，109个候选假设中有28%被医学专家认为是有趣的。该管道系统成功解决了在任何目标上可扩展地量化“有趣性”的挑战。我们公开了数据和代码：https://github.com/LinialLab/InterFeat

> Finding interesting phenomena is the core of scientific discovery, but it is a manual, ill-defined concept. We present an integrative pipeline for automating the discovery of interesting simple hypotheses (feature-target relations with effect direction and a potential underlying mechanism) in structured biomedical data. The pipeline combines machine learning, knowledge graphs, literature search and Large Language Models. We formalize "interestingness" as a combination of novelty, utility and plausibility. On 8 major diseases from the UK Biobank, our pipeline consistently recovers risk factors years before their appearance in the literature. 40--53% of our top candidates were validated as interesting, compared to 0--7% for a SHAP-based baseline. Overall, 28% of 109 candidates were interesting to medical experts. The pipeline addresses the challenge of operationalizing "interestingness" scalably and for any target. We release data and code: https://github.com/LinialLab/InterFeat

[Arxiv](https://arxiv.org/abs/2505.13534)