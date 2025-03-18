# MAP：大型语言模型在住院流程中的评估和多智能体增强

发布时间：2025年03月17日

`Agent` `决策支持系统`

> MAP: Evaluation and Multi-Agent Enhancement of Large Language Models for Inpatient Pathways

# 摘要

> 住院路径的复杂性对临床医生提出了巨大挑战，需要基于全面的患者信息进行精准决策。尽管大型语言模型（LLMs）在医疗领域取得突破，但受限于缺乏大规模住院数据集，AI在住院路径系统中的研究仍显不足。现有医疗基准多聚焦于医学问答和检查，忽视了住院环境中临床决策的多维度特性。

为填补这一研究空白，我们从MIMIC-IV数据库构建了住院路径决策支持（IPDS）基准，涵盖九个分诊科室、17个主要疾病类别及16种标准化治疗方案，共计51,274例。在此基础上，我们提出了多智能体住院路径（MAP）框架，通过三个临床智能体协同工作完成住院路径任务：分诊智能体负责患者入院管理，诊断智能体作为科室主要决策者，治疗智能体提供治疗方案。此外，MAP框架还包括一个总智能体，负责监督住院路径，协调并优化这三个临床智能体的工作流程。

实验结果表明，与当前最先进的大型语言模型HuatuoGPT2-13B相比，MAP框架将诊断准确率提升了25.10%。更值得关注的是，MAP在临床合规性方面表现出色，比三名认证临床医生高出10%-12%，为住院路径系统的发展奠定了坚实基础。


> Inpatient pathways demand complex clinical decision-making based on comprehensive patient information, posing critical challenges for clinicians. Despite advancements in large language models (LLMs) in medical applications, limited research focused on artificial intelligence (AI) inpatient pathways systems, due to the lack of large-scale inpatient datasets. Moreover, existing medical benchmarks typically concentrated on medical question-answering and examinations, ignoring the multifaceted nature of clinical decision-making in inpatient settings. To address these gaps, we first developed the Inpatient Pathway Decision Support (IPDS) benchmark from the MIMIC-IV database, encompassing 51,274 cases across nine triage departments and 17 major disease categories alongside 16 standardized treatment options. Then, we proposed the Multi-Agent Inpatient Pathways (MAP) framework to accomplish inpatient pathways with three clinical agents, including a triage agent managing the patient admission, a diagnosis agent serving as the primary decision maker at the department, and a treatment agent providing treatment plans. Additionally, our MAP framework includes a chief agent overseeing the inpatient pathways to guide and promote these three clinician agents. Extensive experiments showed our MAP improved the diagnosis accuracy by 25.10% compared to the state-of-the-art LLM HuatuoGPT2-13B. It is worth noting that our MAP demonstrated significant clinical compliance, outperforming three board-certified clinicians by 10%-12%, establishing a foundation for inpatient pathways systems.

[Arxiv](https://arxiv.org/abs/2503.13205)