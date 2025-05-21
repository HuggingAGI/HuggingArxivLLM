# # 从片段到事实：基于大型语言模型的部分信息片段推理

发布时间：2025年05月19日

`LLM理论

论文摘要讨论了大型语言模型（LLMs）在特定攻击条件下的安全性和脆弱性，属于模型理论层面的分析。`

> Fragments to Facts: Partial-Information Fragment Inference from LLMs

# 摘要

> 大型语言模型（LLMs）可能通过记忆和成员推断攻击泄露敏感训练数据。以往研究主要假设攻击者可获取完整的样本或长的有序前缀，但若攻击者仅拥有部分、无序的样本信息，LLMs的脆弱性仍不明确。例如，若攻击者知道一位患者有“高血压”，他们能否通过查询基于患者数据微调的模型得知该患者还患有“骨关节炎”？本文在这一较弱假设下提出了一种更通用的威胁模型，揭示了微调后的LLMs易受特定片段提取攻击。为系统研究这些攻击，我们提出了两种无数据方法：（1）一种受成员推断启发的似然比攻击；（2）一种新颖方法PRISM，通过外部先验对比例进行正则化。通过医疗和法律领域的实例，我们发现这两种方法可与假设访问标记分布内数据的数据感知基线分类器相媲美，凸显了其鲁棒性。

> Large language models (LLMs) can leak sensitive training data through memorization and membership inference attacks. Prior work has primarily focused on strong adversarial assumptions, including attacker access to entire samples or long, ordered prefixes, leaving open the question of how vulnerable LLMs are when adversaries have only partial, unordered sample information. For example, if an attacker knows a patient has "hypertension," under what conditions can they query a model fine-tuned on patient data to learn the patient also has "osteoarthritis?" In this paper, we introduce a more general threat model under this weaker assumption and show that fine-tuned LLMs are susceptible to these fragment-specific extraction attacks. To systematically investigate these attacks, we propose two data-blind methods: (1) a likelihood ratio attack inspired by methods from membership inference, and (2) a novel approach, PRISM, which regularizes the ratio by leveraging an external prior. Using examples from both medical and legal settings, we show that both methods are competitive with a data-aware baseline classifier that assumes access to labeled in-distribution data, underscoring their robustness.

[Arxiv](https://arxiv.org/abs/2505.13819)