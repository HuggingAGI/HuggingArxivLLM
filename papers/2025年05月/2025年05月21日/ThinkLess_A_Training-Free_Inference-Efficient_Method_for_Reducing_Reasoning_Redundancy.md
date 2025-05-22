# ThinkLess——一种无需训练且推理效率高的方法，旨在减少推理冗余

发布时间：2025年05月21日

`LLM应用` `人工智能`

> ThinkLess: A Training-Free Inference-Efficient Method for Reducing Reasoning Redundancy

# 摘要

> 尽管Chain-of-Thought (CoT) 提示法能够提升大型语言模型 (LLMs) 的推理能力，但冗长的推理标记显著增加了延迟和KV缓存内存的使用，甚至可能在上下文限制下截断最终答案。为此，我们提出了ThinkLess——一个无需修改模型的推理高效框架，能够在提前终止推理生成的同时维持输出质量。通过注意力分析发现，答案标记对早期推理步骤的关注度极低，主要关注于推理终止符标记，这是由于因果掩蔽下的信息迁移所致。基于这一发现，ThinkLess在早期位置插入终止符标记，跳过冗余推理同时保留底层知识传递。为了避免早期终止导致的格式破坏，ThinkLess采用了轻量级的后调节机制，依赖模型自然的指令遵循能力生成结构良好的答案。无需微调或辅助数据，ThinkLess在实现与完整长度CoT解码相当的准确性的同时，大幅降低了解码时间和内存消耗。

> While Chain-of-Thought (CoT) prompting improves reasoning in large language models (LLMs), the excessive length of reasoning tokens increases latency and KV cache memory usage, and may even truncate final answers under context limits. We propose ThinkLess, an inference-efficient framework that terminates reasoning generation early and maintains output quality without modifying the model. Atttention analysis reveals that answer tokens focus minimally on earlier reasoning steps and primarily attend to the reasoning terminator token, due to information migration under causal masking. Building on this insight, ThinkLess inserts the terminator token at earlier positions to skip redundant reasoning while preserving the underlying knowledge transfer. To prevent format discruption casued by early termination, ThinkLess employs a lightweight post-regulation mechanism, relying on the model's natural instruction-following ability to produce well-structured answers. Without fine-tuning or auxiliary data, ThinkLess achieves comparable accuracy to full-length CoT decoding while greatly reducing decoding time and memory consumption.

[Arxiv](https://arxiv.org/abs/2505.15684)