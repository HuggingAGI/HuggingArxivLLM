# <翻译失败>

发布时间：2025年08月29日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> Instruction-Level Weight Shaping: A Framework for Self-Improving AI Agents

# 摘要

> <翻译失败>

> Large language models (LLMs) are fluent but largely static after pre-training; new or shifting knowledge is typically added with retrieval-augmented generation (RAG) or fine-tuning. RAG raises latency and engineering overhead and often fails to integrate facts; prompt engineering is brittle and can conflict with prior knowledge; fine-tuning is costly and risks catastrophic forgetting. We propose Instruction-Level Weight Shaping (ILWS): curated system instructions act as external, auditable pseudo-parameters updated after each session via reflection and user feedback. A Reflection Engine inspects conversation traces, diagnoses reasoning successes and failures, and proposes typed deltas $ΔK=(ΔS,ΔU,ΔT)$ over instructions, user preferences, and tools. Deltas are version-controlled, evaluated with a sliding window of 1-5 star ratings, auto-repaired on first failure, and rolled back on repeated failure. When an edit budget crosses a threshold, the agent compiles a rating-weighted synthetic set and distills matured instruction-space gains into parameters, converting prompt-space improvements into weight-space without downtime. ILWS makes explicit the low-rank shaping induced by context in transformer blocks, preserves governance, and removes per-call retrieval. In enterprise support it increased throughput 2.4-5.0x and cut audited hallucinations by about 80% versus a frozen baseline. In an Adobe Commerce Cloud proof of concept "L0 Support", it achieved 4-5x more tickets per hour and about 80% lower time per ticket, with autonomous instruction updates and optional tool synthesis. Because ILWS operates at the instruction layer until controlled distillation, it generalizes to dynamic domains (legal, medical, engineering) requiring adaptive reasoning, tool creation, and low-latency deployment.

[Arxiv](https://arxiv.org/abs/2509.00251)