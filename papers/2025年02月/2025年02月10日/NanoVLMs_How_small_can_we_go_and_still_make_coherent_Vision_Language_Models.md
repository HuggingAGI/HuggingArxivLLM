# # NanoVLMs：如何在保持视觉语言模型连贯性的同时做到极致轻量化？

发布时间：2025年02月10日

`LLM应用` `多模态模型` `数据科学`

> NanoVLMs: How small can we go and still make coherent Vision Language Models?

# 摘要

> 视觉语言模型（VLMs）在多模态任务中表现卓越，但受限于专有性、计算需求和可访问性等挑战。现有的小模型如GIT和BLIP难以生成连贯文本，这让我们思考：VLMs能有多小还能保持流畅输出？受3-4岁儿童视觉学习启发，我们推出了ShortDesc和LongDesc两个数据集，由GPT-4o生成，采用简单词汇和语法。通过这些数据集，我们成功训练出比现有小模型小10倍的VLMs，架构简洁。我们采用GPT-4o进行多维度评分，弥补传统基准不足。这项研究为资源受限环境开发轻量级多模态模型提供了新思路。

> Vision-Language Models (VLMs), such as GPT-4V and Llama 3.2 vision, have garnered significant research attention for their ability to leverage Large Language Models (LLMs) in multimodal tasks. However, their potential is constrained by inherent challenges, including proprietary restrictions, substantial computational demands, and limited accessibility. Smaller models, such as GIT and BLIP, exhibit marked limitations, often failing to generate coherent and consistent text beyond a few tokens, even with extensive training. This underscores a pivotal inquiry: how small can a VLM be and still produce fluent and consistent text? Drawing inspiration from the exceptional learning process of 3-4 year old children, who rely heavily on visual cues for understanding and communication, we introduce two novel datasets: ShortDesc (featuring concise image descriptions) and LongDesc (containing more detailed image descriptions). These datasets consist of image-text pairs where the text is restricted to the simple vocabulary and syntax typically used by young children, generated with a scaled- down model, GPT-4o. Using these datasets, we demonstrate that it is possible to train VLMs that are significantly smaller, up to 10 times smaller than state of the art(SOTA) small VLMs while maintaining architectural simplicity. To evaluate the outputs, we leverage GPT-4o to grade the text, as if stories written by students, on creativity, meaningfulness, and consistency, assigning scores out of 10. This method addresses limitations of standard benchmarks by accommodating unstructured outputs and providing a multidimensional evaluation of the model capabilities. Our findings contribute to the development of lightweight, accessible multimodal models for resource constrained environments.

[Arxiv](https://arxiv.org/abs/2502.07838)