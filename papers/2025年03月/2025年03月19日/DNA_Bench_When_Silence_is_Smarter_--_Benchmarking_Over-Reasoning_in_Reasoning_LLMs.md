# DNA Bench: 静默有时更明智 -- 评估推理型LLM的过度推理现象

发布时间：2025年03月19日

`LLM应用` `人工智能`

> DNA Bench: When Silence is Smarter -- Benchmarking Over-Reasoning in Reasoning LLMs

# 摘要

> 测试时间缩放显著提升了大语言模型的性能，使其能够进行更深入的推理以解决复杂问题。然而，这种增强的推理能力也导致了过度生成的标记和不必要的问题解决尝试。我们引入了不应答基准测试（Dont Answer Bench，DNA Bench），这是一个旨在评估大语言模型对复杂推理触发器的稳健理解能力以及避免不必要的生成的新型基准测试。DNA Bench 包含了 150 个经过精心设计的对抗性提示，这些提示对于人类来说易于理解和回应，但令人惊讶的是，许多近期知名的 LLMs 却难以应对。DNA Bench 考察了模型在不同能力方面的表现，包括指令遵循、幻觉避免、冗余过滤以及无法回答问题的识别。我们对推理大语言模型（RLMs），如 DeepSeek-R1、OpenAI O3-mini 和 Claude-3.7-sonnet 进行了评估，并将其与强大的非推理模型（例如 GPT-4o）进行了对比。实验结果表明，RLMs 生成的标记数量比实际需要多出 70 倍，常常在那些简单非推理模型能够高效准确完成的任务上表现不佳。我们的研究发现凸显了在 RLMs 中开发更有效的训练和推理策略的必要性。

> Test-time scaling has significantly improved large language model performance, enabling deeper reasoning to solve complex problems. However, this increased reasoning capability also leads to excessive token generation and unnecessary problem-solving attempts. We introduce Dont Answer Bench (DNA Bench), a new benchmark designed to evaluate LLMs ability to robustly understand the tricky reasoning triggers and avoiding unnecessary generation. DNA Bench consists of 150 adversarially designed prompts that are easy for humans to understand and respond to, but surprisingly not for many of the recent prominent LLMs. DNA Bench tests models abilities across different capabilities, such as instruction adherence, hallucination avoidance, redundancy filtering, and unanswerable question recognition. We evaluate reasoning LLMs (RLMs), including DeepSeek-R1, OpenAI O3-mini, Claude-3.7-sonnet and compare them against a powerful non-reasoning model, e.g., GPT-4o. Our experiments reveal that RLMs generate up to 70x more tokens than necessary, often failing at tasks that simpler non-reasoning models handle efficiently with higher accuracy. Our findings underscore the need for more effective training and inference strategies in RLMs.

[Arxiv](https://arxiv.org/abs/2503.15793)