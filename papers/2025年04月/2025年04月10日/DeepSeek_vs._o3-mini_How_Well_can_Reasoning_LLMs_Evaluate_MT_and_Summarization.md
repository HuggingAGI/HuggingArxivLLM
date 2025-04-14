# DeepSeek 与 o3-mini：推理型大语言模型在机器翻译和总结任务中的评估能力如何？

发布时间：2025年04月10日

`LLM应用`

> DeepSeek vs. o3-mini: How Well can Reasoning LLMs Evaluate MT and Summarization?

# 摘要

> 推理增强的大型语言模型（LLMs）在复杂逻辑和数学任务中表现卓越，但其在自然语言生成评估中的潜力尚未被充分挖掘。本研究对比了DeepSeek-R1和OpenAI o3等推理型LLMs与其基础版本在机器翻译（MT）和文本摘要（TS）任务中的表现。我们评估了涵盖先进推理模型、蒸馏版本（80亿至700亿参数）和常规LLMs的八种模型。实验结果显示，推理优势因模型和任务而异：OpenAI o3-mini系列模型随推理强度增加性能提升显著，但DeepSeek-R1的表现仅在TS评估的部分方面优于其基础版本。分析表明，推理过程中的token使用量增加与o3-mini模型的评估质量正相关。此外，推理能力的蒸馏在中型模型（320亿参数）中表现尚可，但在小型模型（80亿参数）中大幅下降。本研究首次全面评估了推理型LLMs在NLG评估中的应用，为实际应用提供了重要参考。

> Reasoning-enabled large language models (LLMs) have recently demonstrated impressive performance in complex logical and mathematical tasks, yet their effectiveness in evaluating natural language generation remains unexplored. This study systematically compares reasoning-based LLMs (DeepSeek-R1 and OpenAI o3) with their non-reasoning counterparts across machine translation (MT) and text summarization (TS) evaluation tasks. We evaluate eight models across three architectural categories, including state-of-the-art reasoning models, their distilled variants (ranging from 8B to 70B parameters), and equivalent conventional, non-reasoning LLMs. Our experiments on WMT23 and SummEval benchmarks reveal that the benefits of reasoning capabilities are highly model and task-dependent: while OpenAI o3-mini models show consistent performance improvements with increased reasoning intensity, DeepSeek-R1 underperforms compared to its non-reasoning variant, with exception to certain aspects of TS evaluation. Correlation analysis demonstrates that increased reasoning token usage positively correlates with evaluation quality in o3-mini models. Furthermore, our results show that distillation of reasoning capabilities maintains reasonable performance in medium-sized models (32B) but degrades substantially in smaller variants (8B). This work provides the first comprehensive assessment of reasoning LLMs for NLG evaluation and offers insights into their practical use.

[Arxiv](https://arxiv.org/abs/2504.08120)