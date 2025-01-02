# 在复杂表格问答中，借助工具实现高效的多智能体协作以进行在线规划

发布时间：2024年12月28日

`Agent` `表格问答` `智能协作`

> Efficient Multi-Agent Collaboration with Tool Use for Online Planning in Complex Table Question Answering

# 摘要

> 复杂表格问答（TQA）旨在回答基于表格数据、需要复杂推理（如多步骤或多类别推理）的问题。以往的方法借助闭源大型语言模型（LLMs）或微调的开放权重LLMs取得了显著性能。然而，微调LLMs需要高质量训练数据，获取成本高，使用闭源LLMs存在访问难题和可重复性问题。本文中，我们提出了使用工具的多智能体协作（MACT）框架，它既无需闭源模型，也无需微调。在MACT中，规划智能体和使用工具的编码智能体协同回答问题。我们在四个TQA基准上的实验表明，MACT在四个基准中的三个上超越了以往的SoTA系统，在两个基准上，即便仅使用未微调的开放权重模型，其表现也能与更庞大且更昂贵的闭源模型GPT-4相媲美。我们进行了大量分析，以证明MACT在TQA中的多智能体协作的有效性。

> Complex table question answering (TQA) aims to answer questions that require complex reasoning, such as multi-step or multi-category reasoning, over data represented in tabular form. Previous approaches demonstrated notable performance by leveraging either closed-source large language models (LLMs) or fine-tuned open-weight LLMs. However, fine-tuning LLMs requires high-quality training data, which is costly to obtain, and utilizing closed-source LLMs poses accessibility challenges and leads to reproducibility issues. In this paper, we propose Multi-Agent Collaboration with Tool use (MACT), a framework that requires neither closed-source models nor fine-tuning. In MACT, a planning agent and a coding agent that also make use of tools collaborate to answer questions. Our experiments on four TQA benchmarks show that MACT outperforms previous SoTA systems on three out of four benchmarks and that it performs comparably to the larger and more expensive closed-source model GPT-4 on two benchmarks, even when using only open-weight models without any fine-tuning. We conduct extensive analyses to prove the effectiveness of MACT's multi-agent collaboration in TQA.

[Arxiv](https://arxiv.org/abs/2412.20145)