# 语言与视觉交汇于道路安全：运用多模态大语言模型进行视频交通事故分析

发布时间：2025年01月17日

`Agent

理由：这篇论文提出了一个名为SeeUnsafe的框架，该框架集成了多模态大语言模型（MLLM）代理，用于自动化视频交通事故分析。框架的核心是通过交互式对话模式来处理视频数据，这与传统的“提取-解释”流程不同。这种交互式对话模式依赖于MLLM代理的能力，使其能够自动化复杂任务并适应不同的交通场景和用户查询。因此，这篇论文主要关注的是如何利用代理（Agent）技术来改进视频分析流程，属于Agent分类。` `视频分析`

> When language and vision meet road safety: leveraging multimodal large language models for video-based traffic accident analysis

# 摘要

> # 摘要
随着24/7/365全天候交通视频的普及，其在提升交通事故时空覆盖范围方面展现出巨大潜力，有助于改善交通安全。然而，分析数百甚至数千个交通摄像头全天候录制的视频仍极具挑战，因为现有视觉方法主要聚焦于提取车辆轨迹或单个物体检测等原始信息，但需繁琐后处理才能获得可操作见解。我们提出SeeUnsafe框架，集成多模态大语言模型（MLLM）代理，将视频交通事故分析从传统的“提取-解释”流程转变为交互式对话模式。这一转变通过自动化视频分类和视觉定位等复杂任务，显著提升处理效率，同时通过无缝适应不同交通场景和用户查询，增强系统灵活性。框架采用基于严重性的聚合策略处理不同长度视频，并引入新颖多模态提示生成结构化响应，支持细粒度视觉定位。我们提出IMS（信息匹配分数），一种基于MLLM的新指标，用于对齐结构化响应与真实数据。在丰田Woven交通安全数据集上的大量实验表明，SeeUnsafe利用现成MLLM有效实现事故感知视频分类和视觉定位。源代码将在url{https://github.com/ai4ce/SeeUnsafe}提供。

> The increasing availability of traffic videos functioning on a 24/7/365 time scale has the great potential of increasing the spatio-temporal coverage of traffic accidents, which will help improve traffic safety. However, analyzing footage from hundreds, if not thousands, of traffic cameras in a 24/7/365 working protocol remains an extremely challenging task, as current vision-based approaches primarily focus on extracting raw information, such as vehicle trajectories or individual object detection, but require laborious post-processing to derive actionable insights. We propose SeeUnsafe, a new framework that integrates Multimodal Large Language Model (MLLM) agents to transform video-based traffic accident analysis from a traditional extraction-then-explanation workflow to a more interactive, conversational approach. This shift significantly enhances processing throughput by automating complex tasks like video classification and visual grounding, while improving adaptability by enabling seamless adjustments to diverse traffic scenarios and user-defined queries. Our framework employs a severity-based aggregation strategy to handle videos of various lengths and a novel multimodal prompt to generate structured responses for review and evaluation and enable fine-grained visual grounding. We introduce IMS (Information Matching Score), a new MLLM-based metric for aligning structured responses with ground truth. We conduct extensive experiments on the Toyota Woven Traffic Safety dataset, demonstrating that SeeUnsafe effectively performs accident-aware video classification and visual grounding by leveraging off-the-shelf MLLMs. Source code will be available at \url{https://github.com/ai4ce/SeeUnsafe}.

[Arxiv](https://arxiv.org/abs/2501.10604)