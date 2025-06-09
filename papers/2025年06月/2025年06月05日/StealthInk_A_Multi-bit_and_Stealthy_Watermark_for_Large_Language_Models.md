# # 摘要  
StealthInk: 面向大型语言模型的多比特隐蔽水印方案

发布时间：2025年06月05日

`LLM应用` `AI生成内容` `数字版权管理`

> StealthInk: A Multi-bit and Stealthy Watermark for Large Language Models

# 摘要

> 大型语言模型（LLMs）的水印技术为识别AI生成文本提供了一种有效方法。然而，现有方法要么破坏LLMs生成文本的原始分布，要么仅限于嵌入零比特信息，只能检测水印而无法识别来源。我们提出了一种名为StealthInk的隐秘多比特水印方案，它在保留原始文本分布的同时，支持嵌入来源数据（如userID、TimeStamp和modelID）到LLM生成文本中。这使得快速追溯成为可能，而无需访问语言模型的API或提示。我们推导出在固定等错误率下检测水印所需令牌数量的下限，为提升水印容量提供了重要见解。通过在多种任务上的全面实证评估，StealthInk的隐秘性、可检测性和抗性得到了充分验证，确立了它作为LLM水印应用的有效解决方案。

> Watermarking for large language models (LLMs) offers a promising approach to identifying AI-generated text. Existing approaches, however, either compromise the distribution of original generated text by LLMs or are limited to embedding zero-bit information that only allows for watermark detection but ignores identification. We present StealthInk, a stealthy multi-bit watermarking scheme that preserves the original text distribution while enabling the embedding of provenance data, such as userID, TimeStamp, and modelID, within LLM-generated text. This enhances fast traceability without requiring access to the language model's API or prompts. We derive a lower bound on the number of tokens necessary for watermark detection at a fixed equal error rate, which provides insights on how to enhance the capacity. Comprehensive empirical evaluations across diverse tasks highlight the stealthiness, detectability, and resilience of StealthInk, establishing it as an effective solution for LLM watermarking applications.

[Arxiv](https://arxiv.org/abs/2506.05502)