# # 摘要
ShortV：冻结无效层中的视觉令牌，实现高效多模态大型语言模型

发布时间：2025年04月01日

`LLM理论` `计算机视觉`

> ShortV: Efficient Multimodal Large Language Models by Freezing Visual Tokens in Ineffective Layers

# 摘要

> 多模态大型语言模型（MLLMs）因规模庞大且视觉标记数量众多，导致计算成本居高不下。本文中，我们引入了一种全新指标——层贡献度（Layer Contribution，LC），通过分层冗余分析MLLMs。LC量化了各层变换对视觉与文本标记的具体影响，其计算基于移除特定标记层变换后模型输出的差异。初步实验表明，MLLMs中许多层在处理视觉标记时贡献度极低。基于此发现，我们提出了无需训练的ShortV方法，利用LC识别低效层，并冻结这些层中的视觉标记更新。实验结果显示，ShortV可在约60%的MLLM层中冻结视觉标记更新，从而大幅降低视觉标记更新相关的计算成本。例如，在LLaVA-NeXT-13B模型上，ShortV实现了50%的FLOPs减少，同时保持了优异性能。代码将在https://github.com/icip-cas/ShortV公开发布。


> Multimodal Large Language Models (MLLMs) suffer from high computational costs due to their massive size and the large number of visual tokens. In this paper, we investigate layer-wise redundancy in MLLMs by introducing a novel metric, Layer Contribution (LC), which quantifies the impact of a layer's transformations on visual and text tokens, respectively. The calculation of LC involves measuring the divergence in model output that results from removing the layer's transformations on the specified tokens. Our pilot experiment reveals that many layers of MLLMs exhibit minimal contribution during the processing of visual tokens. Motivated by this observation, we propose ShortV, a training-free method that leverages LC to identify ineffective layers, and freezes visual token updates in these layers. Experiments show that ShortV can freeze visual token in approximately 60\% of the MLLM layers, thereby dramatically reducing computational costs related to updating visual tokens. For example, it achieves a 50\% reduction in FLOPs on LLaVA-NeXT-13B while maintaining superior performance. The code will be publicly available at https://github.com/icip-cas/ShortV

[Arxiv](https://arxiv.org/abs/2504.00502)