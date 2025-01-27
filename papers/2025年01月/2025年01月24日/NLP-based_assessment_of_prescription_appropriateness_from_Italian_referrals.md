# 基于NLP的意大利转诊处方合理性评估

发布时间：2025年01月24日

`LLM应用

**理由**：该论文描述了一种利用基于Transformer模型的嵌入技术来处理和评估医疗转诊文本的流程。虽然论文中没有明确提到“大型语言模型”（LLM），但Transformer模型是LLM的核心架构之一，且该研究将Transformer模型应用于具体的NLP任务（即医疗文本的聚类和适当性评估），因此可以归类为“LLM应用”。`

> NLP-based assessment of prescription appropriateness from Italian referrals

# 摘要

> # 目标
本研究提出了一种自然语言处理（NLP）流程，用于评估意大利转诊中处方的适当性。由于处方原因仅以自由文本记录，自动与指南对比变得复杂。该流程首次全面总结了转诊原因并量化了其适当性，虽然基于具体案例，但方法设计具有广泛适用性。
# 方法
我们利用基于Transformer模型的嵌入技术，对转诊文本进行聚类，并将聚类结果与现有指南对齐。案例研究基于2019至2021年间伦巴第大区496,971份下肢静脉彩色多普勒超声转诊数据，其中1,000份样本经过手动注释以验证结果。
# 结果
在注释样本中，流程在转诊原因（Prec=92.43%，Rec=83.28%）和适当性（Prec=93.58%，Rec=91.52%）上表现优异。整体数据分析显示，34.32%的转诊适当，34.07%不适当，14.37%可能不适当，17.24%无法与指南对应。
# 结论
该流程成功评估了大样本中的处方适当性，为卫生部门提供了有力工具。研究结果支持了伦巴第大区加强建议和减少不适当转诊的努力。

> Objective: This study proposes a Natural Language Processing pipeline to evaluate prescription appropriateness in Italian referrals, where reasons for prescriptions are recorded only as free text, complicating automated comparisons with guidelines. The pipeline aims to derive, for the first time, a comprehensive summary of the reasons behind these referrals and a quantification of their appropriateness. While demonstrated in a specific case study, the approach is designed to generalize to other types of examinations.
  Methods: Leveraging embeddings from a transformer-based model, the proposed approach clusters referral texts, maps clusters to labels, and aligns these labels with existing guidelines. We present a case study on a dataset of 496,971 referrals, consisting of all referrals for venous echocolordopplers of the lower limbs between 2019 and 2021 in the Lombardy Region. A sample of 1,000 referrals was manually annotated to validate the results.
  Results: The pipeline exhibited high performance for referrals' reasons (Prec=92.43%, Rec=83.28%) and excellent results for referrals' appropriateness (Prec=93.58%, Rec=91.52%) on the annotated subset. Analysis of the entire dataset identified clusters matching guideline-defined reasons - both appropriate and inappropriate - as well as clusters not addressed in the guidelines. Overall, 34.32% of referrals were marked as appropriate, 34.07% inappropriate, 14.37% likely inappropriate, and 17.24% could not be mapped to guidelines.
  Conclusions: The proposed pipeline effectively assessed prescription appropriateness across a large dataset, serving as a valuable tool for health authorities. Findings have informed the Lombardy Region's efforts to strengthen recommendations and reduce the burden of inappropriate referrals.

[Arxiv](https://arxiv.org/abs/2501.14701)