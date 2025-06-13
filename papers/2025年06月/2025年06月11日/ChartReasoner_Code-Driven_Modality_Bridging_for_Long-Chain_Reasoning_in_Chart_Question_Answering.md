# ChartReasoner：代码驱动的模态间桥接，助力图表问答中的长链推理。

发布时间：2025年06月11日

`LLM应用` `数据分析` `人工智能`

> ChartReasoner: Code-Driven Modality Bridging for Long-Chain Reasoning in Chart Question Answering

# 摘要

> 大型语言模型在长链推理中展现了卓越的推理能力，但如何将其扩展到视觉推理任务仍是待解难题。现有方法通过图像到文本的转换实现多模态推理，却常在图表问答等任务中丢失关键的结构与语义信息。为此，我们提出了ChartReasoner，一个代码驱动的两阶段框架，专为精准、可解释的图表推理而设计。

首先，我们训练了一个高保真模型，将多样化的图表图像转化为结构化的ECharts代码，最大限度地保留布局与数据语义。接着，我们设计了一个通用的图表推理数据合成管道，利用预训练的传输模型自动、可扩展地生成推理轨迹，并借助代码验证器筛选高质量样本。最终，我们在合成的数据集上结合监督微调与强化学习训练多模态模型。实验结果表明，ChartReasoner在四个公开基准上表现优异，不仅保留图表细节，更以更少参数匹敌顶尖开源模型，甚至在跨领域场景中逼近GPT-4等专有系统。

> Recently, large language models have shown remarkable reasoning capabilities through long-chain reasoning before responding. However, how to extend this capability to visual reasoning tasks remains an open challenge. Existing multimodal reasoning approaches transfer such visual reasoning task into textual reasoning task via several image-to-text conversions, which often lose critical structural and semantic information embedded in visualizations, especially for tasks like chart question answering that require a large amount of visual details. To bridge this gap, we propose ChartReasoner, a code-driven novel two-stage framework designed to enable precise, interpretable reasoning over charts. We first train a high-fidelity model to convert diverse chart images into structured ECharts codes, preserving both layout and data semantics as lossless as possible. Then, we design a general chart reasoning data synthesis pipeline, which leverages this pretrained transport model to automatically and scalably generate chart reasoning trajectories and utilizes a code validator to filter out low-quality samples. Finally, we train the final multimodal model using a combination of supervised fine-tuning and reinforcement learning on our synthesized chart reasoning dataset and experimental results on four public benchmarks clearly demonstrate the effectiveness of our proposed ChartReasoner. It can preserve the original details of the charts as much as possible and perform comparably with state-of-the-art open-source models while using fewer parameters, approaching the performance of proprietary systems like GPT-4o in out-of-domain settings.

[Arxiv](https://arxiv.org/abs/2506.10116)