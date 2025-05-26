# RAVEN: 基于查询引导的表示对齐，面向问答任务，涵盖音频、视频、嵌入式传感器与自然语言

发布时间：2025年05月21日

`LLM应用` `人工智能`

> RAVEN: Query-Guided Representation Alignment for Question Answering over Audio, Video, Embedded Sensors, and Natural Language

# 摘要

> 多模态问答系统（QA）在解答问题时，常常需要从视频、音频或传感器数据中精准识别出相关的信息片段。然而，由于模态之间的不一致，如离机语音、背景噪声或视野外的动作，那些对所有信息流同等加权的融合模型常常会被误导。我们提出了RAVEN，一种统一的QA架构，其核心是QuART模块——一个基于查询的跨模态门控机制。QuART能够为各模态的每个信息片段分配相关性评分，从而在融合前增强关键信息并抑制干扰因素。RAVEN的训练采用三阶段pipeline：单模态预训练、查询对齐融合和分歧导向微调，分别针对多模态推理中的三大挑战——表示质量、跨模态相关性和模态不匹配的鲁棒性。为了支持研究，我们发布了AVS-QA数据集，包含30万对同步的音频-视频-传感器流，并自动配对了问题-答案对。在包括自中心和他中心任务在内的七个跨模态QA基准测试中，RAVEN的表现超越了当前最优的多模态大语言模型，准确率分别提升了14.5%和8.0%。整合传感器数据更是带来了额外16.4%的性能提升，且在模态损坏的情况下，RAVEN依然表现出强大的鲁棒性，高出SOTA基线50.23%。我们的代码和数据集已开源，地址为https://github.com/BASHLab/RAVEN。

> Multimodal question answering (QA) often requires identifying which video, audio, or sensor tokens are relevant to the question. Yet modality disagreements are common: off-camera speech, background noise, or motion outside the field of view often mislead fusion models that weight all streams equally. We present RAVEN, a unified QA architecture whose core is QuART, a query-conditioned cross-modal gating module that assigns scalar relevance scores to each token across modalities, enabling the model to amplify informative signals and suppress distractors before fusion. RAVEN is trained through a three-stage pipeline comprising unimodal pretraining, query-aligned fusion, and disagreement-oriented fine-tuning -- each stage targeting a distinct challenge in multi-modal reasoning: representation quality, cross-modal relevance, and robustness to modality mismatch. To support training and evaluation, we release AVS-QA, a dataset of 300K synchronized Audio--Video-Sensor streams paired with automatically generated question-answer pairs. Experimental results on seven multi-modal QA benchmarks -- including egocentric and exocentric tasks -- show that RAVEN achieves up to 14.5\% and 8.0\% gains in accuracy compared to state-of-the-art multi-modal large language models, respectively. Incorporating sensor data provides an additional 16.4\% boost, and the model remains robust under modality corruption, outperforming SOTA baselines by 50.23\%. Our code and dataset are available at https://github.com/BASHLab/RAVEN.

[Arxiv](https://arxiv.org/abs/2505.17114)