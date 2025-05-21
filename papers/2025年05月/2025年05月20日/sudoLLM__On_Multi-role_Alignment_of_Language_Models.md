# # sudoLLM：语言模型的多角色对齐研究

发布时间：2025年05月20日

`LLM应用` `信息安全` `人工智能`

> sudoLLM : On Multi-role Alignment of Language Models

# 摘要

> 基于用户授权的访问权限是许多安全关键系统的重要功能，但在大型语言模型 (LLM) 领域尚未实现。本研究从访问控制系统中汲取灵感，提出了 sudoLLM 框架，能够生成多角色对齐的 LLM，即 LLM 能够根据用户访问权限进行行为。sudoLLM 在查询中注入基于用户的微妙偏见，并训练 LLM 利用这一偏见信号，仅在用户授权时生成敏感信息。实证结果表明，该方法在对齐性、泛化能力和抵御基于提示的越狱攻击方面均有显著提升。语言建模目标与安全对齐之间的持久紧张关系，通常被用于越狱 LLM，借助注入的偏见信号得到了一定程度的缓解。我们的框架作为额外的安全层，与现有护栏机制相辅相成，从而增强与 LLM 的端到端安全性。

> User authorization-based access privileges are a key feature in many safety-critical systems, but have thus far been absent from the large language model (LLM) realm. In this work, drawing inspiration from such access control systems, we introduce sudoLLM, a novel framework that results in multi-role aligned LLMs, i.e., LLMs that account for, and behave in accordance with, user access rights. sudoLLM injects subtle user-based biases into queries and trains an LLM to utilize this bias signal in order to produce sensitive information if and only if the user is authorized. We present empirical results demonstrating that this approach shows substantially improved alignment, generalization, and resistance to prompt-based jailbreaking attacks. The persistent tension between the language modeling objective and safety alignment, which is often exploited to jailbreak LLMs, is somewhat resolved with the aid of the injected bias signal. Our framework is meant as an additional security layer, and complements existing guardrail mechanisms for enhanced end-to-end safety with LLMs.

[Arxiv](https://arxiv.org/abs/2505.14607)