# LLMs 为何及如何产生幻觉：基于后续关联的串联机制

发布时间：2025年04月17日

`LLM理论` `模型分析`

> Why and How LLMs Hallucinate: Connecting the Dots with Subsequence Associations

# 摘要

> 大型语言模型 (LLMs) 常常生成幻觉内容——与事实准确性或所提供上下文不符的内容——由于潜在原因的复杂相互作用，诊断这些幻觉具有挑战性。本文引入了一种子序列关联框架，以系统地追踪和理解幻觉现象。我们的关键见解在于，当主导的幻觉关联超过忠实的关联时，幻觉就会产生。通过理论和实证分析，我们证明了解码器-only 的 transformers 有效地作为子序列嵌入模型运作，其中线性层编码输入输出关联。我们提出了一种追踪算法，通过分析随机输入上下文中的幻觉概率来识别因果子序列。实验表明，我们的方法在识别幻觉原因方面优于标准归因技术，并与模型训练语料库的证据相一致。这项工作为幻觉现象提供了统一的视角，并为追踪和分析幻觉提供了一个稳健的框架。

> Large language models (LLMs) frequently generate hallucinations-content that deviates from factual accuracy or provided context-posing challenges for diagnosis due to the complex interplay of underlying causes. This paper introduces a subsequence association framework to systematically trace and understand hallucinations. Our key insight is that hallucinations arise when dominant hallucinatory associations outweigh faithful ones. Through theoretical and empirical analyses, we demonstrate that decoder-only transformers effectively function as subsequence embedding models, with linear layers encoding input-output associations. We propose a tracing algorithm that identifies causal subsequences by analyzing hallucination probabilities across randomized input contexts. Experiments show our method outperforms standard attribution techniques in identifying hallucination causes and aligns with evidence from the model's training corpus. This work provides a unified perspective on hallucinations and a robust framework for their tracing and analysis.

[Arxiv](https://arxiv.org/abs/2504.12691)