# GEMA-Score：用于放射科报告评估的细粒度可解释多智能体评分系统

发布时间：2025年03月07日

`LLM应用

理由：这篇论文主要探讨了大型语言模型在医学报告生成中的应用，特别是提出了一个基于多智能体的评分系统来评估生成报告的质量。虽然提到了多智能体的概念，但核心内容还是围绕LLM的应用，因此归类为LLM应用。` `评分系统`

> GEMA-Score: Granular Explainable Multi-Agent Score for Radiology Report Evaluation

# 摘要

> 自动医学报告生成不仅助力临床诊断，还能有效缓解放射科医生的工作压力，并有望提升诊断的一致性。然而，现有的评估指标主要关注生成报告与人工报告在关键医疗信息覆盖上的准确性，却忽视了报告中异常的位置和确定性等关键细节。这种局限性不仅限制了对生成报告可靠性的全面评估，还可能带来临床应用中的风险。因此，我们在本文中提出了细粒度可解释的多智能体评分（GEMA-Score），通过基于大型语言模型的多智能体工作流实现客观量化与主观评估的结合。GEMA-Score能够解析结构化报告，并通过智能体间的信息交互进行NER-F1计算，从而全面评估疾病诊断、位置、严重性和不确定性。此外，基于LLM的评分智能体还能从完整性和可读性等多个维度进行评估，并提供详细的解释性反馈。实验结果表明，GEMA-Score在公共数据集上与人类专家评估结果具有高度相关性（Rexval数据集的Kendall系数为0.70，RadEvalX数据集的Kendall系数为0.54），充分证明了其在临床评分中的有效性。项目演示已匿名开放，欢迎访问https://github.com/Zhenxuan-Zhang/GEMA_score体验。


> Automatic medical report generation supports clinical diagnosis, reduces the workload of radiologists, and holds the promise of improving diagnosis consistency. However, existing evaluation metrics primarily assess the accuracy of key medical information coverage in generated reports compared to human-written reports, while overlooking crucial details such as the location and certainty of reported abnormalities. These limitations hinder the comprehensive assessment of the reliability of generated reports and pose risks in their selection for clinical use. Therefore, we propose a Granular Explainable Multi-Agent Score (GEMA-Score) in this paper, which conducts both objective quantification and subjective evaluation through a large language model-based multi-agent workflow. Our GEMA-Score parses structured reports and employs NER-F1 calculations through interactive exchanges of information among agents to assess disease diagnosis, location, severity, and uncertainty. Additionally, an LLM-based scoring agent evaluates completeness, readability, and clinical terminology while providing explanatory feedback. Extensive experiments validate that GEMA-Score achieves the highest correlation with human expert evaluations on a public dataset, demonstrating its effectiveness in clinical scoring (Kendall coefficient = 0.70 for Rexval dataset and Kendall coefficient = 0.54 for RadEvalX dataset). The anonymous project demo is available at: https://github.com/Zhenxuan-Zhang/GEMA_score.

[Arxiv](https://arxiv.org/abs/2503.05347)