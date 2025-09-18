# # 从视觉视角深入探析大型视觉语言模型的幻觉缓解

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Diving into Mitigating Hallucinations from a Vision Perspective for Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）中的物体幻觉问题严重影响其实际应用价值。视觉编码器作为准确解析视觉信息的核心部件，其选型至关重要。我们推测，不同视觉编码器因采用多样化训练范式而形成独特的归纳偏差，这正是导致它们幻觉表现各异的原因。现有基准测试多聚焦于粗粒度幻觉检测，难以捕捉我们假设中所阐述的多样化幻觉现象。为系统分析这些影响，我们构建了VHBench-10——一个涵盖约10,000个样本的综合基准测试集，可在十个细粒度幻觉类别上对LVLMs进行评估。评估结果证实，不同编码器确实具有独特的幻觉特征。基于这些发现以及简单特征融合的局限性，我们提出VisionWeaver——一种全新的上下文感知路由网络。该网络利用全局视觉特征生成路由信号，动态聚合多个专业专家的视觉特征。大量实验证实，VisionWeaver能有效显著减少幻觉，同时提升模型整体性能。

> Object hallucination in Large Vision-Language Models (LVLMs) significantly impedes their real-world applicability. As the primary component for accurately interpreting visual information, the choice of visual encoder is pivotal. We hypothesize that the diverse training paradigms employed by different visual encoders instill them with distinct inductive biases, which leads to their diverse hallucination performances. Existing benchmarks typically focus on coarse-grained hallucination detection and fail to capture the diverse hallucinations elaborated in our hypothesis. To systematically analyze these effects, we introduce VHBench-10, a comprehensive benchmark with approximately 10,000 samples for evaluating LVLMs across ten fine-grained hallucination categories. Our evaluations confirm encoders exhibit unique hallucination characteristics. Building on these insights and the suboptimality of simple feature fusion, we propose VisionWeaver, a novel Context-Aware Routing Network. It employs global visual features to generate routing signals, dynamically aggregating visual features from multiple specialized experts. Comprehensive experiments confirm the effectiveness of VisionWeaver in significantly reducing hallucinations and improving overall model performance.

[Arxiv](https://arxiv.org/abs/2509.13836)