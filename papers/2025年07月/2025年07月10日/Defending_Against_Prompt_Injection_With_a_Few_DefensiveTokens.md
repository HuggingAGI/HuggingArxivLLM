# Defending Against Prompt Injection With a Few DefensiveTokens
使用几个防御令牌对抗提示注入攻击

发布时间：2025年07月10日

`LLM应用

理由：这篇论文主要讨论了如何保护大型语言模型免受提示注入攻击，提出了一个名为 DefensiveToken 的防御机制。它属于 LLM 的实际应用，特别是安全防护方面的应用，因此归类为LLM应用。` `人工智能`

> Defending Against Prompt Injection With a Few DefensiveTokens

# 摘要

> # DefensiveToken: 保护大语言模型免受提示注入攻击的灵活防御机制

当大型语言模型 (LLM) 与外部数据交互执行复杂任务时，一种名为“提示注入攻击”的新型威胁应运而生。攻击者通过在系统访问的数据中注入恶意指令，能够随意替换用户的真实任务指令，造成严重安全风险。

为应对这一威胁，研究者提出了多种测试时防御方案（如防御性提示），允许开发者在需要时灵活启用安全防护。然而，这些方案的效果远逊于通过修改模型参数实现的训练时防御。针对这一痛点，我们提出了一种名为 DefensiveToken 的创新性测试时防御机制，其防御效果可与训练时方案相媲美。

DefensiveToken 是一种特殊的新增标记，其嵌入参数经过专门优化以提升安全性。在需要高度安全防护的场景中，开发者只需在 LLM 输入前添加少量 DefensiveToken，即可在几乎不影响模型性能的前提下实现强大的防护能力。而在安全需求较低的场景中，开发者可完全省略 DefensiveToken，此时 LLM 将保持原汁原味的高性能表现，生成高质量输出。

这一突破性方案的意义在于，它为 LLM 开发者提供了一个灵活的选择：通过简单的配置，即可在测试时自由切换，实现状态-of-the-art (SOTA) 的实用性和几乎 SOTA 的安全性之间的完美平衡。我们的代码已开源，地址为 https://github.com/Sizhe-Chen/DefensiveToken。


> When large language model (LLM) systems interact with external data to perform complex tasks, a new attack, namely prompt injection, becomes a significant threat. By injecting instructions into the data accessed by the system, the attacker is able to override the initial user task with an arbitrary task directed by the attacker. To secure the system, test-time defenses, e.g., defensive prompting, have been proposed for system developers to attain security only when needed in a flexible manner. However, they are much less effective than training-time defenses that change the model parameters. Motivated by this, we propose DefensiveToken, a test-time defense with prompt injection robustness comparable to training-time alternatives. DefensiveTokens are newly inserted as special tokens, whose embeddings are optimized for security. In security-sensitive cases, system developers can append a few DefensiveTokens before the LLM input to achieve security with a minimal utility drop. In scenarios where security is less of a concern, developers can simply skip DefensiveTokens; the LLM system remains the same as there is no defense, generating high-quality responses. Thus, DefensiveTokens, if released alongside the model, allow a flexible switch between the state-of-the-art (SOTA) utility and almost-SOTA security at test time. The code is available at https://github.com/Sizhe-Chen/DefensiveToken.

[Arxiv](https://arxiv.org/abs/2507.07974)