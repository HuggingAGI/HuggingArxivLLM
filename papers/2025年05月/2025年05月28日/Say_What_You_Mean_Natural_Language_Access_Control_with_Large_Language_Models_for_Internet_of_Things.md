# 一语道破：基于大型语言模型的自然语言物联网访问控制方案

发布时间：2025年05月28日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLM）来改进物联网（IoT）中的访问控制机制。LACE 引擎通过自然语言处理和自动策略生成，展示了 LLM 在实际应用中的潜力，特别是在安全和灵活的访问控制方面。因此，它属于LLM应用类别。` `物联网` `智能家居`

> Say What You Mean: Natural Language Access Control with Large Language Models for Internet of Things

# 摘要

> 物联网 (IoT) 的访问控制日益复杂，需考虑时间、位置、用户行为及环境条件等因素。现有平台或控制粒度粗，或依赖 rigid 规则匹配，难以应对语义丰富或模糊的场景。此外，策略编写分散：专家用自然语言描述需求，开发人员手动转译为代码，导致语义差距和配置错误。本研究提出 LACE，基于语言的访问控制引擎，结合 LLM 弥合人类意图与机器逻辑。LACE 通过提示生成策略、增强推理和正式验证，支持表达性、可解释性及可验证的访问控制。用户可用自然语言指定策略，自动转为结构化规则，验证正确性，并通过混合 LLM-规则引擎决策。我们在智能家居环境中进行了广泛实验，LACE 在策略生成正确率 100%，DeepSeek-V3 达 88% 准确率和 0.79 F1 值，超越 GPT-3.5 和 Gemini。系统在策略数量和并发请求增加时表现优异。结果表明 LACE 在 IoT 平台中实现安全、灵活及用户友好的访问控制潜力巨大。

> Access control in the Internet of Things (IoT) is becoming increasingly complex, as policies must account for dynamic and contextual factors such as time, location, user behavior, and environmental conditions. However, existing platforms either offer only coarse-grained controls or rely on rigid rule matching, making them ill-suited for semantically rich or ambiguous access scenarios. Moreover, the policy authoring process remains fragmented: domain experts describe requirements in natural language, but developers must manually translate them into code, introducing semantic gaps and potential misconfiguration. In this work, we present LACE, the Language-based Access Control Engine, a hybrid framework that leverages large language models (LLMs) to bridge the gap between human intent and machine-enforceable logic. LACE combines prompt-guided policy generation, retrieval-augmented reasoning, and formal validation to support expressive, interpretable, and verifiable access control. It enables users to specify policies in natural language, automatically translates them into structured rules, validates semantic correctness, and makes access decisions using a hybrid LLM-rule-based engine. We evaluate LACE in smart home environments through extensive experiments. LACE achieves 100% correctness in verified policy generation and up to 88% decision accuracy with 0.79 F1-score using DeepSeek-V3, outperforming baselines such as GPT-3.5 and Gemini. The system also demonstrates strong scalability under increasing policy volume and request concurrency. Our results highlight LACE's potential to enable secure, flexible, and user-friendly access control across real-world IoT platforms.

[Arxiv](https://arxiv.org/abs/2505.23835)