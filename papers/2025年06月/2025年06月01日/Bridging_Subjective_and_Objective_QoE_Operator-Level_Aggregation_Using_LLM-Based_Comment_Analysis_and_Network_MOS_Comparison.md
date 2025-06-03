# 连接主观与客观服务质量：运营商级聚合分析——基于大语言模型的评论分析与网络主观质量评分对比

发布时间：2025年06月01日

`LLM应用` `互联网服务`

> Bridging Subjective and Objective QoE: Operator-Level Aggregation Using LLM-Based Comment Analysis and Network MOS Comparison

# 摘要

> 本文提出了一种双层框架，用于网络侧用户体验质量（QoE）评估，结合了客观网络建模和主观用户感知分析。在客观层面，我们开发了一种基于平均意见得分（MOS）训练的机器学习模型，仅利用网络参数即可精准预测用户感知的视频质量。在主观层面，我们构建了一个语义过滤和评分管道，从直播用户评论中提取性能反馈，并使用大型语言模型为筛选后的评论分配 MOS 分数。我们创建了一个包含 47,894 条直播评论的数据集，其中约 34,000 条与 QoE 相关。每条评论均附加了模拟的互联网服务提供商归属信息和时间戳，支持运营商级别的性能聚合和时间序列分析。我们提出了一种 delta MOS 指标，用于衡量运营商与平台整体情绪的偏离，可检测局部性能下降。受控停播模拟验证了该框架通过评论趋势分析即可识别服务中断。该系统为每个运营商提供实时的主观 MOS 评分和对比分析，支持性能偏差的实时解释和对比。

> This paper introduces a dual-layer framework for network operator-side quality of experience (QoE) assessment that integrates both objective network modeling and subjective user perception extracted from live-streaming platforms. On the objective side, we develop a machine learning model trained on mean opinion scores (MOS) computed via the ITU-T P.1203 reference implementation, allowing accurate prediction of user-perceived video quality using only network parameters such as packet loss, delay, jitter, and throughput without reliance on video content or client-side instrumentation. On the subjective side, we present a semantic filtering and scoring pipeline that processes user comments from live streams to extract performance-related feedback. A large language model is used to assign scalar MOS scores to filtered comments in a deterministic and reproducible manner. To support scalable and interpretable analysis, we construct a labeled dataset of 47,894 live-stream comments, of which about 34,000 are identified as QoE-relevant through multi-layer semantic filtering. Each comment is enriched with simulated Internet Service Provider attribution and temporally aligned using synthetic timestamps in 5-min intervals. The resulting dataset enables operator-level aggregation and time-series analysis of user-perceived quality. A delta MOS metric is proposed to measure each Internet service provider's deviation from platform-wide sentiment, allowing detection of localized degradations even in the absence of direct network telemetry. A controlled outage simulation confirms the framework's effectiveness in identifying service disruptions through comment-based trends alone. The system provides each operator with its own subjective MOS and the global platform average per interval, enabling real-time interpretation of performance deviations and comparison with objective network-based QoE estimates.

[Arxiv](https://arxiv.org/abs/2506.00924)