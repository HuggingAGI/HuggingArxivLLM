# FCMR：对金融跨模态多跳推理的稳健性评估

发布时间：2024年12月17日

`LLM应用` `多模态推理`

> FCMR: Robust Evaluation of Financial Cross-Modal Multi-Hop Reasoning

# 摘要

> 在现实世界中做决策，往往需要整合并推理来自多种模态的信息。尽管近来的多模态大型语言模型（MLLMs）在这类任务中展现出良好前景，但其在不同来源间进行多跳推理的能力尚未得到充分评估。现有的基准测试，像 MMQA，因（1）数据受污染和（2）缺少需要跨越两种以上模态操作的复杂查询而面临挑战，这阻碍了对其性能的准确评估。为解决此问题，我们推出了金融跨模态多跳推理（FCMR）这一基准，旨在促使 MLLMs 整合金融领域内文本报告、表格和图表中的信息，以分析其推理能力。FCMR 分为简单、中等和困难三个难度级别，便于逐步评估。特别是困难级别的问题需要精确的跨模态三跳推理，且旨在避免任何模态被忽略。在这个新基准上的实验显示，即便是最先进的 MLLMs 也表现不佳，表现最佳的模型（Claude 3.5 Sonnet）在最具挑战性的级别上准确率仅为 30.4％。我们还进行了分析，以深入了解模型的内部运作原理，包括发现信息检索阶段存在的关键瓶颈。

> Real-world decision-making often requires integrating and reasoning over information from multiple modalities. While recent multimodal large language models (MLLMs) have shown promise in such tasks, their ability to perform multi-hop reasoning across diverse sources remains insufficiently evaluated. Existing benchmarks, such as MMQA, face challenges due to (1) data contamination and (2) a lack of complex queries that necessitate operations across more than two modalities, hindering accurate performance assessment. To address this, we present Financial Cross-Modal Multi-Hop Reasoning (FCMR), a benchmark created to analyze the reasoning capabilities of MLLMs by urging them to combine information from textual reports, tables, and charts within the financial domain. FCMR is categorized into three difficulty levels-Easy, Medium, and Hard-facilitating a step-by-step evaluation. In particular, problems at the Hard level require precise cross-modal three-hop reasoning and are designed to prevent the disregard of any modality. Experiments on this new benchmark reveal that even state-of-the-art MLLMs struggle, with the best-performing model (Claude 3.5 Sonnet) achieving only 30.4% accuracy on the most challenging tier. We also conduct analysis to provide insights into the inner workings of the models, including the discovery of a critical bottleneck in the information retrieval phase.

[Arxiv](https://arxiv.org/abs/2412.12567)