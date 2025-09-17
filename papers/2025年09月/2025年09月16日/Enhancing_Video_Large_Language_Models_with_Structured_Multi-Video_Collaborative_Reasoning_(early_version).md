# 基于结构化多视频协同推理的视频大语言模型增强（早期版本）

发布时间：2025年09月16日

`LLM应用` `媒体与娱乐`

> Enhancing Video Large Language Models with Structured Multi-Video Collaborative Reasoning (early version)

# 摘要

> 尽管视频语言模型已蓬勃发展，但当前对全面视频推理的追求却因个体视频固有的时空信息不完整而受阻，进而产生幻觉与推理偏差。潜在的解决方案是通过引入多个相关视频来提升推理性能。然而，视频 tokens 数量庞大且存在冗余信息，若直接将相关视频数据输入大型语言模型以增强响应，反而可能收效甚微。针对这一问题，我们提出了面向视频语言模型的多视频协作框架。为实现高效且灵活的视频表示，我们设计了视频结构化模块，将视频知识转化为时空图。基于此结构化表示，我们设计了图融合模块，将相关视频的结构化知识与关键信息融合至增强的图节点 tokens 中。最后，我们构建了精心设计的多视频结构化提示，将图、视觉及文本 tokens 整合为大型语言模型的输入。大量实验结果验证了该框架的有效性，凸显了其在推动视频语言模型发展方面的潜力，为该领域提供了新的研究方向。

> Despite the prosperity of the video language model, the current pursuit of comprehensive video reasoning is thwarted by the inherent spatio-temporal incompleteness within individual videos, resulting in hallucinations and inaccuracies. A promising solution is to augment the reasoning performance with multiple related videos. However, video tokens are numerous and contain redundant information, so directly feeding the relevant video data into a large language model to enhance responses could be counterproductive. To address this challenge, we propose a multi-video collaborative framework for video language models. For efficient and flexible video representation, we establish a Video Structuring Module to represent the video's knowledge as a spatio-temporal graph. Based on the structured video representation, we design the Graph Fusion Module to fuse the structured knowledge and valuable information from related videos into the augmented graph node tokens. Finally, we construct an elaborate multi-video structured prompt to integrate the graph, visual, and textual tokens as the input to the large language model. Extensive experiments substantiate the effectiveness of our framework, showcasing its potential as a promising avenue for advancing video language models.

[Arxiv](https://arxiv.org/abs/2509.13161)