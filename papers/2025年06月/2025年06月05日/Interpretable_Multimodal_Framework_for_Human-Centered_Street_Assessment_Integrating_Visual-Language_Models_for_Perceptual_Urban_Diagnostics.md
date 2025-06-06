# 以人为核心的街道评估可解释多模态框架：整合视觉-语言模型用于感知城市诊断

发布时间：2025年06月05日

`LLM应用` `城市规划` `人工智能`

> Interpretable Multimodal Framework for Human-Centered Street Assessment: Integrating Visual-Language Models for Perceptual Urban Diagnostics

# 摘要

> 尽管基于图像或 GIS 的街景客观指标已成为城市分析的标准，但它们仍不足以捕捉到包容性城市设计中至关重要的主观感知。本研究提出了一种创新的多模态街景评估框架（MSEF），该框架融合了视觉 transformer（VisualGLM-6B）和大型语言模型（GPT-4），实现了对街景的可解释双输出评估。通过利用来自中国哈尔滨的 15,000 多张标注街景图像，我们采用 LoRA 和 P-Tuning v2 对框架进行微调，以实现参数高效适应。模型在客观特征上达到了 0.84 的 F1 分数，并与聚合后的居民感知达成 89.3% 的一致率，且在分层社会经济地理区域中得到验证。除了分类准确性，MSEF 还捕捉到依赖语境的矛盾：例如，非正式商业活动虽提升了感知活力，却同时降低了行人舒适度。它还识别出非线性和语义相关的模式——例如，建筑透明度在住宅区与商业区带来的感知效果大相径庭——揭示了普遍空间启发式的局限性。通过生成基于注意力机制的自然语言解释，该框架将感官数据与社会情感推理相结合，实现了与 SDG 11 目标相契合的透明诊断。这项研究不仅为城市感知建模提供了方法上的创新，也为寻求在基础设施精度与生活体验之间取得平衡的城市规划系统提供了实用价值。

> While objective street metrics derived from imagery or GIS have become standard in urban analytics, they remain insufficient to capture subjective perceptions essential to inclusive urban design. This study introduces a novel Multimodal Street Evaluation Framework (MSEF) that fuses a vision transformer (VisualGLM-6B) with a large language model (GPT-4), enabling interpretable dual-output assessment of streetscapes. Leveraging over 15,000 annotated street-view images from Harbin, China, we fine-tune the framework using LoRA and P-Tuning v2 for parameter-efficient adaptation. The model achieves an F1 score of 0.84 on objective features and 89.3 percent agreement with aggregated resident perceptions, validated across stratified socioeconomic geographies. Beyond classification accuracy, MSEF captures context-dependent contradictions: for instance, informal commerce boosts perceived vibrancy while simultaneously reducing pedestrian comfort. It also identifies nonlinear and semantically contingent patterns -- such as the divergent perceptual effects of architectural transparency across residential and commercial zones -- revealing the limits of universal spatial heuristics. By generating natural-language rationales grounded in attention mechanisms, the framework bridges sensory data with socio-affective inference, enabling transparent diagnostics aligned with SDG 11. This work offers both methodological innovation in urban perception modeling and practical utility for planning systems seeking to reconcile infrastructural precision with lived experience.

[Arxiv](https://arxiv.org/abs/2506.05087)