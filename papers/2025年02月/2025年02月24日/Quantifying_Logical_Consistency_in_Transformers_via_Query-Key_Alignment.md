# 通过查询键对齐量化Transformer模型中的逻辑一致性

发布时间：2025年02月24日

`LLM理论` `人工智能`

> Quantifying Logical Consistency in Transformers via Query-Key Alignment

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域展现了卓越的能力，但多步逻辑推理仍是其待突破的难题。虽然链式思维提示（Chain-of-Thought prompting）通过生成中间推理步骤提升了模型的逻辑推理能力，但如何评估这些逻辑转换的连贯性仍是一个挑战。本文提出了一种新颖且轻量级的逻辑推理评估策略，该策略巧妙地利用了Transformer注意力机制中的查询-键对齐（query-key alignments）。通过一次前向计算，从精心选择的注意力头中提取“QK分数”，我们的方法能够可靠地区分有效推理与无效推理，为传统基于消融的评估技术提供了一种更高效的替代方案。我们在多个逻辑推理基准测试中进行了实证验证，结果表明我们的评估方法在面对干扰项时具有更强的鲁棒性，并且能够提升推理深度。实验涵盖了参数规模从15亿到700亿的多种模型，进一步验证了方法的通用性和有效性。

> Large language models (LLMs) have demonstrated impressive performance in various natural language processing tasks, yet their ability to perform multi-step logical reasoning remains an open challenge. Although Chain-of-Thought prompting has improved logical reasoning by enabling models to generate intermediate steps, it lacks mechanisms to assess the coherence of these logical transitions. In this paper, we propose a novel, lightweight evaluation strategy for logical reasoning that uses query-key alignments inside transformer attention heads. By computing a single forward pass and extracting a "QK-score" from carefully chosen heads, our method reveals latent representations that reliably separate valid from invalid inferences, offering a scalable alternative to traditional ablation-based techniques. We also provide an empirical validation on multiple logical reasoning benchmarks, demonstrating improved robustness of our evaluation method against distractors and increased reasoning depth. The experiments were conducted on a diverse set of models, ranging from 1.5B to 70B parameters.

[Arxiv](https://arxiv.org/abs/2502.17017)