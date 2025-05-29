# 多模态推理模型中的放大幻觉：思考与观察的平衡探讨

发布时间：2025年05月23日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型在推理任务中的应用，特别是幻觉风险和模型的注意力机制。研究引入了新的评估指标和基准，分析了模型在实际任务中的表现，属于应用层面的研究。` `多模态` `模型评估`

> More Thinking, Less Seeing? Assessing Amplified Hallucination in Multimodal Reasoning Models

# 摘要

> 测试时计算使多模态大型语言模型能够生成更长的推理链，从而在多模态数学推理等任务中表现出色。然而，这种增强的推理能力通常伴随着更高的幻觉风险：随着生成内容的延长，模型往往偏离基于图像的内容，更多依赖语言先验。注意力分析表明，更长的推理链导致对视觉输入的关注减少，从而导致幻觉。为了系统研究这一现象，我们引入RH-AUC指标，用于量化模型感知准确性随推理长度的变化，从而评估模型在推理过程中是否保持视觉基础。我们还发布了RH-Bench，这是一个涵盖多种多模态任务的诊断基准，旨在评估推理能力和幻觉之间的权衡。分析揭示了两点：(i) 更大的模型通常在推理与感知之间取得更好的平衡，(ii) 这种平衡更多受到训练数据类型和领域的影响，而非整体数据量。这些发现强调了同时考虑推理质量和感知保真度的评估框架的重要性。

> Test-time compute has empowered multimodal large language models to generate extended reasoning chains, yielding strong performance on tasks such as multimodal math reasoning. However, this improved reasoning ability often comes with increased hallucination: as generations become longer, models tend to drift away from image-grounded content and rely more heavily on language priors. Attention analysis shows that longer reasoning chains lead to reduced focus on visual inputs, which contributes to hallucination. To systematically study this phenomenon, we introduce RH-AUC, a metric that quantifies how a model's perception accuracy changes with reasoning length, allowing us to evaluate whether the model preserves visual grounding during reasoning. We also release RH-Bench, a diagnostic benchmark that spans a variety of multimodal tasks, designed to assess the trade-off between reasoning ability and hallucination. Our analysis reveals that (i) larger models typically achieve a better balance between reasoning and perception, and (ii) this balance is influenced more by the types and domains of training data than by its overall volume. These findings underscore the importance of evaluation frameworks that jointly consider both reasoning quality and perceptual fidelity.

[Arxiv](https://arxiv.org/abs/2505.21523)