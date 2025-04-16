# # 从误导提问到精准回答：LLM的三阶段微调方法

发布时间：2025年04月15日

`LLM应用` `信息处理`

> From Misleading Queries to Accurate Answers: A Three-Stage Fine-Tuning Method for LLMs

# 摘要

> 大型语言模型（LLMs）在自然语言处理中表现出色，但对输入查询质量高度敏感，尤其当查询包含误导或不准确信息时。现有方法多专注于纠正输出，却忽视了提升模型检测和纠正输入中误导内容的能力。本文提出一种三阶段微调方法，旨在增强LLMs检测和纠正输入误导信息的能力，从而提高回答准确性并减少幻觉生成。具体包括：(1) 训练模型识别误导信息，(2) 利用内置或外部知识纠正误导信息，(3) 根据纠正后的查询生成准确答案。我们在三个幻觉检测和问答任务数据集，以及两个自建的误导信息数据集上进行了实验。结果表明，该方法显著提升了LLM响应的准确性和事实性，增强了幻觉检测能力，并减少了输出中的幻觉生成，尤其在查询含误导信息时效果显著。我们将在论文被接受后公开代码。

> Large language models (LLMs) exhibit excellent performance in natural language processing (NLP), but remain highly sensitive to the quality of input queries, especially when these queries contain misleading or inaccurate information. Existing methods focus on correcting the output, but they often overlook the potential of improving the ability of LLMs to detect and correct misleading content in the input itself. In this paper, we propose a novel three-stage fine-tuning method that enhances the ability of LLMs to detect and correct misleading information in the input, further improving response accuracy and reducing hallucinations. Specifically, the three stages include (1) training LLMs to identify misleading information, (2) training LLMs to correct the misleading information using built-in or external knowledge, and (3) training LLMs to generate accurate answers based on the corrected queries. To evaluate our method, we conducted experiments on three datasets for the hallucination detection task and the question answering (QA) task, as well as two datasets containing misleading information that we constructed. The experimental results demonstrate that our method significantly improves the accuracy and factuality of LLM responses, while also enhancing the ability to detect hallucinations and reducing the generation of hallucinations in the output, particularly when the query contains misleading information. We will publicly release our code upon acceptance.

[Arxiv](https://arxiv.org/abs/2504.11277)