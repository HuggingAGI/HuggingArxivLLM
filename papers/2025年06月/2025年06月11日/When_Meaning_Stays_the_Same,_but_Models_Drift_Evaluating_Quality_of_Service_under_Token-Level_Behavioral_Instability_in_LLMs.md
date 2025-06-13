# 意义不变，模型漂移：LLMs Token级别行为不稳定性下的服务质量评估

发布时间：2025年06月11日

`LLM理论

摘要讨论了大型语言模型（LLM）在处理提示时的行为，特别是当提示在token级别变化时，尽管语义相同，模型的反应却可能不同。研究的重点在于理解模型内部的工作机制，如token化和解码过程，以及这些过程如何影响模型的输出稳定性。这属于LLM理论，因为它深入探讨了模型的内在特性、行为和潜在的问题。` `语言模型`

> When Meaning Stays the Same, but Models Drift: Evaluating Quality of Service under Token-Level Behavioral Instability in LLMs

# 摘要

> 我们研究了大型语言模型如何应对仅在 token 级别实现不同但保持相同语义意图的提示，这一现象我们称之为 prompt 变体。为此，我们提出了基于提示的语义偏移（Prompt-Based Semantic Shift，PBSS），一个用于在语义等价的提示改写下测量 LLM 行为漂移的诊断框架。通过对十个受限任务的应用，PBSS 揭示了持续且与模型相关的响应偏移，表明与 token 化和解码相关的统计规律。这些结果不仅突显了在改写下模型评估稳定性的被忽视维度，还表明 token 化策略和解码动态可能与训练后服务质量的不稳定性有关。

> We investigate how large language models respond to prompts that differ only in their token-level realization but preserve the same semantic intent, a phenomenon we call prompt variance. We propose Prompt-Based Semantic Shift (PBSS), a diagnostic framework for measuring behavioral drift in LLMs under semantically equivalent prompt rewordings. Applied to ten constrained tasks, PBSS reveals consistent, model-specific response shifts, suggesting statistical regularities linked to tokenization and decoding. These results highlight an overlooked dimension of model evaluation stability under rephrasing and suggest that tokenization strategies and decoding dynamics may contribute to post-training quality of service instability.

[Arxiv](https://arxiv.org/abs/2506.10095)