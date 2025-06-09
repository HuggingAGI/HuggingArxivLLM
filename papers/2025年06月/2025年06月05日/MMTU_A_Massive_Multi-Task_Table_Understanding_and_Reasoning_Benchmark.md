# MMTU：大规模多任务表格理解与推理基准

发布时间：2025年06月05日

`LLM应用

理由：这篇论文专注于评估大型语言模型（LLMs）在处理表格数据方面的应用能力，并提出了一个基准测试MMTU。研究集中在模型在实际任务中的表现和应用，属于LLM的应用领域。` `数据处理` `数据分析`

> MMTU: A Massive Multi-Task Table Understanding and Reasoning Benchmark

# 摘要

> 表格及其应用在电子表格、数据库和计算笔记本等重要场景中发挥着关键作用，这些传统上需要数据工程师、分析师和数据库管理员等专家操作。虽然大型语言模型（LLMs）在处理表格方面取得了显著进展，但对这些能力的全面评估仍然不足。与丰富的自然语言处理基准不同，表格相关任务的评估范围狭窄，仅限于自然语言到 SQL 和表格问答等任务，忽视了专业用户面临的更广泛现实任务。这一差距限制了我们在这一重要领域的理解和模型发展。
  为此，我们推出了 MMTU，一个包含超过 30,000 个问题的大型基准测试，覆盖 25 个真实世界表格任务，旨在全面评估模型在专家级别处理表格的能力。这些任务基于 decades 的计算机科学研究，重点在于专业用户面临的复杂表格挑战。我们发现，MMTU 要求模型结合表格理解、推理和编码等多种技能，而这些对当前前沿模型仍具挑战性，如 OpenAI o4-mini 和 DeepSeek R1 等先进模型在 MMTU 中仅能达到约 60% 的水平，表明存在显著的提升空间。我们通过 MMTU 评估揭示了关键发现，并希望这一基准测试能推动结构化数据处理与分析基础模型的进一步发展。我们的代码和数据已开源，可供访问。

> Tables and table-based use cases play a crucial role in many important real-world applications, such as spreadsheets, databases, and computational notebooks, which traditionally require expert-level users like data engineers, data analysts, and database administrators to operate. Although LLMs have shown remarkable progress in working with tables (e.g., in spreadsheet and database copilot scenarios), comprehensive benchmarking of such capabilities remains limited. In contrast to an extensive and growing list of NLP benchmarks, evaluations of table-related tasks are scarce, and narrowly focus on tasks like NL-to-SQL and Table-QA, overlooking the broader spectrum of real-world tasks that professional users face. This gap limits our understanding and model progress in this important area.
  In this work, we introduce MMTU, a large-scale benchmark with over 30K questions across 25 real-world table tasks, designed to comprehensively evaluate models ability to understand, reason, and manipulate real tables at the expert-level. These tasks are drawn from decades' worth of computer science research on tabular data, with a focus on complex table tasks faced by professional users. We show that MMTU require a combination of skills -- including table understanding, reasoning, and coding -- that remain challenging for today's frontier models, where even frontier reasoning models like OpenAI o4-mini and DeepSeek R1 score only around 60%, suggesting significant room for improvement. We highlight key findings in our evaluation using MMTU and hope that this benchmark drives further advances in understanding and developing foundation models for structured data processing and analysis. Our code and data are available at https://github.com/MMTU-Benchmark/MMTU and https://huggingface.co/datasets/MMTU-benchmark/MMTU.

[Arxiv](https://arxiv.org/abs/2506.05587)