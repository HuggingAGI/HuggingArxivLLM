# # 文本到SQL的合理化模型

发布时间：2025年02月10日

`LLM应用

LLM应用` `数据库管理`

> Rationalization Models for Text-to-SQL

# 摘要

> 我们提出了一种生成链式思维（CoT）推理路径的框架，以提升文本到SQL模型的微调效果。这些推理路径包含中间SQL语句和解释，作为构建最终SQL查询的逐步推理步骤。首先，我们手动标注少量示例，并在迭代、动态的少样本知识蒸馏过程中利用这些示例来提示大型语言模型，从教师模型中提取知识。随后，我们基于验证过的分解查询训练一个理性化模型，从而为文本到SQL数据集生成大量合成的CoT注释。为了验证该方法的效果，我们在BIRD数据集上分别使用和不使用这些推理路径对小型语言模型进行微调。实验结果显示，逐步生成查询能够显著提升执行准确率，尤其在处理中等和高度复杂的查询时效果更为明显，同时还能增强模型的可解释性。

> We introduce a framework for generating Chain-of-Thought (CoT) rationales to enhance text-to-SQL model fine-tuning. These rationales consist of intermediate SQL statements and explanations, serving as incremental steps toward constructing the final SQL query. The process begins with manually annotating a small set of examples, which are then used to prompt a large language model in an iterative, dynamic few-shot knowledge distillation procedure from a teacher model. A rationalization model is subsequently trained on the validated decomposed queries, enabling extensive synthetic CoT annotations for text-to-SQL datasets. To evaluate the approach, we fine-tune small language models with and without these rationales on the BIRD dataset. Results indicate that step-by-step query generation improves execution accuracy, especially for moderately and highly complex queries, while also enhancing explainability.

[Arxiv](https://arxiv.org/abs/2502.06759)