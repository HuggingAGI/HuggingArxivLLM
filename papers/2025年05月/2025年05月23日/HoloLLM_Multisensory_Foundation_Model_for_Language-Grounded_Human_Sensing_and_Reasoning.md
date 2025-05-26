# HoloLLM：多感官语言基础模型，助力人类感知与推理

发布时间：2025年05月23日

`LLM应用` `智能家居` `智能体`

> HoloLLM: Multisensory Foundation Model for Language-Grounded Human Sensing and Reasoning

# 摘要

> 在智能家中运行的具身智能体必须通过多种感官输入理解人类行为，并通过自然语言进行交流。尽管视觉语言模型（VLMs）在基于语言的感知方面取得了令人瞩目的成就，但它们对视觉数据的依赖限制了其在现实场景中的鲁棒性，特别是在存在遮挡、光照不足或隐私限制的情况下。本文中，我们介绍了HoloLLM，这是一种多模态大型语言模型（MLLM），它集成了诸如LiDAR、红外、毫米波雷达和WiFi等不常见但强大的感知模态，以实现在异构环境中无缝感知和推理人类行为。我们解决了两个关键挑战：（1）稀有传感器中对齐的模态-文本数据稀缺，（2）其物理信号表示的异构性。为克服这些挑战，我们设计了一种通用模态注入投影器（UMIP），通过粗细结合的跨模态注意力机制，增强了预对齐的模态嵌入，加入了来自定制编码器的细粒度、文本对齐的特征，而不会引入显著的对齐开销。我们还引入了一种人与VLM协作的数据整理管道，为感知数据集生成配对的文本注释。在两个新构建的基准测试中的大量实验表明，HoloLLM显著超越了现有的MLLM，将基于语言的人类感知准确性提高了高达30%。这项工作为现实世界中基于语言的多感官具身智能奠定了新的基础。


> Embodied agents operating in smart homes must understand human behavior through diverse sensory inputs and communicate via natural language. While Vision-Language Models (VLMs) have enabled impressive language-grounded perception, their reliance on visual data limits robustness in real-world scenarios with occlusions, poor lighting, or privacy constraints. In this paper, we introduce HoloLLM, a Multimodal Large Language Model (MLLM) that integrates uncommon but powerful sensing modalities, such as LiDAR, infrared, mmWave radar, and WiFi, to enable seamless human perception and reasoning across heterogeneous environments. We address two key challenges: (1) the scarcity of aligned modality-text data for rare sensors, and (2) the heterogeneity of their physical signal representations. To overcome these, we design a Universal Modality-Injection Projector (UMIP) that enhances pre-aligned modality embeddings with fine-grained, text-aligned features from tailored encoders via coarse-to-fine cross-attention without introducing significant alignment overhead. We further introduce a human-VLM collaborative data curation pipeline to generate paired textual annotations for sensing datasets. Extensive experiments on two newly constructed benchmarks show that HoloLLM significantly outperforms existing MLLMs, improving language-grounded human sensing accuracy by up to 30%. This work establishes a new foundation for real-world, language-informed multisensory embodied intelligence.

[Arxiv](https://arxiv.org/abs/2505.17645)