# # 医学大型语言模型中的记忆现象：普遍性、特征与影响

发布时间：2025年09月10日

`LLM应用` `医疗健康`

> Memorization in Large Language Models in Medicine: Prevalence, Characteristics, and Implications

# 摘要

> 大型语言模型（LLMs）在医学领域已展现出巨大潜力。迄今为止，LLMs已广泛应用于诊断辅助、医疗问答及临床信息整合等任务。然而，一个核心的开放性问题仍待解答：LLMs对医学训练数据的记忆程度究竟如何？本研究首次对医学领域LLMs的记忆行为展开全面评估，从普遍性（发生频率）、特征（记忆内容）、体量（记忆信息量）及潜在下游影响（记忆行为对医疗应用的影响）四个维度进行考察。我们系统分析了三类常见适配场景：（1）医学语料库的持续预训练；（2）标准医学基准数据集的微调；（3）真实世界临床数据的微调，涵盖耶鲁纽黑文医疗系统的13,000余份独特住院记录。结果显示，记忆行为在所有适配场景中均普遍存在，且其发生率显著高于通用领域的已有报告。记忆行为会影响LLMs在医学领域的开发与应用，可分为三类：有益型（如准确回忆临床指南及生物医学文献）、无意义型（如重复的免责声明或模板化医疗文书用语）及有害型（如再生特定数据集或敏感临床内容）。基于这些发现，我们提出实用建议：促进能增强领域特定推理与事实准确性的有益记忆，减少无意义记忆以推动超越表面模式的深度学习，同时减轻有害记忆以防止敏感或可识别患者信息的泄露。

> Large Language Models (LLMs) have demonstrated significant potential in medicine. To date, LLMs have been widely applied to tasks such as diagnostic assistance, medical question answering, and clinical information synthesis. However, a key open question remains: to what extent do LLMs memorize medical training data. In this study, we present the first comprehensive evaluation of memorization of LLMs in medicine, assessing its prevalence (how frequently it occurs), characteristics (what is memorized), volume (how much content is memorized), and potential downstream impacts (how memorization may affect medical applications). We systematically analyze common adaptation scenarios: (1) continued pretraining on medical corpora, (2) fine-tuning on standard medical benchmarks, and (3) fine-tuning on real-world clinical data, including over 13,000 unique inpatient records from Yale New Haven Health System. The results demonstrate that memorization is prevalent across all adaptation scenarios and significantly higher than reported in the general domain. Memorization affects both the development and adoption of LLMs in medicine and can be categorized into three types: beneficial (e.g., accurate recall of clinical guidelines and biomedical references), uninformative (e.g., repeated disclaimers or templated medical document language), and harmful (e.g., regeneration of dataset-specific or sensitive clinical content). Based on these findings, we offer practical recommendations to facilitate beneficial memorization that enhances domain-specific reasoning and factual accuracy, minimize uninformative memorization to promote deeper learning beyond surface-level patterns, and mitigate harmful memorization to prevent the leakage of sensitive or identifiable patient information.

[Arxiv](https://arxiv.org/abs/2509.08604)