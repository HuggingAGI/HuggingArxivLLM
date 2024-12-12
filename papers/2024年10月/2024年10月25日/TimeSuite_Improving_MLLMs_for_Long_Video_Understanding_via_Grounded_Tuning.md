# TimeSuite：借助基础调优提升用于长视频理解的大型多模态语言模型

发布时间：2024年10月25日

`LLM应用` `短视频` `长视频`

> TimeSuite: Improving MLLMs for Long Video Understanding via Grounded Tuning

# 摘要

> 多模态大型语言模型（MLLMs）在短视频理解领域表现抢眼。但对 MLLMs 而言，理解长视频依旧困难重重。本文提出 TimeSuite，这是一系列用于让现有的短视频 MLLMs 适应长视频理解的新设计，涵盖一个简便高效的长视频序列处理框架、一个用于 MLLMs 针对性调整的高质量视频数据集，以及一个精心策划的指令调整任务，将针对性监督以传统问答形式清晰融入。具体来说，基于 VideoChat，我们通过实施令牌打乱压缩长视频令牌，并引入时间自适应位置编码（TAPE）增强视觉表示的时间感知，提出了长视频 MLLM——VideoChat-T。同时，我们引入 TimePro，这是一个由 9 个任务和 349k 高质量针对性注释构成的以针对性为核心的综合指令调整数据集。值得注意的是，我们设计了一种新的指令调整任务类型——时间针对性字幕，用于进行带有相应时间戳预测的详细视频描述。这种明确的时间位置预测能引导 MLLM 在生成描述时正确关注视觉内容，从而降低由 LLMs 导致的幻觉风险。实验结果表明，我们的 TimeSuite 成功提升了短视频 MLLM 理解长视频的能力，在 Egoschema 和 VideoMME 的基准测试中分别提高了 5.6％和 6.8％。此外，VideoChat-T 展现出强大的零样本时间针对性能力，大幅超越现有的先进 MLLMs。经过微调后，其表现与传统的有监督专家模型旗鼓相当。

> Multimodal Large Language Models (MLLMs) have demonstrated impressive performance in short video understanding. However, understanding long-form videos still remains challenging for MLLMs. This paper proposes TimeSuite, a collection of new designs to adapt the existing short-form video MLLMs for long video understanding, including a simple yet efficient framework to process long video sequence, a high-quality video dataset for grounded tuning of MLLMs, and a carefully-designed instruction tuning task to explicitly incorporate the grounding supervision in the traditional QA format. Specifically, based on VideoChat, we propose our long-video MLLM, coined as VideoChat-T, by implementing a token shuffling to compress long video tokens and introducing Temporal Adaptive Position Encoding (TAPE) to enhance the temporal awareness of visual representation. Meanwhile, we introduce the TimePro, a comprehensive grounding-centric instruction tuning dataset composed of 9 tasks and 349k high-quality grounded annotations. Notably, we design a new instruction tuning task type, called Temporal Grounded Caption, to peform detailed video descriptions with the corresponding time stamps prediction. This explicit temporal location prediction will guide MLLM to correctly attend on the visual content when generating description, and thus reduce the hallucination risk caused by the LLMs. Experimental results demonstrate that our TimeSuite provides a successful solution to enhance the long video understanding capability of short-form MLLM, achieving improvement of 5.6% and 6.8% on the benchmarks of Egoschema and VideoMME, respectively. In addition, VideoChat-T exhibits robust zero-shot temporal grounding capabilities, significantly outperforming the existing state-of-the-art MLLMs. After fine-tuning, it performs on par with the traditional supervised expert models.

[Arxiv](https://arxiv.org/abs/2410.19702)