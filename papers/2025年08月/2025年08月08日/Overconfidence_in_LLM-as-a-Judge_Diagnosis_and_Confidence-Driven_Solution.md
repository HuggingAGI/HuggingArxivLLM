# LLM作为裁判时的过度自信问题：诊断及信心驱动的解决方案

发布时间：2025年08月08日

`LLM应用` `教育评估` `评分系统`

> Overconfidence in LLM-as-a-Judge: Diagnosis and Confidence-Driven Solution

# 摘要

> 大型语言模型（LLMs）被广泛用作自动评分工具，其实用价值不仅取决于准确性，更需要值得信赖、具备风险意识的判断。现有方法主要关注准确性，却忽视了良好校准的自信度的必要性，这对于构建适应性和可靠的评估流程至关重要。在本研究中，我们主张从以准确性为中心的评估转向基于自信度、风险意识的LLM作为评分系统，强调良好校准的自信度对于值得信赖和适应性评估的必要性。我们系统地识别了当前LLM作为评分工具中的**过度自信现象**，其中预测的自信度显著夸大了实际正确性，削弱了实际部署中的可靠性。为了量化这一现象，我们引入了**TH-Score**，一个衡量自信度与准确性对齐的新指标。此外，我们提出了**LLM-as-a-Fuser**，一个集成框架，将LLMs转变为可靠且具备风险意识的评估工具。大量实验表明，我们的方法显著提高了校准效果，并实现了适应性、基于自信度的评估流程，相较于现有基线，取得了更优的可靠性和准确性。

> Large Language Models (LLMs) are widely used as automated judges, where practical value depends on both accuracy and trustworthy, risk-aware judgments. Existing approaches predominantly focus on accuracy, overlooking the necessity of well-calibrated confidence, which is vital for adaptive and reliable evaluation pipelines. In this work, we advocate a shift from accuracy-centric evaluation to confidence-driven, risk-aware LLM-as-a-Judge systems, emphasizing the necessity of well-calibrated confidence for trustworthy and adaptive evaluation. We systematically identify the **Overconfidence Phenomenon** in current LLM-as-a-Judges, where predicted confidence significantly overstates actual correctness, undermining reliability in practical deployment. To quantify this phenomenon, we introduce **TH-Score**, a novel metric measuring confidence-accuracy alignment. Furthermore, we propose **LLM-as-a-Fuser**, an ensemble framework that transforms LLMs into reliable, risk-aware evaluators. Extensive experiments demonstrate that our approach substantially improves calibration and enables adaptive, confidence-driven evaluation pipelines, achieving superior reliability and accuracy compared to existing baselines.

[Arxiv](https://arxiv.org/abs/2508.06225)