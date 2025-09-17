# ChartGaze：基于眼动追踪引导的注意力优化提升LVLMs的图表理解能力

发布时间：2025年09月16日

`LLM应用` `基础理论`

> ChartGaze: Enhancing Chart Understanding in LVLMs with Eye-Tracking Guided Attention Refinement

# 摘要

> 图表是传递与呈现信息的重要视觉媒介。尽管大型视觉语言模型（LVLMs）在图表问答（CQA）任务上已有突破，但该任务仍颇具挑战——尤其是当模型将注意力投向图表无关区域时。为此，我们提出了全新的眼动追踪数据集ChartGaze，专门捕捉人类在图表推理过程中的注视规律。通过系统对比人类与模型的注意力分布，我们发现LVLMs的关注点常与人类注视偏离，进而降低了模型的可解释性与准确性。针对这一问题，我们提出注视引导的注意力优化策略，使图文注意力与人类注视点精准对齐。该方法不仅提升了答案准确率，还改善了注意力对齐效果，在多个模型上实现了最高2.56个百分点的性能增益。这些结果表明，融入人类注视有望同时提升专注于图表的LVLMs的推理质量与可解释性。

> Charts are a crucial visual medium for communicating and representing information. While Large Vision-Language Models (LVLMs) have made progress on chart question answering (CQA), the task remains challenging, particularly when models attend to irrelevant regions of the chart. In this work, we present ChartGaze, a new eye-tracking dataset that captures human gaze patterns during chart reasoning tasks. Through a systematic comparison of human and model attention, we find that LVLMs often diverge from human gaze, leading to reduced interpretability and accuracy. To address this, we propose a gaze-guided attention refinement that aligns image-text attention with human fixations. Our approach improves both answer accuracy and attention alignment, yielding gains of up to 2.56 percentage points across multiple models. These results demonstrate the promise of incorporating human gaze to enhance both the reasoning quality and interpretability of chart-focused LVLMs.

[Arxiv](https://arxiv.org/abs/2509.13282)