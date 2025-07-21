# 法官变量：挑战法官无关的法律判决预测

发布时间：2025年07月18日

`LLM应用` `法律判决`

> The Judge Variable: Challenging Judge-Agnostic Legal Judgment Prediction

# 摘要

> 本研究借助机器学习技术，通过分析法国上诉法院的子女抚养权案件，深入探讨了法官在法律判决中的角色。基于法律现实主义与形式主义的争论，我们研究了法官个人决策模式对案件结果的潜在影响，质疑了法官作为法律适用中立变量的传统假设。为严格遵守法国隐私法规，我们采用了匿名化处理措施。研究数据来源于10,306个案件中的18,937项生活安排裁决。我们对比了两类模型：一类是基于单个法官过往裁决训练的专家模型，另一类是基于聚合数据训练的通用模型。我们的预测系统采用了结合大型语言模型（LLMs）进行特征提取和机器学习模型（RF、XGB 和 SVC）进行结果预测的混合方法。研究结果表明，专家模型在预测准确率上显著优于通用模型，其中表现最佳的专家模型F1分数高达92.85%，而通用模型在样本量大20到100倍的情况下仅达到82.63%。专家模型成功捕捉到了法官个人稳定的决策模式，这些模式无法迁移至其他法官。领域内和跨领域有效性测试为法律现实主义提供了实证支持，表明法官的个人特征对案件结果具有显著影响。本研究的所有数据和代码将公开共享。

> This study examines the role of human judges in legal decision-making by using machine learning to predict child physical custody outcomes in French appellate courts. Building on the legal realism-formalism debate, we test whether individual judges' decision-making patterns significantly influence case outcomes, challenging the assumption that judges are neutral variables that apply the law uniformly. To ensure compliance with French privacy laws, we implement a strict pseudonymization process. Our analysis uses 18,937 living arrangements rulings extracted from 10,306 cases. We compare models trained on individual judges' past rulings (specialist models) with a judge-agnostic model trained on aggregated data (generalist models). The prediction pipeline is a hybrid approach combining large language models (LLMs) for structured feature extraction and ML models for outcome prediction (RF, XGB and SVC). Our results show that specialist models consistently achieve higher predictive accuracy than the general model, with top-performing models reaching F1 scores as high as 92.85%, compared to the generalist model's 82.63% trained on 20x to 100x more samples. Specialist models capture stable individual patterns that are not transferable to other judges. In-Domain and Cross-Domain validity tests provide empirical support for legal realism, demonstrating that judicial identity plays a measurable role in legal outcomes. All data and code used will be made available.

[Arxiv](https://arxiv.org/abs/2507.13732)