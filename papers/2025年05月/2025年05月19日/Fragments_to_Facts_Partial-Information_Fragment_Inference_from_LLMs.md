# 从片段到事实：基于LLMs的部分信息片段推理

发布时间：2025年05月19日

`LLM理论`

> Fragments to Facts: Partial-Information Fragment Inference from LLMs

# 摘要

> 大型语言模型（LLMs）可能通过记忆和成员推断攻击泄露敏感训练数据。此前研究主要关注强对抗假设，例如攻击者可访问完整样本或长有序前缀。然而，当攻击者仅掌握部分无序样本信息时，LLMs的脆弱性仍待探讨。例如，若攻击者得知患者有“高血压”，能否通过查询微调过的模型推断出该患者还患有“骨关节炎”？本文在更弱的假设下提出了一种更通用的威胁模型，揭示微调后的LLMs易受片段特定提取攻击。为系统研究这些攻击，我们提出了两种数据盲方法：（1）受成员推断启发的似然率攻击，以及（2）一种新颖的PRISM方法，通过外部先验正则化比率。通过医疗和法律领域的实例，我们展示了这两种方法与假设可访问标签内分布数据的基线分类器相当，凸显了它们的鲁棒性。

> Large language models (LLMs) can leak sensitive training data through memorization and membership inference attacks. Prior work has primarily focused on strong adversarial assumptions, including attacker access to entire samples or long, ordered prefixes, leaving open the question of how vulnerable LLMs are when adversaries have only partial, unordered sample information. For example, if an attacker knows a patient has "hypertension," under what conditions can they query a model fine-tuned on patient data to learn the patient also has "osteoarthritis?" In this paper, we introduce a more general threat model under this weaker assumption and show that fine-tuned LLMs are susceptible to these fragment-specific extraction attacks. To systematically investigate these attacks, we propose two data-blind methods: (1) a likelihood ratio attack inspired by methods from membership inference, and (2) a novel approach, PRISM, which regularizes the ratio by leveraging an external prior. Using examples from both medical and legal settings, we show that both methods are competitive with a data-aware baseline classifier that assumes access to labeled in-distribution data, underscoring their robustness.

[Arxiv](https://arxiv.org/abs/2505.13819)