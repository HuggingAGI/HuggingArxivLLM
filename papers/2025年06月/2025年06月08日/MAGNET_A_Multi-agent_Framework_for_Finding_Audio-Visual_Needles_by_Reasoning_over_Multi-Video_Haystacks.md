# MAGNET：一个多智能体框架，通过推理多个视频中的内容，精准捕捉音视频中的关键信息。

发布时间：2025年06月08日

`Agent

摘要中提到的多智能体框架MAGNET是论文的核心内容，专注于多视频检索与时间定位任务，属于智能体的应用，因此归类为Agent。` `视频处理` `问答系统`

> MAGNET: A Multi-agent Framework for Finding Audio-Visual Needles by Reasoning over Multi-Video Haystacks

# 摘要

> 大型多模态模型（LMMs）在视听理解领域取得了显著进展，但面对需要跨大量视频进行复杂推理的真实场景时，它们的表现仍有提升空间。现有的视频问答基准通常局限于每个查询对应一个视频片段，难以反映大规模视听检索与推理的实际挑战。为此，我们推出全新任务 AV-HaystacksQA，旨在根据查询在多个视频中识别关键片段，并将其整合生成最具信息量的答案。为此，我们构建了包含 3100 个标注问答对的视听基准 AVHaystacks，专门用于评估 LMMs 在多视频检索与时间定位任务中的能力。同时，我们提出了一种模型不可知的多智能体框架 MAGNET，该框架在我们的 AVHaystacks 数据集上，相较于基线方法在问答任务中实现了 BLEU@4 和 GPT 评估得分分别高达 89% 和 65% 的相对提升。为了更 robust 地评估多视频检索与时间定位能力，从而优化响应生成，我们引入了两个新指标：STEM 用于捕捉地面真实与预测步骤序列的对齐误差，MTGS 则有助于实现对片段级定位性能的平衡与可解释评估。项目链接：https://schowdhury671.github.io/magnet_project/

> Large multimodal models (LMMs) have shown remarkable progress in audio-visual understanding, yet they struggle with real-world scenarios that require complex reasoning across extensive video collections. Existing benchmarks for video question answering remain limited in scope, typically involving one clip per query, which falls short of representing the challenges of large-scale, audio-visual retrieval and reasoning encountered in practical applications. To bridge this gap, we introduce a novel task named AV-HaystacksQA, where the goal is to identify salient segments across different videos in response to a query and link them together to generate the most informative answer. To this end, we present AVHaystacks, an audio-visual benchmark comprising 3100 annotated QA pairs designed to assess the capabilities of LMMs in multi-video retrieval and temporal grounding task. Additionally, we propose a model-agnostic, multi-agent framework MAGNET to address this challenge, achieving up to 89% and 65% relative improvements over baseline methods on BLEU@4 and GPT evaluation scores in QA task on our proposed AVHaystacks. To enable robust evaluation of multi-video retrieval and temporal grounding for optimal response generation, we introduce two new metrics, STEM, which captures alignment errors between a ground truth and a predicted step sequence and MTGS, to facilitate balanced and interpretable evaluation of segment-level grounding performance. Project: https://schowdhury671.github.io/magnet_project/

[Arxiv](https://arxiv.org/abs/2506.07016)