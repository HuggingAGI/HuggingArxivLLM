# # 摘要  
从 EMR 数据到临床洞察：一个基于 LLM 的自动化诊前问卷生成框架

发布时间：2025年08月01日

`LLM应用` `健康管理`

> From EMR Data to Clinical Insight: An LLM-Driven Framework for Automated Pre-Consultation Questionnaire Generation

# 摘要

> 预咨询是有效医疗交付的关键环节，但如何从复杂庞大的电子病历（EMR）中生成全面的预咨询问卷一直是个难题。直接使用大型语言模型（LLM）的方法在信息完整性、逻辑顺序以及疾病层面的综合能力方面存在诸多挑战。为此，我们提出了一种创新的多阶段LLM驱动框架：第一阶段从EMR中提取原子声明（含时间的关键事实）；第二阶段构建个人因果网络，并通过聚类EMR语料库中的代表性网络来综合疾病知识；第三阶段基于这些结构化表示生成定制化个人化和标准化的疾病特异性问卷。通过构建显式的临床知识，该框架成功克服了直接方法的局限性。在真实世界的EMR数据集上进行评估，并经临床专家验证，我们的方法在信息覆盖范围、诊断相关性、可理解性和生成时间方面均表现出色，充分展现了其在增强患者信息收集方面的实用潜力。

> Pre-consultation is a critical component of effective healthcare delivery. However, generating comprehensive pre-consultation questionnaires from complex, voluminous Electronic Medical Records (EMRs) is a challenging task. Direct Large Language Model (LLM) approaches face difficulties in this task, particularly regarding information completeness, logical order, and disease-level synthesis. To address this issue, we propose a novel multi-stage LLM-driven framework: Stage 1 extracts atomic assertions (key facts with timing) from EMRs; Stage 2 constructs personal causal networks and synthesizes disease knowledge by clustering representative networks from an EMR corpus; Stage 3 generates tailored personal and standardized disease-specific questionnaires based on these structured representations. This framework overcomes limitations of direct methods by building explicit clinical knowledge. Evaluated on a real-world EMR dataset and validated by clinical experts, our method demonstrates superior performance in information coverage, diagnostic relevance, understandability, and generation time, highlighting its practical potential to enhance patient information collection.

[Arxiv](https://arxiv.org/abs/2508.00581)