# CircuitProbe：通过电路追踪解析时空视觉语义

发布时间：2025年07月25日

`其他` `人工智能` `计算机视觉`

> CircuitProbe: Dissecting Spatiotemporal Visual Semantics with Circuit Tracing

# 摘要

> 尽管大型视觉语言模型（LVLMs）在语言和图像理解方面的处理机制已被广泛研究，但其在时空理解方面的内部推理机制仍是一个未解之谜。为此，我们提出了一种系统化的电路框架，深入探究时空视觉语义在LVLMs中的表征与处理过程。我们的框架由三个核心电路组成：视觉审核电路、语义追踪电路以及注意力流电路。通过这三重电路的视角，我们发现视觉语义高度集中于特定的对象标记——移除这些标记可能导致模型性能下降高达92.6%。此外，我们还发现，物体与动作的可解释概念在LVLMs的中后层逐渐浮现并不断精炼。与当前仅关注单张图像中物体的研究不同，我们揭示了LVLMs的中后层在时空语义理解方面表现出专门的功能定位。这些发现为理解LVLMs的时空语义分析提供了重要的机制性见解，为设计更加健壮和可解释的模型奠定了基础。

> The processing mechanisms underlying language and image understanding in large vision-language models (LVLMs) have been extensively studied. However, the internal reasoning mechanisms of LVLMs for spatiotemporal understanding remain poorly understood. In this work, we introduce a systematic, circuit-based framework designed to investigate how spatiotemporal visual semantics are represented and processed within these LVLMs. Specifically, our framework comprises three circuits: visual auditing circuit, semantic tracing circuit, and attention flow circuit. Through the lens of these circuits, we discover that visual semantics are highly localized to specific object tokens--removing these tokens can degrade model performance by up to 92.6%. Furthermore, we identify that interpretable concepts of objects and actions emerge and become progressively refined in the middle-to-late layers of LVLMs. In contrary to the current works that solely focus on objects in one image, we reveal that the middle-to-late layers of LVLMs exhibit specialized functional localization for spatiotemporal semantics. Our findings offer significant mechanistic insights into spatiotemporal semantics analysis of LVLMs, laying a foundation for designing more robust and interpretable models.

[Arxiv](https://arxiv.org/abs/2507.19420)