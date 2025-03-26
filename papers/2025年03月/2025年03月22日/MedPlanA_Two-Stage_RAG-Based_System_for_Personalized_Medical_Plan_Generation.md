# MedPlan：一个基于RAG的两阶段个性化医疗计划生成系统

发布时间：2025年03月22日

`LLM应用` `知识图谱`

> MedPlan:A Two-Stage RAG-Based System for Personalized Medical Plan Generation

# 摘要

> 尽管大型语言模型（LLMs）在电子健康记录（EHR）应用中取得了显著成功，但现有系统大多聚焦于评估，而忽视了治疗计划的制定。我们发现当前方法存在三大关键局限：它们在单次处理中生成治疗计划，未能模拟临床医生的逐步推理过程；很少整合患者的历史背景信息；且无法有效区分主观与客观临床信息。受SOAP方法论（主观、客观、评估、计划）启发，我们推出了MedPlan框架，通过结构化LLM推理，使其与临床工作流程高度契合。我们的方法采用两阶段架构：首先基于患者症状和客观数据生成临床评估，随后结合检索增强生成的患者特定信息，制定结构化的治疗计划。全面评估证实，MedPlan在评估准确性和治疗计划质量上显著超越传统方法。

> Despite recent success in applying large language models (LLMs) to electronic health records (EHR), most systems focus primarily on assessment rather than treatment planning. We identify three critical limitations in current approaches: they generate treatment plans in a single pass rather than following the sequential reasoning process used by clinicians; they rarely incorporate patient-specific historical context; and they fail to effectively distinguish between subjective and objective clinical information. Motivated by the SOAP methodology (Subjective, Objective, Assessment, Plan), we introduce MedPlan, a novel framework that structures LLM reasoning to align with real-life clinician workflows. Our approach employs a two-stage architecture that first generates a clinical assessment based on patient symptoms and objective data, then formulates a structured treatment plan informed by this assessment and enriched with patient-specific information through retrieval-augmented generation. Comprehensive evaluation demonstrates that our method significantly outperforms baseline approaches in both assessment accuracy and treatment plan quality.

[Arxiv](https://arxiv.org/abs/2503.17900)