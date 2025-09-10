# CancerGUIDE：基于内部不一致性估计的癌症指南理解

发布时间：2025年09月08日

`Agent` `医疗健康`

> CancerGUIDE: Cancer Guideline Understanding via Internal Disagreement Estimation

# 摘要

> 美国国家综合癌症网络（NCCN）制定了循证癌症治疗指南。将复杂的患者病情转化为符合指南的治疗建议不仅耗时，还需要专业知识，且容易出错。大型语言模型（LLM）的能力提升有望缩短生成治疗建议的时间并提高准确性。我们提出了一种基于LLM智能体的方法，可自动为非小细胞肺癌（NSCLC）患者生成符合指南的治疗方案。我们的贡献主要有三点。首先，我们构建了一个包含121例NSCLC患者的新型纵向数据集，涵盖临床就诊记录、诊断结果和病史，每例均由认证肿瘤专家依据相应的NCCN指南轨迹进行专业注释。其次，我们发现现有LLM具备领域特定知识，能够为模型开发和评估生成高质量的代理基准，与专家注释的基准相关性强（斯皮尔曼系数r=0.88，均方根误差RMSE=0.08）。第三，我们开发了一种混合方法，结合昂贵的人工注释和模型一致性信息，构建了用于预测患者适用指南的智能体框架，以及一个元分类器。该元分类器通过校准的治疗建议置信度分数验证预测准确性（AUROC=0.800），这一能力对于传达输出准确性、定制性能权衡和支持法规遵从至关重要。这项研究建立了一个临床可行的基于LLM的指南遵循系统框架，在平衡准确性、可解释性和法规要求的同时降低了注释成本，为自动化临床决策支持提供了可扩展的解决方案。

> The National Comprehensive Cancer Network (NCCN) provides evidence-based guidelines for cancer treatment. Translating complex patient presentations into guideline-compliant treatment recommendations is time-intensive, requires specialized expertise, and is prone to error. Advances in large language model (LLM) capabilities promise to reduce the time required to generate treatment recommendations and improve accuracy. We present an LLM agent-based approach to automatically generate guideline-concordant treatment trajectories for patients with non-small cell lung cancer (NSCLC). Our contributions are threefold. First, we construct a novel longitudinal dataset of 121 cases of NSCLC patients that includes clinical encounters, diagnostic results, and medical histories, each expertly annotated with the corresponding NCCN guideline trajectories by board-certified oncologists. Second, we demonstrate that existing LLMs possess domain-specific knowledge that enables high-quality proxy benchmark generation for both model development and evaluation, achieving strong correlation (Spearman coefficient r=0.88, RMSE = 0.08) with expert-annotated benchmarks. Third, we develop a hybrid approach combining expensive human annotations with model consistency information to create both the agent framework that predicts the relevant guidelines for a patient, as well as a meta-classifier that verifies prediction accuracy with calibrated confidence scores for treatment recommendations (AUROC=0.800), a critical capability for communicating the accuracy of outputs, custom-tailoring tradeoffs in performance, and supporting regulatory compliance. This work establishes a framework for clinically viable LLM-based guideline adherence systems that balance accuracy, interpretability, and regulatory requirements while reducing annotation costs, providing a scalable pathway toward automated clinical decision support.

[Arxiv](https://arxiv.org/abs/2509.07325)