# 如何评估医疗人工智能

发布时间：2025年09月15日

`LLM应用` `医疗健康`

> How to Evaluate Medical AI

# 摘要

> 将人工智能（AI）融入医疗诊断工作流程，离不开稳健且一致的评估方法，以保障可靠性、临床相关性，同时兼顾专家判断中的固有变异性。传统指标如精确率和召回率往往难以反映专家判断中的固有变异性，进而造成AI性能评估结果的不一致。诸如Cohen's Kappa等评分者间一致性统计量虽更可靠，但其可解释性欠佳。为此，我们提出了算法诊断的相对精确率和召回率（RPAD和RRAD）——这是一种新的评估指标，通过将AI输出与多个专家意见而非单一参考标准对比。通过结合专家间分歧对性能进行标准化，这些指标为预测诊断质量提供了更稳定、更贴合实际的衡量依据。除了全面分析诊断质量指标外，本研究还带来了一项关键的附带发现：我们的评估方法允许在评估特定病例时，无需从有限列表中挑选诊断结果；相反，无论是待测试模型还是验证其结果的检查者，均以自由文本形式给出诊断。这种用于判定自由文本临床诊断一致性的自动化方法，准确率可达98%，表现十分出色。我们基于360份医疗对话数据对该方法进行了评估，并将多个大型语言模型（LLMs）的表现与医师团队进行对比。大规模研究结果显示，性能领先的模型（如DeepSeek-V3）其一致性已达到甚至超越专家共识水平。更重要的是，我们发现专家判断存在显著差异——且这种差异往往大于AI与人类判断之间的差异。这一发现凸显了绝对指标的局限性，也印证了在医疗AI领域采用相对指标的必要性。

> The integration of artificial intelligence (AI) into medical diagnostic workflows requires robust and consistent evaluation methods to ensure reliability, clinical relevance, and the inherent variability in expert judgments. Traditional metrics like precision and recall often fail to account for the inherent variability in expert judgments, leading to inconsistent assessments of AI performance. Inter-rater agreement statistics like Cohen's Kappa are more reliable but they lack interpretability. We introduce Relative Precision and Recall of Algorithmic Diagnostics (RPAD and RRAD) - a new evaluation metrics that compare AI outputs against multiple expert opinions rather than a single reference. By normalizing performance against inter-expert disagreement, these metrics provide a more stable and realistic measure of the quality of predicted diagnosis. In addition to the comprehensive analysis of diagnostic quality measures, our study contains a very important side result. Our evaluation methodology allows us to avoid selecting diagnoses from a limited list when evaluating a given case. Instead, both the models being tested and the examiners verifying them arrive at a free-form diagnosis. In this automated methodology for establishing the identity of free-form clinical diagnoses, a remarkable 98% accuracy becomes attainable. We evaluate our approach using 360 medical dialogues, comparing multiple large language models (LLMs) against a panel of physicians. Large-scale study shows that top-performing models, such as DeepSeek-V3, achieve consistency on par with or exceeding expert consensus. Moreover, we demonstrate that expert judgments exhibit significant variability - often greater than that between AI and humans. This finding underscores the limitations of any absolute metrics and supports the need to adopt relative metrics in medical AI.

[Arxiv](https://arxiv.org/abs/2509.11941)