# QuoTA：面向查询的标记分配方法，通过分解查询链式思维实现长视频理解

发布时间：2025年03月11日

`LLM应用` `视频处理` `跨模态学习`

> QuoTA: Query-oriented Token Assignment via CoT Query Decouple for Long Video Comprehension

# 摘要

> 长视频理解领域的最新进展主要通过基于注意力分布的视觉令牌剪枝来缓解视觉冗余问题。然而，现有方法虽然在解码器层采用了后处理低响应令牌剪枝，却忽视了视觉令牌与指令（查询）在输入层面的语义关联。本文提出了一种名为QuoTA的无训练模块，通过基于查询导向的帧级重要性评估扩展现有的大视频语言模型（LVLMs），实现视觉令牌分配。基于查询的令牌选择至关重要，因为它使视觉处理与特定任务要求保持一致，在优化令牌预算使用的同时保留语义相关的内容。具体而言，QuoTA具有以下三个特点：(i) 基于查询相关性战略性分配帧级重要性评分，在解码器层的跨模态交互之前实现一次性视觉令牌分配，(ii) 通过链式思维推理解耦查询，以便更精确地进行基于LVLM的帧重要性评分，(iii) 提供即插即用功能，可扩展至现有LVLMs。实验结果表明，将QuoTA与LLaVA-Video-7B结合使用，在六个基准测试（包括Video-MME和MLVU）中平均性能提升3.2%，同时在与基线相同的视觉令牌预算下运行。代码已开源，地址为https://github.com/MAC-AutoML/QuoTA。

> Recent advances in long video understanding typically mitigate visual redundancy through visual token pruning based on attention distribution. However, while existing methods employ post-hoc low-response token pruning in decoder layers, they overlook the input-level semantic correlation between visual tokens and instructions (query). In this paper, we propose QuoTA, an ante-hoc training-free modular that extends existing large video-language models (LVLMs) for visual token assignment based on query-oriented frame-level importance assessment. The query-oriented token selection is crucial as it aligns visual processing with task-specific requirements, optimizing token budget utilization while preserving semantically relevant content. Specifically, (i) QuoTA strategically allocates frame-level importance scores based on query relevance, enabling one-time visual token assignment before cross-modal interactions in decoder layers, (ii) we decouple the query through Chain-of-Thoughts reasoning to facilitate more precise LVLM-based frame importance scoring, and (iii) QuoTA offers a plug-and-play functionality that extends to existing LVLMs. Extensive experimental results demonstrate that implementing QuoTA with LLaVA-Video-7B yields an average performance improvement of 3.2% across six benchmarks (including Video-MME and MLVU) while operating within an identical visual token budget as the baseline. Codes are open-sourced at https://github.com/MAC-AutoML/QuoTA.

[Arxiv](https://arxiv.org/abs/2503.08689)