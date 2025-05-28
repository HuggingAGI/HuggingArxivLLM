# MUSEG：利用时间戳感知多片段定位提升视频时序理解能力

发布时间：2025年05月27日

`LLM应用` `视频分析` `人工智能`

> MUSEG: Reinforcing Video Temporal Understanding via Timestamp-Aware Multi-Segment Grounding

# 摘要

> 视频时间理解能力对于多模态大语言模型（MLLMs）在视频中进行事件推理至关重要。尽管通用视频理解领域取得了进展，但MLLMs在细粒度时间推理方面仍面临挑战。近期虽然尝试用强化学习（RL）来解决这一问题，但现有RL方法的效果仍显不足。为此，我们提出了MUSEG——一种基于RL的创新方法，通过引入时间戳感知的多片段定位，显著提升了时间理解能力。MUSEG使MLLMs能够将查询与多个相关视频片段精准对齐，从而实现更全面的时间推理。为促进有效学习，我们设计了一套定制的RL训练方案，采用分阶段奖励机制，逐步引导模型向时间定位推理方向优化。在时间定位和时间敏感的视频问答任务上的大量实验表明，MUSEG不仅显著超越现有方法，还在各种时间理解场景中展现出卓越的泛化能力。访问我们的项目页面：https://github.com/THUNLP-MT/MUSEG。


> Video temporal understanding is crucial for multimodal large language models (MLLMs) to reason over events in videos. Despite recent advances in general video understanding, current MLLMs still struggle with fine-grained temporal reasoning. While reinforcement learning (RL) has been explored to address this issue recently, existing RL approaches remain limited in effectiveness. In this work, we propose MUSEG, a novel RL-based method that enhances temporal understanding by introducing timestamp-aware multi-segment grounding. MUSEG enables MLLMs to align queries with multiple relevant video segments, promoting more comprehensive temporal reasoning. To facilitate effective learning, we design a customized RL training recipe with phased rewards that progressively guides the model toward temporally grounded reasoning. Extensive experiments on temporal grounding and time-sensitive video QA tasks demonstrate that MUSEG significantly outperforms existing methods and generalizes well across diverse temporal understanding scenarios. View our project at https://github.com/THUNLP-MT/MUSEG.

[Arxiv](https://arxiv.org/abs/2505.20715)