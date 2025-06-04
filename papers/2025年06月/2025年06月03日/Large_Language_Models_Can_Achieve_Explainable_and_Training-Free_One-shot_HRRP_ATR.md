# 大型语言模型能够实现可解释且无需训练的一次性HRRP ATR任务

发布时间：2025年06月03日

`LLM应用

理由：这篇论文将大型语言模型（LLMs）应用于高分辨率距离像（HRRP）的自动目标识别（ATR）任务。通过将HRRP信号转换为文本描述，并利用精心设计的提示，使LLMs能够进行上下文学习，从而完成ATR任务。这属于将LLM应用于特定领域任务的创新应用，因此归类为LLM应用。` `自动目标识别`

> Large Language Models Can Achieve Explainable and Training-Free One-shot HRRP ATR

# 摘要

> 本文提出了一种开创性的无训练、可解释框架，用于高分辨率距离像（HRRP）自动目标识别（ATR），该框架基于大规模预训练的大型语言模型（LLMs）。与传统方法不同，传统方法通常需要大量特定任务的训练或微调，我们的方法将一维HRRP信号转换为文本形式的散射中心描述。通过精心设计的提示，我们使LLMs的语义空间与ATR任务对齐，利用其丰富的预训练知识进行少量样本的上下文学习，无需任何参数更新。为了推动基于LLMs的HRRP ATR研究，我们公开了我们的代码，方便研究者进一步探索和改进。

> This letter introduces a pioneering, training-free and explainable framework for High-Resolution Range Profile (HRRP) automatic target recognition (ATR) utilizing large-scale pre-trained Large Language Models (LLMs). Diverging from conventional methods requiring extensive task-specific training or fine-tuning, our approach converts one-dimensional HRRP signals into textual scattering center representations. Prompts are designed to align LLMs' semantic space for ATR via few-shot in-context learning, effectively leveraging its vast pre-existing knowledge without any parameter update. We make our codes publicly available to foster research into LLMs for HRRP ATR.

[Arxiv](https://arxiv.org/abs/2506.02465)