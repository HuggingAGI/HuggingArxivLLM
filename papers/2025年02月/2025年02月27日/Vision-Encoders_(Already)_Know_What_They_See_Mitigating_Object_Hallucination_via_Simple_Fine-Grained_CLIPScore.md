# 视觉编码器“已知”所见：简单细粒度CLIPScore缓解物体幻觉

发布时间：2025年02月27日

`LLM应用` `计算机视觉`

> Vision-Encoders (Already) Know What They See: Mitigating Object Hallucination via Simple Fine-Grained CLIPScore

# 摘要

> 近年来，大型视觉-语言模型（LVLMs）在多个领域展现了卓越的性能。然而，这些模型存在物体幻觉的问题。我们重新审视了先前关于这种幻觉主要源于视觉编码器表示能力有限的观点，并发现视觉编码器本身的容量已经足以检测物体幻觉。基于这一发现，我们提出了一种细粒度CLIPScore（F-CLIPScore），这是一种简单而有效的评估指标，通过在名词短语级别引入文本嵌入来增强物体级别的粒度。在OHD-Caps基准上的评估表明，F-CLIPScore在准确性上比传统CLIPScore高出39.6%的显著优势，且无需额外训练。我们进一步通过实验证明，使用F-CLIPScore过滤数据进行训练的LVLM表现出幻觉减少的特性。

> Recently, Large Vision-Language Models (LVLMs) show remarkable performance across various domains. However, these models suffer from object hallucination. This study revisits the previous claim that the primary cause of such hallucination lies in the limited representational capacity of the vision encoder. Our analysis reveals that the capacity of the vision encoder itself is already enough for detecting object hallucination. Based on this insight, we propose a Fine-grained CLIPScore (F-CLIPScore), a simple yet effective evaluation metric that enhances object-level granularity by incorporating text embeddings at the noun phrase level. Evaluations on the OHD-Caps benchmark show that F-CLIPScore significantly outperforms conventional CLIPScore in accuracy by a large margin of 39.6% without additional training. We further validate F-CLIPScore by showing that LVLM trained with the data filtered using F-CLIPScore exhibits reduced hallucination.

[Arxiv](https://arxiv.org/abs/2502.20034)