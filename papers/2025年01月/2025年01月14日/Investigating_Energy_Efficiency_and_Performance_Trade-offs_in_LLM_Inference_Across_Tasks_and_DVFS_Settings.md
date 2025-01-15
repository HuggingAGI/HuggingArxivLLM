# 探索LLM推理在不同任务和DVFS设置下的能效与性能权衡。

发布时间：2025年01月14日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在推理过程中的性能和能效问题，分析了不同参数规模和架构对模型表现的影响，并研究了硬件节能技术对模型延迟和能效的影响。这些内容属于对LLMs的理论研究和优化，因此归类为LLM理论。` `人工智能` `能源效率`

> Investigating Energy Efficiency and Performance Trade-offs in LLM Inference Across Tasks and DVFS Settings

# 摘要

> # 摘要
大型语言模型（LLMs）在众多自然语言处理（NLP）任务中表现卓越，推动了其在各行业的广泛应用。然而，这些模型在训练和推理过程中消耗大量计算资源，导致能源消耗激增和环境负担加重。随着LLMs的普及，其可持续性问题日益凸显，亟需在不牺牲性能的前提下优化其运行效率。因此，识别影响LLMs性能和能效的关键参数至关重要。本研究旨在探讨这些参数对LLMs推理过程中性能和能效的影响，并分析其间的权衡关系。
首先，我们通过基准测试Falcon-7B、Mistral-7B-v0.1、T5-3B、GPT-2、GPT-J-6B和GPT-Neo-2.7B等模型，分析了不同参数规模和架构的模型在文本生成、问答和摘要任务中的表现。其次，我们考察了输入输出序列长度等特征对能耗、性能和吞吐量的影响。最后，我们研究了动态电压频率缩放（DVFS）等硬件节能技术对模型延迟和能效的影响。通过广泛的基准测试和统计分析，我们揭示了多项有趣的发现，展示了如何在保持吞吐量和准确性的同时降低能耗。本研究为设计和优化高效能LLM推理系统提供了宝贵的实践指导。

> Large language models (LLMs) have shown significant improvements in many natural language processing (NLP) tasks, accelerating their rapid adoption across many industries. These models are resource-intensive, requiring extensive computational resources both during training and inference, leading to increased energy consumption and negative environmental impact. As their adoption accelerates, the sustainability of LLMs has become a critical issue, necessitating strategies to optimize their runtime efficiency without compromising performance. Hence, it is imperative to identify the parameters that significantly influence the performance and energy efficiency of LLMs. To that end, in this work, we investigate the effect of important parameters on the performance and energy efficiency of LLMs during inference and examine their trade-offs.
  First, we analyze how different types of models with varying numbers of parameters and architectures perform on tasks like text generation, question answering, and summarization by benchmarking LLMs such as Falcon-7B, Mistral-7B-v0.1, T5-3B, GPT-2, GPT-J-6B, and GPT-Neo-2.7B. Second, we study input and output sequence characteristics such as sequence length concerning energy consumption, performance, and throughput. Finally, we explore the impact of hardware-based power-saving techniques, i.e., Dynamic Voltage Frequency Scaling (DVFS), on the models' latency and energy efficiency. Our extensive benchmarking and statistical analysis reveal many interesting findings, uncovering how specific optimizations can reduce energy consumption while maintaining throughput and accuracy. This study provides actionable insights for researchers and practitioners to design energy-efficient LLM inference systems.

[Arxiv](https://arxiv.org/abs/2501.08219)