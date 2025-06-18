# # 工具增强型大型语言模型的重新初始化令牌学习方法

发布时间：2025年06月17日

`LLM应用` `人工智能` `工具整合`

> Re-Initialization Token Learning for Tool-Augmented Large Language Models

# 摘要

> 大型语言模型虽然表现出色，但在数值推理和计划生成等复杂任务上仍有不足。将计算器、数据库等外部工具整合到大型语言模型（LLMs）中，是提升其问题解决能力的关键。现有的方法为每个工具分配唯一令牌，使LLMs能够通过令牌预测（类似于单词生成）调用工具。然而，这种方法未能考虑工具与单词令牌之间的关系，限制了预训练LLMs的适应性。为解决这一问题，我们提出了一种新型令牌学习方法，从初始化的角度使工具令牌与现有的单词嵌入空间对齐，从而提升模型性能。我们首先根据工具的名称或描述构建每个工具的先验令牌嵌入，用于初始化和正则化可学习的工具令牌嵌入。这确保了学习到的嵌入与单词令牌空间良好对齐，提高了工具调用的准确性。我们在GSM8K-XL、FuncQA、KAMEL和VirtualHome数据集上，针对数值推理、基于知识的问题回答和具身计划生成等任务评估了该方法。结果表明，与最近的基线方法（包括CoT、REACT、ICL和ToolkenGPT）相比，我们的方法有明显改进，表明我们的方法通过相关令牌有效增强了LLMs在多个领域的能力。


> Large language models have demonstrated exceptional performance, yet struggle with complex tasks such as numerical reasoning, plan generation. Integrating external tools, such as calculators and databases, into large language models (LLMs) is crucial for enhancing problem-solving capabilities. Current methods assign a unique token to each tool, enabling LLMs to call tools through token prediction-similar to word generation. However, this approach fails to account for the relationship between tool and word tokens, limiting adaptability within pre-trained LLMs. To address this issue, we propose a novel token learning method that aligns tool tokens with the existing word embedding space from the perspective of initialization, thereby enhancing model performance. We begin by constructing prior token embeddings for each tool based on the tool's name or description, which are used to initialize and regularize the learnable tool token embeddings. This ensures the learned embeddings are well-aligned with the word token space, improving tool call accuracy. We evaluate the method on tasks such as numerical reasoning, knowledge-based question answering, and embodied plan generation using GSM8K-XL, FuncQA, KAMEL, and VirtualHome datasets. The results demonstrate clear improvements over recent baselines, including CoT, REACT, ICL, and ToolkenGPT, indicating that our approach effectively augments LLMs with tools through relevant tokens across diverse domains.

[Arxiv](https://arxiv.org/abs/2506.14248)