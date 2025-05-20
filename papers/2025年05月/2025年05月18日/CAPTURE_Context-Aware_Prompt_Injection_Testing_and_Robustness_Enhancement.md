# CAPTURE: 上下文感知提示注入测试与鲁棒性增强

发布时间：2025年05月18日

`LLM应用` `网络安全` `信息安全`

> CAPTURE: Context-Aware Prompt Injection Testing and Robustness Enhancement

# 摘要

> 提示注入攻击仍然是大型语言模型的重大安全隐患。然而，现有的防护模型在上下文感知环境下的有效性仍未得到充分研究，因为它们往往依赖静态攻击基准。此外，这些模型还存在过度防御的倾向。我们引入了CAPTURE，这是一个全新的上下文感知基准，能够以最少的领域内示例评估攻击检测和过度防御倾向。我们的实验表明，当前的提示注入防护模型在对抗性案例中存在大量漏报，在良性场景中则出现过多误报，凸显了其关键局限性。

> Prompt injection remains a major security risk for large language models. However, the efficacy of existing guardrail models in context-aware settings remains underexplored, as they often rely on static attack benchmarks. Additionally, they have over-defense tendencies. We introduce CAPTURE, a novel context-aware benchmark assessing both attack detection and over-defense tendencies with minimal in-domain examples. Our experiments reveal that current prompt injection guardrail models suffer from high false negatives in adversarial cases and excessive false positives in benign scenarios, highlighting critical limitations.

[Arxiv](https://arxiv.org/abs/2505.12368)