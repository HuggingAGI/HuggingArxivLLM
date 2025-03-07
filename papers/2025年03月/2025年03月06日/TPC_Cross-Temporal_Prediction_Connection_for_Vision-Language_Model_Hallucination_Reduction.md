# TPC：跨时间预测连接，助力减少视觉语言模型的幻觉

发布时间：2025年03月06日

`LLM应用`

> TPC: Cross-Temporal Prediction Connection for Vision-Language Model Hallucination Reduction

# 摘要

> 视觉语言模型（VLMs）在多种任务中取得了显著进展，但一个关键挑战依然存在：模型会过度自信地描述图像中并不存在的对象或属性，这种现象被称为幻觉。由于VLMs倾向于依赖语言先验，这一问题更加严重，从而降低了模型在高风险应用中的可靠性。在本研究中，我们发现了一种名为logits连续一致性增强的特性，并提出了一种简单高效的方法——跨时间步预测连接（TPC）。该方法通过在时间步之间建立联系，增强了logits的语义一致性。TPC不仅提升了信息流动，还增强了连贯性，从而有效减少了幻觉现象。大量实验表明，TPC超越了现有方法，在准确性和效率方面均表现出更优性能，同时在开放式的文本生成任务中保持了强大的鲁棒性。

> Vision-language models (VLMs) have achieved remarkable advancements, capitalizing on the impressive capabilities of large language models (LLMs) across diverse tasks. Despite this, a critical challenge known as hallucination occurs when models overconfidently describe objects or attributes absent from the image, a problem exacerbated by the tendency of VLMs to rely on linguistic priors. This limitation reduces model reliability in high-stakes applications. In this work, we have observed the characteristic of logits' continuity consistency enhancement and introduced a straightforward and efficient method, Cross-Temporal Prediction Connection (TPC), designed to enhance the semantic consistency of logits by connecting them temporally across timesteps. TPC amplifies information flow and improves coherence, effectively reducing hallucination. Extensive experiments show that TPC surpasses existing representatives, delivering superior performance in both accuracy and efficiency while maintaining robustness in open-ended text generation tasks.

[Arxiv](https://arxiv.org/abs/2503.04457)