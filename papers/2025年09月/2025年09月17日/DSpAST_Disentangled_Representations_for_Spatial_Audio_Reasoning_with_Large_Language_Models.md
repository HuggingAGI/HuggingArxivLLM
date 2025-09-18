# DSpAST：基于大型语言模型的空间音频推理解耦表示

发布时间：2025年09月17日

`LLM应用` `媒体与娱乐`

> DSpAST: Disentangled Representations for Spatial Audio Reasoning with Large Language Models

# 摘要

> 利用大型语言模型进行空间音频推理时，需以空间音频编码器作为声学前端，获取用于后续处理的音频嵌入。这类编码器需捕获检测声音事件类型、对应声源方向及距离所需的全部信息。由于这些任务所需信息大多相互独立，单个音频编码器难以胜任这一需求，因此其性能往往不及特定任务音频编码器。为此，我们提出新型音频编码器DSpAST——它基于SpatialAST构建，能学习空间音频的解纠缠表示，且仅增加0.2%的参数。在SpatialSoundQA数据集上，通过空间音频推理系统BAT进行的实验证实，DSpAST性能显著优于SpatialAST。

> Reasoning about spatial audio with large language models requires a spatial audio encoder as an acoustic front-end to obtain audio embeddings for further processing. Such an encoder needs to capture all information required to detect the type of sound events, as well as the direction and distance of their corresponding sources. Accomplishing this with a single audio encoder is demanding as the information required for each of these tasks is mostly independent of each other. As a result, the performance obtained with a single encoder is often worse than when using task-specific audio encoders. In this work, we present DSpAST, a novel audio encoder based on SpatialAST that learns disentangled representations of spatial audio while having only 0.2% additional parameters. Experiments on SpatialSoundQA with the spatial audio reasoning system BAT demonstrate that DSpAST significantly outperforms SpatialAST.

[Arxiv](https://arxiv.org/abs/2509.13927)