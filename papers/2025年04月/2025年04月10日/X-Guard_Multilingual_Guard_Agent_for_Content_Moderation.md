# # X-Guard：多语言内容审核守护代理
X-Guard 是一个多语言内容审核守护代理，通过强大的多语言理解和生成能力，为内容审核提供智能化解决方案。

发布时间：2025年04月10日

`Agent` `内容安全` `跨语言`

> X-Guard: Multilingual Guard Agent for Content Moderation

# 摘要

> 大型语言模型 (LLMs) 已迅速成为关键领域众多应用的核心，这些领域对可靠性要求极高。尽管在安全框架和防护措施方面取得了长足进步，但目前的保护措施仍存在关键漏洞，尤其是在多语言环境下。现有安全系统依然容易受到低资源语言和代码切换技术的攻击，这主要是因为它们的设计以英语为中心。此外，由于缺乏多样化的跨语言训练数据，有效多语言防护措施的开发受到限制。即使像 Llama Guard-3 这样的最新解决方案，尽管提供了多语言支持，但其决策过程缺乏透明度。

我们通过引入 X-Guard 代理来应对这些挑战，该代理是一个透明的多语言安全代理，旨在在各种语言环境中提供内容审核。X-Guard 能够有效防御传统的低资源语言攻击以及复杂的代码切换攻击。我们的方法包括：整理并增强多个开源安全数据集，附带明确的评估理由；采用陪审团法官的方法来缓解个别法官 LLM 提供商的偏见；创建一个涵盖 132 种语言、包含 500 万个数据点的多语言安全数据集；以及开发一个两阶段架构，结合定制微调的 mBART-50 翻译模块和通过监督微调和 GRPO 训练的评估 X-Guard 3B 模型。

我们的实证评估表明，X-Guard 在多种语言中有效检测不安全内容，同时在整个安全评估过程中保持透明。我们的工作代表了为 LLM 及其集成系统创建强大、透明且语言包容的安全系统的重要进展。

> Large Language Models (LLMs) have rapidly become integral to numerous applications in critical domains where reliability is paramount. Despite significant advances in safety frameworks and guardrails, current protective measures exhibit crucial vulnerabilities, particularly in multilingual contexts. Existing safety systems remain susceptible to adversarial attacks in low-resource languages and through code-switching techniques, primarily due to their English-centric design. Furthermore, the development of effective multilingual guardrails is constrained by the scarcity of diverse cross-lingual training data. Even recent solutions like Llama Guard-3, while offering multilingual support, lack transparency in their decision-making processes. We address these challenges by introducing X-Guard agent, a transparent multilingual safety agent designed to provide content moderation across diverse linguistic contexts. X-Guard effectively defends against both conventional low-resource language attacks and sophisticated code-switching attacks. Our approach includes: curating and enhancing multiple open-source safety datasets with explicit evaluation rationales; employing a jury of judges methodology to mitigate individual judge LLM provider biases; creating a comprehensive multilingual safety dataset spanning 132 languages with 5 million data points; and developing a two-stage architecture combining a custom-finetuned mBART-50 translation module with an evaluation X-Guard 3B model trained through supervised finetuning and GRPO training. Our empirical evaluations demonstrate X-Guard's effectiveness in detecting unsafe content across multiple languages while maintaining transparency throughout the safety evaluation process. Our work represents a significant advancement in creating robust, transparent, and linguistically inclusive safety systems for LLMs and its integrated systems.

[Arxiv](https://arxiv.org/abs/2504.08848)