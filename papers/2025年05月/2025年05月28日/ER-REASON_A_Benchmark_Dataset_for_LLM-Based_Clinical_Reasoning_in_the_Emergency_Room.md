# ER-REASON：面向急诊室临床推理的大型语言模型基准数据集

发布时间：2025年05月28日

`LLM应用` `人工智能`

> ER-REASON: A Benchmark Dataset for LLM-Based Clinical Reasoning in the Emergency Room

# 摘要

> 大型语言模型（LLMs）在基于执业考试的医疗问答任务中表现突出。然而，现实世界中的评估往往依赖于昂贵的人工标注员，现有基准测试通常专注于孤立任务，很少涵盖临床推理或医疗决策背后的完整工作流程。本文介绍的ER-Reason基准测试，专注于评估LLM在急诊室（ER）环境下的临床推理和决策能力。ER是一个高压环境，临床医生在时间紧迫的情况下，需快速做出影响深远的决策，面对多样的患者情况和医学专科领域。

ER-Reason包含3984名患者的资料，涵盖25174份匿名纵向临床记录，包括出院总结、病程记录、病史与体检报告、会诊记录、超声心动图报告、影像学记录和急诊科医生文档。该基准测试涵盖了ER工作流程中的关键阶段：分诊接诊、初步评估、治疗选择、处置规划和最终诊断，每个阶段都经过精心设计，以反映核心临床推理过程，例如通过排除法进行的鉴别诊断。

我们还收集了72份完整的医生撰写推理说明，这些说明解释了推理过程，类似于住院医师培训中使用的教学过程，而这些通常在ER文档中缺失。在ER-Reason上对最先进的LLMs进行评估，揭示了LLM生成与临床医生撰写的临床推理之间的差距，强调了未来研究需要填补这一鸿沟。


> Large language models (LLMs) have been extensively evaluated on medical question answering tasks based on licensing exams. However, real-world evaluations often depend on costly human annotators, and existing benchmarks tend to focus on isolated tasks that rarely capture the clinical reasoning or full workflow underlying medical decisions. In this paper, we introduce ER-Reason, a benchmark designed to evaluate LLM-based clinical reasoning and decision-making in the emergency room (ER)--a high-stakes setting where clinicians make rapid, consequential decisions across diverse patient presentations and medical specialties under time pressure. ER-Reason includes data from 3,984 patients, encompassing 25,174 de-identified longitudinal clinical notes spanning discharge summaries, progress notes, history and physical exams, consults, echocardiography reports, imaging notes, and ER provider documentation. The benchmark includes evaluation tasks that span key stages of the ER workflow: triage intake, initial assessment, treatment selection, disposition planning, and final diagnosis--each structured to reflect core clinical reasoning processes such as differential diagnosis via rule-out reasoning. We also collected 72 full physician-authored rationales explaining reasoning processes that mimic the teaching process used in residency training, and are typically absent from ER documentation. Evaluations of state-of-the-art LLMs on ER-Reason reveal a gap between LLM-generated and clinician-authored clinical reasoning for ER decisions, highlighting the need for future research to bridge this divide.

[Arxiv](https://arxiv.org/abs/2505.22919)