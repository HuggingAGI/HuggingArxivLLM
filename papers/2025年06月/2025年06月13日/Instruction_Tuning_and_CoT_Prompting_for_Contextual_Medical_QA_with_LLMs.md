# 基于大型语言模型（LLMs）的情境化医疗问答任务中的指令微调与链式思考提示方法

发布时间：2025年06月13日

`LLM应用` `医学问答` `生物医学推理`

> Instruction Tuning and CoT Prompting for Contextual Medical QA with LLMs

# 摘要

> 大型语言模型（LLMs）在医学问答（MedQA）领域表现出了强大的能力，但要在生物医学推理中应用它们仍然面临挑战，主要是由于领域特定的复杂性和监督数据的有限性。本研究旨在探讨提示设计和轻量级微调对开源LLMs在PubMedQA基准测试中的性能有何影响，该基准用于评估多选生物医学问题。我们重点研究了两种常用的提示策略——标准指令提示和链式思维（CoT）提示，并采用QLoRA进行参数高效的指令微调。实验结果表明，在零样本设置下，仅使用CoT提示即可显著提升推理能力，而指令微调则能显著提高准确性。然而，基于CoT提示的微调并非对所有模型都适用，甚至可能对某些大型模型造成性能下降。这些发现表明，具有推理意识的提示是有用的，但其效果会因模型和规模而异。本研究为在医学问答应用中将提示工程与高效微调相结合提供了实用的见解。

> Large language models (LLMs) have shown great potential in medical question answering (MedQA), yet adapting them to biomedical reasoning remains challenging due to domain-specific complexity and limited supervision. In this work, we study how prompt design and lightweight fine-tuning affect the performance of open-source LLMs on PubMedQA, a benchmark for multiple-choice biomedical questions. We focus on two widely used prompting strategies - standard instruction prompts and Chain-of-Thought (CoT) prompts - and apply QLoRA for parameter-efficient instruction tuning. Across multiple model families and sizes, our experiments show that CoT prompting alone can improve reasoning in zero-shot settings, while instruction tuning significantly boosts accuracy. However, fine-tuning on CoT prompts does not universally enhance performance and may even degrade it for certain larger models. These findings suggest that reasoning-aware prompts are useful, but their benefits are model- and scale-dependent. Our study offers practical insights into combining prompt engineering with efficient finetuning for medical QA applications.

[Arxiv](https://arxiv.org/abs/2506.12182)