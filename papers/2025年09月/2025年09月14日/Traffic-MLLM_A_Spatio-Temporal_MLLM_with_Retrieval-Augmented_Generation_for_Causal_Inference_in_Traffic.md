# Traffic-MLLM：融合检索增强生成的时空MLLM——面向交通因果推断

发布时间：2025年09月14日

`LLM应用` `交通运输`

> Traffic-MLLM: A Spatio-Temporal MLLM with Retrieval-Augmented Generation for Causal Inference in Traffic

# 摘要

> 随着智能交通系统的不断进步，交通视频理解在全面场景感知与因果分析中发挥着日益关键的作用。然而，现有方法在精准建模时空因果关系、整合领域专业知识方面存在明显不足，导致其在复杂场景中的表现受限。针对这些问题，我们提出了Traffic-MLLM——一款专为细粒度交通分析打造的多模态大型语言模型。该模型以Qwen2.5-VL为基础架构，通过高质量交通专用多模态数据集训练，并采用低秩适应（LoRA）进行轻量化微调，大幅提升了对视频序列中连续时空特征的建模能力。此外，我们创新性地设计了知识提示模块，融合思维链（CoT）推理与检索增强生成（RAG）技术，可将详细交通法规与领域知识精准融入推理过程。这一设计显著增强了模型的逻辑推理与知识适配能力。在TrafficQA和DriveQA基准数据集上的实验结果显示，Traffic-MLLM性能达到当前最优水平，充分证明了其处理多模态交通数据的出色能力。同时，该模型还展现出优异的零样本推理和跨场景泛化能力。

> As intelligent transportation systems advance, traffic video understanding plays an increasingly pivotal role in comprehensive scene perception and causal analysis. Yet, existing approaches face notable challenges in accurately modeling spatiotemporal causality and integrating domain-specific knowledge, limiting their effectiveness in complex scenarios. To address these limitations, we propose Traffic-MLLM, a multimodal large language model tailored for fine-grained traffic analysis. Built on the Qwen2.5-VL backbone, our model leverages high-quality traffic-specific multimodal datasets and uses Low-Rank Adaptation (LoRA) for lightweight fine-tuning, significantly enhancing its capacity to model continuous spatiotemporal features in video sequences. Furthermore, we introduce an innovative knowledge prompting module fusing Chain-of-Thought (CoT) reasoning with Retrieval-Augmented Generation (RAG), enabling precise injection of detailed traffic regulations and domain knowledge into the inference process. This design markedly boosts the model's logical reasoning and knowledge adaptation capabilities. Experimental results on TrafficQA and DriveQA benchmarks show Traffic-MLLM achieves state-of-the-art performance, validating its superior ability to process multimodal traffic data. It also exhibits remarkable zero-shot reasoning and cross-scenario generalization capabilities.

[Arxiv](https://arxiv.org/abs/2509.11165)