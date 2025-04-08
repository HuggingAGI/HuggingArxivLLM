# 大型语言模型的多语言多轮自动红队测试

发布时间：2025年04月04日

`LLM应用` `人工智能安全` `模型安全`

> Multi-lingual Multi-turn Automated Red Teaming for LLMs

# 摘要

> 大型语言模型（LLMs）近年来取得了显著进步，其应用范围和能力也在不断扩大。为了确保模型在实际应用中的安全性，研究者们致力于``模型对齐''，即防止LLMs生成不安全的响应。在评估模型安全风险时，	extit{红队测试}是一种常用方法，测试人员通过设计复杂的提示来触发模型生成不安全的响应，从而测试模型的对齐机制。然而，传统的人工红队测试成本高昂、耗时且难以覆盖所有最新功能（如多语言、多模态），而现有的自动化方法仅支持英语或单轮对话等有限场景。为此，我们提出了	extbf{多语言多轮自动化红队测试（MM-ART）}，一种能够完全自动化多语言对话式红队测试的方法，并快速识别导致不安全响应的提示。通过在不同语言上的实验，我们发现：经过5轮英文对话后，模型的脆弱性比初始轮次平均增加了71\%。而对于非英语对话，模型的安全漏洞比标准单轮英语方法多出195\%，这充分证明了开发与LLMs能力相匹配的自动化红队测试方法的必要性。

> Language Model Models (LLMs) have improved dramatically in the past few years, increasing their adoption and the scope of their capabilities over time. A significant amount of work is dedicated to ``model alignment'', i.e., preventing LLMs to generate unsafe responses when deployed into customer-facing applications. One popular method to evaluate safety risks is \textit{red-teaming}, where agents attempt to bypass alignment by crafting elaborate prompts that trigger unsafe responses from a model. Standard human-driven red-teaming is costly, time-consuming and rarely covers all the recent features (e.g., multi-lingual, multi-modal aspects), while proposed automation methods only cover a small subset of LLMs capabilities (i.e., English or single-turn). We present Multi-lingual Multi-turn Automated Red Teaming (\textbf{MM-ART}), a method to fully automate conversational, multi-lingual red-teaming operations and quickly identify prompts leading to unsafe responses. Through extensive experiments on different languages, we show the studied LLMs are on average 71\% more vulnerable after a 5-turn conversation in English than after the initial turn. For conversations in non-English languages, models display up to 195\% more safety vulnerabilities than the standard single-turn English approach, confirming the need for automated red-teaming methods matching LLMs capabilities.

[Arxiv](https://arxiv.org/abs/2504.03174)