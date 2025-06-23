# SGIC：自引导迭代校准框架，专为RAG打造

发布时间：2025年06月19日

`RAG` `生成模型`

> SGIC: A Self-Guided Iterative Calibration Framework for RAG

# 摘要

> 检索增强生成（RAG）领域的最新研究主要聚焦于从候选文档中提取有用信息。然而，现有方法往往忽视了大型语言模型（LLMs）的校准潜力，这些潜力得益于其强大的上下文推理能力。研究表明，为LLMs提供特定提示能显著提升校准效果，尤其在多轮校准中表现突出。为此，我们提出了一种创新的SGIC框架：自引导迭代校准框架，该框架巧妙运用不确定性评分作为核心工具。首先，框架通过计算不确定性评分，精准评估每个文档与查询的相关性，以及LLMs生成回复的可信度。随后，它会迭代更新这些评分，并结合历史回复进行优化，从而实现更精准的校准。此外，我们还开发了一种新颖的迭代自校准训练集构建方法，该方法能够优化LLMs，使其更高效地利用不确定性评分捕捉关键信息并提升回复质量。实验结果表明，我们的框架在闭源和开源权重的LLMs上均取得了显著性能提升。

> Recent research in retrieval-augmented generation (RAG) has concentrated on retrieving useful information from candidate documents. However, numerous methodologies frequently neglect the calibration capabilities of large language models (LLMs), which capitalize on their robust in-context reasoning prowess. This work illustrates that providing LLMs with specific cues substantially improves their calibration efficacy, especially in multi-round calibrations. We present a new SGIC: Self-Guided Iterative Calibration Framework that employs uncertainty scores as a tool. Initially, this framework calculates uncertainty scores to determine both the relevance of each document to the query and the confidence level in the responses produced by the LLMs. Subsequently, it reevaluates these scores iteratively, amalgamating them with prior responses to refine calibration. Furthermore, we introduce an innovative approach for constructing an iterative self-calibration training set, which optimizes LLMs to efficiently harness uncertainty scores for capturing critical information and enhancing response accuracy. Our proposed framework significantly improves performance on both closed-source and open-weight LLMs.

[Arxiv](https://arxiv.org/abs/2506.16172)