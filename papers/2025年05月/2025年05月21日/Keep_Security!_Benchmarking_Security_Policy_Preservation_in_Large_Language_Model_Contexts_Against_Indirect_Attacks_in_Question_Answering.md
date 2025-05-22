# # 保持安全！针对大型语言模型的问答场景中的间接攻击，开展安全策略保存基准测试研究

发布时间：2025年05月21日

`LLM应用

理由：这篇论文专注于评估大型语言模型（LLMs）在实际应用中的安全性，特别是在对抗攻击背景下的上下文安全保护。它通过引入基准数据集CoPriva，分析了LLMs在处理敏感信息时的表现，属于对LLM应用的研究。` `社会治理`

> Keep Security! Benchmarking Security Policy Preservation in Large Language Model Contexts Against Indirect Attacks in Question Answering

# 摘要

> 随着大型语言模型 (LLMs) 在企业、政府等敏感领域的广泛应用，确保其在上下文中严格遵守用户定义的安全策略变得至关重要，尤其是防止敏感信息泄露。尽管此前的研究主要关注于 LLM 的通用安全性和社会敏感数据处理，但在对抗攻击背景下，针对上下文安全保护的大规模基准测试仍存在空白。为此，我们推出了全新的大规模基准数据集 CoPriva，专注于评估 LLM 在问答任务中对上下文非披露策略的遵循情况。我们的数据集源于现实场景，包含明确的安全策略和精心设计的查询，这些查询既包括直接攻击，也包含更具挑战性的间接攻击，旨在试探模型对被禁止信息的泄露。通过对 10 个 LLM 的评估，我们发现了一个严重的问题：许多模型在面对这些攻击时，会违反用户定义的策略并泄露敏感信息。这种漏洞在间接攻击中表现得尤为突出，凸显了现有 LLM 在安全对齐方面存在的关键缺陷，尤其是在处理敏感应用时。我们的研究进一步揭示，尽管这些模型通常能够准确识别出问题的正确答案，但在生成过程中却难以有效整合安全策略约束。不过，当被明确提示时，它们能够对输出进行一定程度的修订。这些发现凸显了开发更强大方法以确保上下文安全的紧迫性。

> As Large Language Models (LLMs) are increasingly deployed in sensitive domains such as enterprise and government, ensuring that they adhere to user-defined security policies within context is critical-especially with respect to information non-disclosure. While prior LLM studies have focused on general safety and socially sensitive data, large-scale benchmarks for contextual security preservation against attacks remain lacking. To address this, we introduce a novel large-scale benchmark dataset, CoPriva, evaluating LLM adherence to contextual non-disclosure policies in question answering. Derived from realistic contexts, our dataset includes explicit policies and queries designed as direct and challenging indirect attacks seeking prohibited information. We evaluate 10 LLMs on our benchmark and reveal a significant vulnerability: many models violate user-defined policies and leak sensitive information. This failure is particularly severe against indirect attacks, highlighting a critical gap in current LLM safety alignment for sensitive applications. Our analysis reveals that while models can often identify the correct answer to a query, they struggle to incorporate policy constraints during generation. In contrast, they exhibit a partial ability to revise outputs when explicitly prompted. Our findings underscore the urgent need for more robust methods to guarantee contextual security.

[Arxiv](https://arxiv.org/abs/2505.15805)