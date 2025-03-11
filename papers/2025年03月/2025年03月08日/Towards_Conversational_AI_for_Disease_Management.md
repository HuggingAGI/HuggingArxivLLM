# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月08日

`LLM应用

摘要中提到的论文讨论了将大型语言模型（LLMs）应用于医疗诊断和临床管理中的推理能力。具体来说，他们开发了一个名为AMIE的智能系统，该系统整合了疾病进展、治疗反应评估和用药处方等专业推理能力，并结合了Gemini的长上下文能力来确保输出符合权威临床知识。研究通过虚拟考试和基准测试评估了该系统的性能，结果显示其在管理推理和用药推理方面优于全科医生。这些内容都涉及将LLMs应用于实际的医疗场景，因此归类为LLM应用。` `临床诊断`

> Towards Conversational AI for Disease Management

# 摘要

> 尽管大型语言模型 (LLMs) 在诊断对话中展现出潜力，但在疾病进展、治疗反应和安全用药处方等有效管理推理方面的能力，仍有待深入探索。我们通过一种新型基于 LLM 的智能系统 AMIE（Articulate Medical Intelligence Explorer），进一步提升了其诊断能力。该系统专为临床管理和对话设计，整合了对疾病演变、多次患者就诊经历、治疗反应评估以及用药处方的专业推理能力。为了确保推理基于权威临床知识，AMIE 借助 Gemini 的长上下文能力，结合上下文检索与结构化推理，使其输出与最新临床实践指南和药物手册保持一致。在一项随机、盲法虚拟客观结构化临床考试 (OSCE) 中，AMIE 与 21 名全科医生 (PCPs) 在 100 个反映英国 NICE 指南和 BMJ 最佳实践指南的多就诊案例场景中展开对比。根据专科医生评估，AMIE 的管理推理能力不劣于全科医生，并在治疗和检查的精准性以及管理计划与临床指南的对齐和依据方面表现更优。为了评估用药推理能力，我们开发了 RxQA，这是一个基于美国和英国两个国家药物手册的多项选择题基准，并由认证药剂师验证。尽管 AMIE 和全科医生都能受益于访问外部药物信息的能力，但 AMIE 在更高难度的问题上表现更优。虽然实际应用仍需进一步研究，但 AMIE 在各项评估中的强劲表现标志着其作为疾病管理工具的对话式 AI 的重要进展。

> While large language models (LLMs) have shown promise in diagnostic dialogue, their capabilities for effective management reasoning - including disease progression, therapeutic response, and safe medication prescription - remain under-explored. We advance the previously demonstrated diagnostic capabilities of the Articulate Medical Intelligence Explorer (AMIE) through a new LLM-based agentic system optimised for clinical management and dialogue, incorporating reasoning over the evolution of disease and multiple patient visit encounters, response to therapy, and professional competence in medication prescription. To ground its reasoning in authoritative clinical knowledge, AMIE leverages Gemini's long-context capabilities, combining in-context retrieval with structured reasoning to align its output with relevant and up-to-date clinical practice guidelines and drug formularies. In a randomized, blinded virtual Objective Structured Clinical Examination (OSCE) study, AMIE was compared to 21 primary care physicians (PCPs) across 100 multi-visit case scenarios designed to reflect UK NICE Guidance and BMJ Best Practice guidelines. AMIE was non-inferior to PCPs in management reasoning as assessed by specialist physicians and scored better in both preciseness of treatments and investigations, and in its alignment with and grounding of management plans in clinical guidelines. To benchmark medication reasoning, we developed RxQA, a multiple-choice question benchmark derived from two national drug formularies (US, UK) and validated by board-certified pharmacists. While AMIE and PCPs both benefited from the ability to access external drug information, AMIE outperformed PCPs on higher difficulty questions. While further research would be needed before real-world translation, AMIE's strong performance across evaluations marks a significant step towards conversational AI as a tool in disease management.

[Arxiv](https://arxiv.org/abs/2503.06074)