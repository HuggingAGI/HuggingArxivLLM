# 应对用药过量难题：优化大型语言模型在药物推荐任务中的应用

发布时间：2025年03月05日

`LLM应用` `用药推荐`

> Addressing Overprescribing Challenges: Fine-Tuning Large Language Models for Medication Recommendation Tasks

# 摘要

> 用药推荐系统凭借其根据患者临床数据提供个性化药物组合的能力，成为医疗领域的一大焦点。然而，现有方法在应对多样化的电子健康记录（EHR）系统和非结构化数据时表现欠佳，导致其泛化能力受限。近期，大型语言模型（LLMs）在医疗领域的应用逐渐受到关注，尤其是在辅助医疗专业人员和提升患者护理方面。尽管医疗LLMs在医疗问答等任务中表现出色，但其在临床场景中的实际应用，尤其是用药推荐领域，仍有待进一步探索。

本次研究对通用型和医疗专用型LLMs在用药推荐任务中的表现进行了评估。研究发现，LLMs在用药推荐时存在过度推荐的问题，这不仅增加了临床风险，还降低了推荐的准确性。针对这一问题，我们提出了语言辅助用药推荐方法（LAMO），通过参数高效的微调策略，将开源LLMs优化以提升其在用药推荐场景中的表现。LAMO充分利用临床笔记中的丰富临床信息，这一资源在传统方法中往往未被充分利用。通过我们的方法，LAMO在内部验证的准确性上比之前最先进的方法高出10%以上。此外，时间验证和外部验证均显示，LAMO在不同时间和医院环境中的泛化能力非常 robust。另外，一项针对未在训练数据中的药物推荐的实验表明，即使面对未见数据，LAMO仍能保持令人惊叹的推荐准确性。

> Medication recommendation systems have garnered attention within healthcare for their potential to deliver personalized and efficacious drug combinations based on patient's clinical data. However, existing methodologies encounter challenges in adapting to diverse Electronic Health Records (EHR) systems and effectively utilizing unstructured data, resulting in limited generalization capabilities and suboptimal performance. Recently, interest is growing in harnessing Large Language Models (LLMs) in the medical domain to support healthcare professionals and enhance patient care. Despite the emergence of medical LLMs and their promising results in tasks like medical question answering, their practical applicability in clinical settings, particularly in medication recommendation, often remains underexplored.
  In this study, we evaluate both general-purpose and medical-specific LLMs for medication recommendation tasks. Our findings reveal that LLMs frequently encounter the challenge of overprescribing, leading to heightened clinical risks and diminished medication recommendation accuracy. To address this issue, we propose Language-Assisted Medication Recommendation (LAMO), which employs a parameter-efficient fine-tuning approach to tailor open-source LLMs for optimal performance in medication recommendation scenarios. LAMO leverages the wealth of clinical information within clinical notes, a resource often underutilized in traditional methodologies. As a result of our approach, LAMO outperforms previous state-of-the-art methods by over 10% in internal validation accuracy. Furthermore, temporal and external validations demonstrate LAMO's robust generalization capabilities across various temporal and hospital contexts. Additionally, an out-of-distribution medication recommendation experiment demonstrates LAMO's remarkable accuracy even with medications outside the training data.

[Arxiv](https://arxiv.org/abs/2503.03687)