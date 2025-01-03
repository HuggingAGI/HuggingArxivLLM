# 基于LLM的产品属性值提取的自动化自我优化与修正

发布时间：2025年01月02日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）进行产品属性值提取任务，并评估了自优化技术在该任务中的效果。研究涉及了零样本、少样本上下文学习和微调等场景，并使用了GPT-4o进行评估。这些内容属于LLM在实际应用中的使用和优化，因此归类为“LLM应用”。`

> Automated Self-Refinement and Self-Correction for LLM-based Product Attribute Value Extraction

# 摘要

> 结构化产品数据（属性-值对）是电商平台支持分面搜索和属性比较等功能的关键。然而，供应商常提供非结构化描述，因此提取属性值以确保数据一致性和可用性至关重要。大型语言模型（LLMs）在少样本场景中展现了提取产品属性值的潜力。近期研究表明，自优化技术能提升LLMs在代码生成和文本到SQL翻译等任务中的表现，但在其他任务中，由于处理额外标记，这些技术增加了成本却未提升性能。本文探讨了将基于错误的提示重写和自我纠正两种自优化技术应用于产品属性值提取任务，并在零样本、少样本上下文学习和微调场景中使用GPT-4o进行评估。实验结果显示，这两种技术在不同场景下对模型性能影响甚微，却显著增加了处理成本。对于有训练数据的场景，微调表现最佳，且随着产品描述数量增加，微调的启动成本被抵消。

> Structured product data, in the form of attribute-value pairs, is essential for e-commerce platforms to support features such as faceted product search and attribute-based product comparison. However, vendors often provide unstructured product descriptions, making attribute value extraction necessary to ensure data consistency and usability. Large language models (LLMs) have demonstrated their potential for product attribute value extraction in few-shot scenarios. Recent research has shown that self-refinement techniques can improve the performance of LLMs on tasks such as code generation and text-to-SQL translation. For other tasks, the application of these techniques has resulted in increased costs due to processing additional tokens, without achieving any improvement in performance. This paper investigates applying two self-refinement techniques, error-based prompt rewriting and self-correction, to the product attribute value extraction task. The self-refinement techniques are evaluated across zero-shot, few-shot in-context learning, and fine-tuning scenarios using GPT-4o. The experiments show that both self-refinement techniques have only a marginal impact on the model's performance across the different scenarios, while significantly increasing processing costs. For scenarios with training data, fine-tuning yields the highest performance, while the ramp-up costs of fine-tuning are balanced out as the amount of product descriptions increases.

[Arxiv](https://arxiv.org/abs/2501.01237)