# ReFF：于各类任务中增强语言模型的格式忠实度

发布时间：2024年12月12日

`LLM应用` `人工智能`

> ReFF: Reinforcing Format Faithfulness in Language Models across Varied Tasks

# 摘要

> 遵循格式化指令生成结构优良的内容，对于大型语言模型（LLMs）而言是一项基础但常未达标的能力。为研究此能力，我们将其称为格式忠实度，并推出了FormatBench，这是一个全面的格式相关基准。和以往的格式相关基准相比，FormatBench在应用场景（传统的NLP任务、创意作品、自主代理任务）、人与LLM的交互方式（单轮指令、多轮聊天）以及格式类型（包含、包装、长度、编码）等方面涵盖了更多样的任务。而且，FormatBench中的每个任务都配有一个格式检查程序。在该基准上的大量实验显示，最先进的开源和闭源LLMs在格式忠实度方面仍存在严重不足。凭借格式的可判定性，我们提出强化格式忠实度（ReFF），助力LLMs按指示生成格式化输出，且不影响总体质量。在无任何标注数据的情况下，ReFF能大幅提升格式忠实度率（比如，从原始LLaMA3的21.6%提升至标题分割任务的95.0%），同时保持总体质量相近（比如，F1分数从47.3降至46.4）。结合有标签的训练数据，ReFF能够同时提高格式忠实度（比如，从原始LLaMA3的21.6%提升至75.5%）和总体质量（比如，F1分数从47.3提升至61.6）。我们进一步提供了可解释性分析，以阐释ReFF如何提升格式忠实度和总体质量。

> Following formatting instructions to generate well-structured content is a fundamental yet often unmet capability for large language models (LLMs). To study this capability, which we refer to as format faithfulness, we present FormatBench, a comprehensive format-related benchmark. Compared to previous format-related benchmarks, FormatBench involves a greater variety of tasks in terms of application scenes (traditional NLP tasks, creative works, autonomous agency tasks), human-LLM interaction styles (single-turn instruction, multi-turn chat), and format types (inclusion, wrapping, length, coding). Moreover, each task in FormatBench is attached with a format checker program. Extensive experiments on the benchmark reveal that state-of-the-art open- and closed-source LLMs still suffer from severe deficiency in format faithfulness. By virtue of the decidable nature of formats, we propose to Reinforce Format Faithfulness (ReFF) to help LLMs generate formatted output as instructed without compromising general quality. Without any annotated data, ReFF can substantially improve the format faithfulness rate (e.g., from 21.6% in original LLaMA3 to 95.0% on caption segmentation task), while keep the general quality comparable (e.g., from 47.3 to 46.4 in F1 scores). Combined with labeled training data, ReFF can simultaneously improve both format faithfulness (e.g., from 21.6% in original LLaMA3 to 75.5%) and general quality (e.g., from 47.3 to 61.6 in F1 scores). We further offer an interpretability analysis to explain how ReFF improves both format faithfulness and general quality.

[Arxiv](https://arxiv.org/abs/2412.09173)