# TokenSkip：可控思维链压缩技术

发布时间：2025年02月17日

`LLM应用` `人工智能`

> TokenSkip: Controllable Chain-of-Thought Compression in LLMs

# 摘要

> 思维链 (CoT) 在提升大型语言模型 (LLMs) 推理能力方面表现出色。近期 OpenAI 的 o1 和 DeepSeek-R1 等进展表明，增加 CoT 序列长度可进一步提升推理性能。然而，由于 LLM 解码的自回归特性，更长的 CoT 输出会导致推理延迟增加，尤其当 CoT 超过 10,000 tokens 时，严重影响用户体验。为解决这一问题，我们研究了 CoT 输出中 tokens 的语义重要性，发现其对推理的贡献存在差异。基于此，我们提出了 TokenSkip，一种简单有效的方法，使 LLM 能够选择性跳过不重要的 tokens，实现可控的 CoT 压缩。实验结果表明，TokenSkip 在减少 CoT token 使用的同时，仍能保持强大的推理性能。特别地，应用于 Qwen2.5-14B-Instruct 时，TokenSkip 在 GSM8K 上将推理 tokens 减少 40%（从 313 个减少到 181 个），性能下降不到 0.4%。

> Chain-of-Thought (CoT) has been proven effective in enhancing the reasoning capabilities of large language models (LLMs). Recent advancements, such as OpenAI's o1 and DeepSeek-R1, suggest that scaling up the length of CoT sequences during inference could further boost LLM reasoning performance. However, due to the autoregressive nature of LLM decoding, longer CoT outputs lead to a linear increase in inference latency, adversely affecting user experience, particularly when the CoT exceeds 10,000 tokens. To address this limitation, we analyze the semantic importance of tokens within CoT outputs and reveal that their contributions to reasoning vary. Building on this insight, we propose TokenSkip, a simple yet effective approach that enables LLMs to selectively skip less important tokens, allowing for controllable CoT compression. Extensive experiments across various models and tasks demonstrate the effectiveness of TokenSkip in reducing CoT token usage while preserving strong reasoning performance. Notably, when applied to Qwen2.5-14B-Instruct, TokenSkip reduces reasoning tokens by 40% (from 313 to 181) on GSM8K, with less than a 0.4% performance drop.

[Arxiv](https://arxiv.org/abs/2502.12067)