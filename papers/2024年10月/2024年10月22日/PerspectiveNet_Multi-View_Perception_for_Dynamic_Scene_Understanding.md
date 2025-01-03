# PerspectiveNet: 多视角感知助力动态场景理解

发布时间：2024年10月22日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来生成多视角的详细描述，特别是在交通安全描述与分析任务中。论文的核心是利用LLMs的自然语言生成能力，结合视觉特征提取模型和其他模块，构建一个轻量高效的模型。因此，这篇论文属于LLM应用类别。` `交通安全` `视觉分析`

> PerspectiveNet: Multi-View Perception for Dynamic Scene Understanding

# 摘要

> 由于视觉数据的复杂性和不一致性，从多摄像头和多视角生成详细描述颇具挑战。本文提出 PerspectiveNet，一个轻量高效的模型，用于生成跨多视角的长描述。我们采用视觉编码器、紧凑的连接器模块将视觉特征转换为固定大小的张量，并借助大型语言模型（LLMs）的强大自然语言生成能力。连接器模块的设计目标有三：将视觉特征映射到 LLM 嵌入、突出生成描述所需的关键信息，并生成固定大小的特征矩阵。此外，我们还引入了一个辅助任务——帧序列检测，使模型能够搜索正确的帧序列以生成描述。最终，我们将连接器模块、辅助任务、LLM 和视觉特征提取模型整合为一个单一架构，专门用于交通安全描述与分析任务。该任务要求从多摄像头和多视角生成事件的详细、细粒度描述。该模型轻量高效，训练和推理速度快，同时保持出色的性能。

> Generating detailed descriptions from multiple cameras and viewpoints is challenging due to the complex and inconsistent nature of visual data. In this paper, we introduce PerspectiveNet, a lightweight yet efficient model for generating long descriptions across multiple camera views. Our approach utilizes a vision encoder, a compact connector module to convert visual features into a fixed-size tensor, and large language models (LLMs) to harness the strong natural language generation capabilities of LLMs. The connector module is designed with three main goals: mapping visual features onto LLM embeddings, emphasizing key information needed for description generation, and producing a fixed-size feature matrix. Additionally, we augment our solution with a secondary task, the correct frame sequence detection, enabling the model to search for the correct sequence of frames to generate descriptions. Finally, we integrate the connector module, the secondary task, the LLM, and a visual feature extraction model into a single architecture, which is trained for the Traffic Safety Description and Analysis task. This task requires generating detailed, fine-grained descriptions of events from multiple cameras and viewpoints. The resulting model is lightweight, ensuring efficient training and inference, while remaining highly effective.

[Arxiv](https://arxiv.org/abs/2410.16824)