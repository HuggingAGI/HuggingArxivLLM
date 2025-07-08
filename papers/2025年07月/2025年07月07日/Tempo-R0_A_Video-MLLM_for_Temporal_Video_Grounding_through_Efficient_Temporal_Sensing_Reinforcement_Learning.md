# # Tempo-R0：基于高效时间感知强化学习的视频多模态大语言模型，专为时间视频定位而设计。

发布时间：2025年07月07日

`LLM应用` `视频技术` `视频分析`

> Tempo-R0: A Video-MLLM for Temporal Video Grounding through Efficient Temporal Sensing Reinforcement Learning

# 摘要

> 时间视频定位（TVG）是一项极具挑战性的视频理解任务，要求根据语言查询精准定位视频中的相关时间片段。由于视频通常包含大量信息和冗余内容，模型需要全面理解整个视频才能准确检索相关片段。为此，我们提出了Tempo-R0：一款专为时间视频定位任务设计的视频多模态大型语言模型（Video-MLLM），通过多模态时间感知强化学习实现。具体而言，在预处理阶段，我们采用基于帧内容变化的自适应注意力分配（SAA）方法，以高效利用 MLLM 的有限注意力资源。同时，显式时间模态对齐（ETA）方法被用于增强模型对视频中事件边界的感知能力。在微调阶段，我们创新性地将部分无关拒绝的组相对策略优化（PIR-GRPO）应用于 TVG 领域，不仅帮助模型接受相关视频-查询对，还能有效拒绝无关对，从而提升其时间推理能力。实验结果表明，与现有最优方法相比，我们的方法在原始 QVHighlights 测试基准及其更合理的标注修正版本上，均取得了约 3.5% 的显著优势。

> Temporal Video Grounding (TVG), which requires pinpointing relevant temporal segments from video based on language query, has always been a highly challenging task in the field of video understanding. Videos often have a larger volume of information and redundancy than texts or images. Models should present comprehensive understanding of the whole video to accurately retrieve query-relevant clips. We thus propose Tempo-R0: a Video Multimodal Large Language Model (Video-MLLM) for the temporal video grounding task via multimodal temporal sensing reinforcement. Specifically, during the preprocessing stage of our pipeline, we employ Self-adaptive Attention Allocation (SAA) method based on frame content variation to efficiently use the MLLM's limited attention. The Explicit Timestamp-modal Aligned (ETA) method is also utilized to strengthen our model's capability to perceive the boundaries of events in the video. In the fine-tuning part of our pipeline, we creatively apply Partial Irrelevance Refusing-based Group Relative Policy Optimization (PIR-GRPO) in TVG area to foster model's temporal reasoning from not only accepting relevant video-query pairs but also refusing irrelevant ones. Experiments demonstrate that our method accomplishes a notable advantage over SOTA solutions by around 3.5% on both the original QVHighlights testbench and its corrected version with more reasonable ground truth annotations.

[Arxiv](https://arxiv.org/abs/2507.04702)