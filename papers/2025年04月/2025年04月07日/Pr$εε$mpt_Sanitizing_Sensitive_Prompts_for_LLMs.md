# # Pr$εε$mpt：为大型语言模型清理敏感提示词的方法

发布时间：2025年04月07日

`LLM应用` `信息处理`

> Pr$εε$mpt: Sanitizing Sensitive Prompts for LLMs

# 摘要

> 大型语言模型 (LLMs) 的兴起带来了新的隐私挑战，尤其是在推理过程中，提示中的敏感信息可能暴露于专有 LLM API。本文旨在解决在保护提示中敏感信息的同时保持响应质量的问题。为此，我们提出了以下解决方案：

首先，我们引入了一种受加密启发的“提示净化器”概念，用于将输入提示转换为保护其敏感令牌。其次，我们提出了 Pr$εε$mpt，这是一个实现提示净化器的新型系统。Pr$εε$mpt 将敏感令牌分为两类：(1) LLM 响应仅依赖于格式的令牌（如 SSN、信用卡号），我们采用格式保留加密 (FPE)；(2) 响应依赖于具体值的令牌（如年龄、薪水），我们应用度量差分隐私 (mDP)。

我们的评估表明，Pr$εε$mpt 是一种实用的方法，能够在保持高实用性的同时实现有意义的隐私保证，并优于先前的方法。

> The rise of large language models (LLMs) has introduced new privacy challenges, particularly during inference where sensitive information in prompts may be exposed to proprietary LLM APIs. In this paper, we address the problem of formally protecting the sensitive information contained in a prompt while maintaining response quality. To this end, first, we introduce a cryptographically inspired notion of a prompt sanitizer which transforms an input prompt to protect its sensitive tokens. Second, we propose Pr$εε$mpt, a novel system that implements a prompt sanitizer. Pr$εε$mpt categorizes sensitive tokens into two types: (1) those where the LLM's response depends solely on the format (such as SSNs, credit card numbers), for which we use format-preserving encryption (FPE); and (2) those where the response depends on specific values, (such as age, salary) for which we apply metric differential privacy (mDP). Our evaluation demonstrates that Pr$εε$mpt is a practical method to achieve meaningful privacy guarantees, while maintaining high utility compared to unsanitized prompts, and outperforming prior methods

[Arxiv](https://arxiv.org/abs/2504.05147)