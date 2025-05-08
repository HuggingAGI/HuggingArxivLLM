# # **AutoPatch：修复真实世界CVE漏洞的多智能体框架**

发布时间：2025年05月07日

`LLM应用` `软件开发` `代码安全`

> AutoPatch: Multi-Agent Framework for Patching Real-World CVE Vulnerabilities

# 摘要

> 大型语言模型（LLMs）在软件开发中展现出巨大潜力，能够实现代码的自动生成与分析。然而，这些模型的知识仅限于固定的时间点，导致生成的代码容易受到新披露的 CVE 漏洞的影响。现有方法要么需要频繁微调，成本高昂，要么专注于过于简化的 CWE 示例，并且需要明确提供漏洞位置，这限制了它们修复复杂真实漏洞的能力。

为了解决这些问题，我们提出了 AutoPatch，这是一个旨在修复 LLM 生成代码中的漏洞的多智能体框架，特别针对那些在 LLM 知识截止日期后出现的漏洞。AutoPatch 将检索增强生成（RAG）与一个包含最近披露漏洞的结构化数据库相结合，该数据库包含从 Linux 内核和 Chrome 等真实系统中提取的 75 个高危 CVE 的 525 个代码片段。

AutoPatch 结合语义分析和污点分析来识别最相关的 CVE，并利用增强的链式推理（CoT）来构建用于验证和修复的丰富提示。我们的统一相似性模型在选择最相关漏洞时达到了 90.4% 的准确率。AutoPatch 在漏洞验证方面达到了 89.5% 的 F1 分数，并在修复方面达到了 95.0% 的准确率，同时比传统的微调方法成本效益提高了 50 多倍。

> Large Language Models (LLMs) have emerged as promising tools in software development, enabling automated code generation and analysis. However, their knowledge is limited to a fixed cutoff date, making them prone to generating code vulnerable to newly disclosed CVEs. Frequent fine-tuning with new CVE sets is costly, and existing LLM-based approaches focus on oversimplified CWE examples and require providing explicit bug locations to LLMs, limiting their ability to patch complex real-world vulnerabilities. To address these limitations, we propose AutoPatch, a multi-agent framework designed to patch vulnerable LLM-generated code, particularly those introduced after the LLMs' knowledge cutoff. AutoPatch integrates Retrieval-Augmented Generation (RAG) with a structured database of recently disclosed vulnerabilities, comprising 525 code snippets derived from 75 high-severity CVEs across real-world systems such as the Linux kernel and Chrome. AutoPatch combines semantic and taint analysis to identify the most relevant CVE and leverages enhanced Chain-of-Thought (CoT) reasoning to construct enriched prompts for verification and patching. Our unified similarity model, which selects the most relevant vulnerabilities, achieves 90.4 percent accuracy in CVE matching. AutoPatch attains 89.5 percent F1-score for vulnerability verification and 95.0 percent accuracy in patching, while being over 50x more cost-efficient than traditional fine-tuning approaches.

[Arxiv](https://arxiv.org/abs/2505.04195)