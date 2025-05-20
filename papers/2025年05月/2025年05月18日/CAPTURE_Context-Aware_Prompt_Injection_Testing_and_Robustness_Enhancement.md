# CAPTURE：上下文感知的提示注入测试与鲁棒性增强

发布时间：2025年05月18日

`LLM应用`

> CAPTURE: Context-Aware Prompt Injection Testing and Robustness Enhancement

# 摘要

> 提示注入攻击仍是大型语言模型的重大安全威胁。现有防护模型在上下文感知环境下的有效性尚不明确，因其通常依赖静态攻击基准，且存在过度防御倾向。我们提出CAPTURE，这是一个新颖的上下文感知基准，仅需少量领域内示例即可评估攻击检测与过度防御倾向。实验表明，当前防护模型在对抗性案例中漏报严重，在良性场景中误报过多，凸显其关键局限性。

> Prompt injection remains a major security risk for large language models. However, the efficacy of existing guardrail models in context-aware settings remains underexplored, as they often rely on static attack benchmarks. Additionally, they have over-defense tendencies. We introduce CAPTURE, a novel context-aware benchmark assessing both attack detection and over-defense tendencies with minimal in-domain examples. Our experiments reveal that current prompt injection guardrail models suffer from high false negatives in adversarial cases and excessive false positives in benign scenarios, highlighting critical limitations.

[Arxiv](https://arxiv.org/abs/2505.12368)