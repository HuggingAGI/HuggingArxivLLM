# 精度降低反而更可靠？——一项超越准确性的量化对CLIP影响系统性评估

发布时间：2025年09月25日

`LLM应用` `基础理论`

> Can Less Precise Be More Reliable? A Systematic Evaluation of Quantization's Impact on CLIP Beyond Accuracy

# 摘要

> CLIP等视觉语言模型（VLMs）凭借强大的零样本泛化能力，为分布外（OOD）检测等安全相关任务开辟了全新范式。然而，在CLIP的高效计算与可靠部署中，一些关键问题仍未得到足够关注。尤其是，量化对CLIP性能的影响——除了准确率之外——尚未得到深入研究。本研究对CLIP模型的量化展开大规模评估，不仅考察了分布内准确率，还评估了一整套可靠性指标，进而揭示了由预训练数据来源引发的反直觉结果。我们发现，量化能持续提升通常信心不足的预训练模型的校准效果，却常常会削弱过度自信模型变体的校准表现。有趣的是，尽管校准有所下降，其他可靠性指标仍可能提升；我们观察到，即便是这些校准不佳的模型，其OOD检测性能依然可以改善。此外，我们还找到了特定的量化感知训练（QAT）方法，可同时提升零样本准确率、校准效果及OOD鲁棒性，这对“效率与性能不可兼得”的固有认知提出了挑战。这些发现为解决高效、可靠、鲁棒的VLMs部署这一多目标难题提供了关键思路，其核心在于让量化发挥超越传统的作用。

> The powerful zero-shot generalization capabilities of vision-language models (VLMs) like CLIP have enabled new paradigms for safety-related tasks such as out-of-distribution (OOD) detection. However, additional aspects crucial for the computationally efficient and reliable deployment of CLIP are still overlooked. In particular, the impact of quantization on CLIP's performance beyond accuracy remains underexplored. This work presents a large-scale evaluation of quantization on CLIP models, assessing not only in-distribution accuracy but a comprehensive suite of reliability metrics and revealing counterintuitive results driven by pre-training source. We demonstrate that quantization consistently improves calibration for typically underconfident pre-trained models, while often degrading it for overconfident variants. Intriguingly, this degradation in calibration does not preclude gains in other reliability metrics; we find that OOD detection can still improve for these same poorly calibrated models. Furthermore, we identify specific quantization-aware training (QAT) methods that yield simultaneous gains in zero-shot accuracy, calibration, and OOD robustness, challenging the view of a strict efficiency-performance trade-off. These findings offer critical insights for navigating the multi-objective problem of deploying efficient, reliable, and robust VLMs by utilizing quantization beyond its conventional role.

[Arxiv](https://arxiv.org/abs/2509.21173)