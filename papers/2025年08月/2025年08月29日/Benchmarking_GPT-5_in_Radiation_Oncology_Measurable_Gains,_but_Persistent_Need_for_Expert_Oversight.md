# # GPT-5在放射肿瘤学中的基准测试：可量化收益显著，但专家监督仍不可或缺

发布时间：2025年08月29日

`LLM应用` `医疗健康`

> Benchmarking GPT-5 in Radiation Oncology: Measurable Gains, but Persistent Need for Expert Oversight

# 摘要

> 引言：大型语言模型（LLM）在临床决策支持领域展现出巨大潜力，而GPT-5作为新型LLM系统，专门面向肿瘤学应用。
  方法：研究通过两个互补基准评估其性能：（i）美国放射学会（ACR）2021年放射肿瘤学培训考试（TXIT），含300道多项选择题；（ii）精选的60个真实放射肿瘤学病例，覆盖不同疾病部位与治疗适应症。在病例评估中，GPT-5被要求生成简洁治疗方案，由四名委员会认证的放射肿瘤学家对方案的正确性、全面性及幻觉情况进行评分，并采用Fleiss' κ系数量化评分者间信度。
  结果：在TXIT基准中，GPT-5平均准确率达92.8%，显著优于GPT-4（78.8%）和GPT-3.5（62.1%），尤其在剂量和诊断领域性能提升最为突出。病例评估显示，其治疗建议的正确性（平均3.24/4分，95%置信区间：3.11-3.38）和全面性（3.59/4分，95%置信区间：3.49-3.69）评分均较高。幻觉现象罕见，且无病例达成存在幻觉的多数共识。评分者间一致性较低（正确性的Fleiss' κ系数为0.083），反映了临床判断本身存在的差异性。错误主要集中于需精确试验知识或详细临床调整的复杂场景。
  讨论：GPT-5在放射肿瘤学多项选择基准上明显优于前代模型。尽管其在生成真实世界放射肿瘤学治疗建议方面表现良好，但正确性评分显示仍有提升空间。尽管幻觉不常见，但实质性错误的存在提示，GPT-5生成的建议在临床应用前需经过严格的专家审核。

> Introduction: Large language models (LLM) have shown great potential in clinical decision support. GPT-5 is a novel LLM system that has been specifically marketed towards oncology use.
  Methods: Performance was assessed using two complementary benchmarks: (i) the ACR Radiation Oncology In-Training Examination (TXIT, 2021), comprising 300 multiple-choice items, and (ii) a curated set of 60 authentic radiation oncologic vignettes representing diverse disease sites and treatment indications. For the vignette evaluation, GPT-5 was instructed to generate concise therapeutic plans. Four board-certified radiation oncologists rated correctness, comprehensiveness, and hallucinations. Inter-rater reliability was quantified using Fleiss' \k{appa}.
  Results: On the TXIT benchmark, GPT-5 achieved a mean accuracy of 92.8%, outperforming GPT-4 (78.8%) and GPT-3.5 (62.1%). Domain-specific gains were most pronounced in Dose and Diagnosis. In the vignette evaluation, GPT-5's treatment recommendations were rated highly for correctness (mean 3.24/4, 95% CI: 3.11-3.38) and comprehensiveness (3.59/4, 95% CI: 3.49-3.69). Hallucinations were rare with no case reaching majority consensus for their presence. Inter-rater agreement was low (Fleiss' \k{appa} 0.083 for correctness), reflecting inherent variability in clinical judgment. Errors clustered in complex scenarios requiring precise trial knowledge or detailed clinical adaptation.
  Discussion: GPT-5 clearly outperformed prior model variants on the radiation oncology multiple-choice benchmark. Although GPT-5 exhibited favorable performance in generating real-world radiation oncology treatment recommendations, correctness ratings indicate room for further improvement. While hallucinations were infrequent, the presence of substantive errors underscores that GPT-5-generated recommendations require rigorous expert oversight before clinical implementation.

[Arxiv](https://arxiv.org/abs/2508.21777)