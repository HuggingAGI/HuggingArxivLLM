# VidCtx：借助图像模型实现的上下文感知视频问答

发布时间：2024年12月23日

`LLM应用` `问答系统`

> VidCtx: Context-aware Video Question Answering with Image Models

# 摘要

> 为应对视频问答任务中大型多模态模型在计算和内存方面的限制，近来的一些方法会为每一帧提取文本表征（比如通过添加字幕），并将其输入大型语言模型（LLM）以生成最终回答。但如此一来，LLM无法获取视觉信息，还常常得处理临近帧的重复文本描述。为克服这些不足，本文引入了 VidCtx 这一全新的无训练视频问答框架，它融合了两种模态，即输入帧的视觉信息以及能提供恰当上下文的其他帧的文本描述。具体而言，在所提出的框架中，会提示预训练的大型多模态模型（LMM）定期提取视频帧的问题感知文本描述（字幕）。当同一 LMM 被提示回答给定的输入问题，即 a）某一帧，b）问题以及 c）适当帧的上下文/字幕时，这些将被用作上下文。为避免冗余信息，我们选择远处帧的描述作为上下文。最后，采用了一种简单而有效的最大池化机制来聚合帧级别的决策。这种方法使模型能够聚焦于视频的相关片段，并能处理大量的帧。实验表明，在依赖开放模型的方法中，VidCtx 在三个公共视频问答基准 NExT-QA、IntentQA 和 STAR 上表现出了极具竞争力的性能。

> To address computational and memory limitations of Large Multimodal Models in the Video Question-Answering task, several recent methods extract textual representations per frame (e.g., by captioning) and feed them to a Large Language Model (LLM) that processes them to produce the final response. However, in this way, the LLM does not have access to visual information and often has to process repetitive textual descriptions of nearby frames. To address those shortcomings, in this paper, we introduce VidCtx, a novel training-free VideoQA framework which integrates both modalities, i.e. both visual information from input frames and textual descriptions of others frames that give the appropriate context. More specifically, in the proposed framework a pre-trained Large Multimodal Model (LMM) is prompted to extract at regular intervals, question-aware textual descriptions (captions) of video frames. Those will be used as context when the same LMM will be prompted to answer the question at hand given as input a) a certain frame, b) the question and c) the context/caption of an appropriate frame. To avoid redundant information, we chose as context the descriptions of distant frames. Finally, a simple yet effective max pooling mechanism is used to aggregate the frame-level decisions. This methodology enables the model to focus on the relevant segments of the video and scale to a high number of frames. Experiments show that VidCtx achieves competitive performance among approaches that rely on open models on three public Video QA benchmarks, NExT-QA, IntentQA and STAR.

[Arxiv](https://arxiv.org/abs/2412.17415)