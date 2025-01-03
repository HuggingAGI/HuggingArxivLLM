# 感知、查询与推理：问题引导的时间查询提升视频问答效果

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在视频问答（Video QA）任务中的应用。论文提出了T-Former方法，旨在解决视频问答中的时空对齐问题，并充分利用MLLMs的视觉与文本对齐能力。这表明该研究属于LLM在实际应用中的探索和改进，因此应归类为“LLM应用”。` `视频分析` `问答系统`

> Perceive, Query & Reason: Enhancing Video QA with Question-Guided Temporal Queries

# 摘要

> # 视频问答（Video QA）
视频问答（Video QA）是一项极具挑战的任务，要求模型理解整个视频，根据问题上下文识别关键信息，并精准推理给出答案。多模态大型语言模型（MLLMs）凭借其强大的常识推理能力，彻底革新了这一领域。然而，视频问答中的时空对齐问题，尤其是跨帧提取相关信息，仍然是一个巨大挑战。本研究探索了多种时间建模技术与MLLMs的结合，旨在实现问题引导的时间建模，充分利用MLLMs中预训练的视觉与文本对齐。我们提出了T-Former，一种创新的时间建模方法，它在帧级视觉感知与LLMs推理能力之间架起了一座问题引导的桥梁。在多个视频问答基准测试中，T-Former表现优异，与现有方法媲美，并紧跟视频问答领域的最新进展。

> Video Question Answering (Video QA) is a challenging video understanding task that requires models to comprehend entire videos, identify the most relevant information based on contextual cues from a given question, and reason accurately to provide answers. Recent advancements in Multimodal Large Language Models (MLLMs) have transformed video QA by leveraging their exceptional commonsense reasoning capabilities. This progress is largely driven by the effective alignment between visual data and the language space of MLLMs. However, for video QA, an additional space-time alignment poses a considerable challenge for extracting question-relevant information across frames. In this work, we investigate diverse temporal modeling techniques to integrate with MLLMs, aiming to achieve question-guided temporal modeling that leverages pre-trained visual and textual alignment in MLLMs. We propose T-Former, a novel temporal modeling method that creates a question-guided temporal bridge between frame-wise visual perception and the reasoning capabilities of LLMs. Our evaluation across multiple video QA benchmarks demonstrates that T-Former competes favorably with existing temporal modeling approaches and aligns with recent advancements in video QA.

[Arxiv](https://arxiv.org/abs/2412.19304)