# # 拒绝方向在安全对齐语言中普遍存在

发布时间：2025年05月22日

`LLM理论`

> Refusal Direction is Universal Across Safety-Aligned Languages

# 摘要

> 大型语言模型 (LLMs) 中的拒绝机制对于确保安全性至关重要。近期研究表明，拒绝行为可通过激活空间中的单一方向调节，从而实现针对性干预以绕过拒绝。尽管这一发现主要在英语环境中展示，但所有语言都需要适当的拒绝行为，然而目前对此理解有限。本文通过 PolyRefuse（一个通过将恶意和良性英文提示翻译成其他语言创建的多语言安全数据集），研究了 LLMs 在 14 种语言中的拒绝行为。我们发现了一个令人惊讶的跨语言通用拒绝方向：从英语中提取的向量可以几乎完美地绕过其他语言的拒绝，无需任何额外微调。更令人remarkable的是，从任何安全对齐语言中推导出的拒绝方向都可以无缝转移到其他语言。我们将这种可转移性归因于拒绝向量在嵌入空间中的跨语言平行性，并揭示了跨语言越狱背后的潜在机制。这些发现为构建更强大的多语言安全防御提供了可操作的见解，并为理解 LLMs 中的跨语言漏洞提供了更深入的机制理解。


> Refusal mechanisms in large language models (LLMs) are essential for ensuring safety. Recent research has revealed that refusal behavior can be mediated by a single direction in activation space, enabling targeted interventions to bypass refusals. While this is primarily demonstrated in an English-centric context, appropriate refusal behavior is important for any language, but poorly understood. In this paper, we investigate the refusal behavior in LLMs across 14 languages using PolyRefuse, a multilingual safety dataset created by translating malicious and benign English prompts into these languages. We uncover the surprising cross-lingual universality of the refusal direction: a vector extracted from English can bypass refusals in other languages with near-perfect effectiveness, without any additional fine-tuning. Even more remarkably, refusal directions derived from any safety-aligned language transfer seamlessly to others. We attribute this transferability to the parallelism of refusal vectors across languages in the embedding space and identify the underlying mechanism behind cross-lingual jailbreaks. These findings provide actionable insights for building more robust multilingual safety defenses and pave the way for a deeper mechanistic understanding of cross-lingual vulnerabilities in LLMs.

[Arxiv](https://arxiv.org/abs/2505.17306)