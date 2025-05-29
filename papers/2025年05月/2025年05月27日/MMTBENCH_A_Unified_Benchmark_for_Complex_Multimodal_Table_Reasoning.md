# MMTBENCH：统一的复杂多模态表格推理基准

发布时间：2025年05月27日

`其他` `数据处理` `信息抽取`

> MMTBENCH: A Unified Benchmark for Complex Multimodal Table Reasoning

# 摘要

> 多模态表格，即整合了半结构化数据与视觉元素（如图表和地图）的表格，在现实世界中无处不在，然而这对现有的视觉语言模型（VLMs）构成了巨大挑战。尽管大型语言模型（LLMs）和VLMs在文本和图像理解方面表现出色，但它们在处理复杂、现实世界的多模态表格推理方面的能力尚未得到充分探索。为了填补这一空白，我们引入了MMTBENCH（多模态表格基准测试），这是一个包含500个来自多样化现实世界来源的多模态表格的基准，总共有4021个问答对。MMTBENCH的问题涵盖了四种问题类型（显式、隐式、答案提及和基于视觉），五种推理类型（数学、极值识别、事实验证、基于视觉和其他），以及八种表格类型（单一/多个实体、带实体的地图和图表、单一/多个图表、地图和可视化）。对现有先进模型在所有类型上的广泛评估揭示了显著的性能差距，特别是在需要基于视觉推理和多步推理的问题上。这些发现凸显了迫切需要改进架构，以更紧密地整合视觉和语言处理。通过提供一个具有挑战性、高质量的资源，反映现实任务的复杂性，MMTBENCH突显了其作为未来多模态表格研究资源的价值。

> Multimodal tables those that integrate semi structured data with visual elements such as charts and maps are ubiquitous across real world domains, yet they pose a formidable challenge to current vision language models (VLMs). While Large Language models (LLMs) and VLMs have demonstrated strong capabilities in text and image understanding, their performance on complex, real world multimodal table reasoning remains unexplored. To bridge this gap, we introduce MMTBENCH (Multimodal Table Benchmark), a benchmark consisting of 500 real world multimodal tables drawn from diverse real world sources, with a total of 4021 question answer pairs. MMTBENCH questions cover four question types (Explicit, Implicit, Answer Mention, and Visual Based), five reasoning types (Mathematical, Extrema Identification, Fact Verification, Vision Based, and Others), and eight table types (Single/Multiple Entity, Maps and Charts with Entities, Single/Multiple Charts, Maps, and Visualizations). Extensive evaluation of state of the art models on all types reveals substantial performance gaps, particularly on questions requiring visual-based reasoning and multi-step inference. These findings show the urgent need for improved architectures that more tightly integrate vision and language processing. By providing a challenging, high-quality resource that mirrors the complexity of real-world tasks, MMTBENCH underscores its value as a resource for future research on multimodal tables.

[Arxiv](https://arxiv.org/abs/2505.21771)