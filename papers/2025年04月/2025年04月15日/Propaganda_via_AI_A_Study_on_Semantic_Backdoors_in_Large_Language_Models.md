# AI宣传？大型语言模型中的语义后门探索。

发布时间：2025年04月15日

`LLM理论

论文摘要：大型语言模型 (LLMs) 在多种语言任务中表现优异，但它们仍易受后门攻击，即攻击者植入隐藏触发器以操纵模型输出。传统防御方法专注于显式的token级异常，忽视了概念层面的语义后门——这些触发器依赖于意义线索而非词汇怪异性。我们在受控微调设置中证明，仅需少量中毒数据即可植入语义后门，证实其可行性。我们定义了 LLM 中的语义后门，并提出 RAVEN（“响应异常监测以发现语义后门”）框架，结合语义熵和跨模型一致性分析。该框架通过结构化提示探测多模型，利用双向蕴含聚类响应，并标记异常一致输出；跨模型比较可区分模型特异性异常与语料库偏差。对 GPT-4o、Llama、DeepSeek 和 Mistral 等 LLM 的评估揭示了未被发现的语义后门，首次证明了这些隐藏漏洞的存在，强调了对部署模型进行概念审计的迫切需求。我们的代码和数据已开源，地址为 https://github.com/NayMyatMin/RAVEN。` `人工智能安全` `模型安全性`

> Propaganda via AI? A Study on Semantic Backdoors in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 在多种语言任务中表现优异，但它们仍易受后门攻击，即攻击者植入隐藏触发器以操纵模型输出。传统防御方法专注于显式的token级异常，忽视了概念层面的语义后门——这些触发器依赖于意义线索而非词汇怪异性。我们在受控微调设置中证明，仅需少量中毒数据即可植入语义后门，证实其可行性。我们定义了 LLM 中的语义后门，并提出 RAVEN（“响应异常监测以发现语义后门”）框架，结合语义熵和跨模型一致性分析。该框架通过结构化提示探测多模型，利用双向蕴含聚类响应，并标记异常一致输出；跨模型比较可区分模型特异性异常与语料库偏差。对 GPT-4o、Llama、DeepSeek 和 Mistral 等 LLM 的评估揭示了未被发现的语义后门，首次证明了这些隐藏漏洞的存在，强调了对部署模型进行概念审计的迫切需求。我们的代码和数据已开源，地址为 https://github.com/NayMyatMin/RAVEN。

> Large language models (LLMs) demonstrate remarkable performance across myriad language tasks, yet they remain vulnerable to backdoor attacks, where adversaries implant hidden triggers that systematically manipulate model outputs. Traditional defenses focus on explicit token-level anomalies and therefore overlook semantic backdoors-covert triggers embedded at the conceptual level (e.g., ideological stances or cultural references) that rely on meaning-based cues rather than lexical oddities. We first show, in a controlled finetuning setting, that such semantic backdoors can be implanted with only a small poisoned corpus, establishing their practical feasibility. We then formalize the notion of semantic backdoors in LLMs and introduce a black-box detection framework, RAVEN (short for "Response Anomaly Vigilance for uncovering semantic backdoors"), which combines semantic entropy with cross-model consistency analysis. The framework probes multiple models with structured topic-perspective prompts, clusters the sampled responses via bidirectional entailment, and flags anomalously uniform outputs; cross-model comparison isolates model-specific anomalies from corpus-wide biases. Empirical evaluations across diverse LLM families (GPT-4o, Llama, DeepSeek, Mistral) uncover previously undetected semantic backdoors, providing the first proof-of-concept evidence of these hidden vulnerabilities and underscoring the urgent need for concept-level auditing of deployed language models. We open-source our code and data at https://github.com/NayMyatMin/RAVEN.

[Arxiv](https://arxiv.org/abs/2504.12344)