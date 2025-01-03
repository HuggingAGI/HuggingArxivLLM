# 如何为大型语言模型的评估指标设定阈值

发布时间：2024年12月10日

`LLM应用

理由：这篇论文主要讨论了如何选择和确定大型语言模型（LLMs）评估指标的稳健阈值，以确保和监控LLMs的可靠性。论文提出了一种逐步选择LLM评估指标阈值的方法，并展示了该方法在Faithfulness指标上的应用。这些内容直接涉及到LLMs在实际应用中的评估和监控，因此应归类为“LLM应用”。` `人工智能`

> How to Choose a Threshold for an Evaluation Metric for Large Language Models

# 摘要

> 为了确保和监控大型语言模型（LLMs）的可靠性，文献中提出了多种评估指标。然而，尽管在LLMs部署中错误选择阈值会带来严重后果，但关于如何确定这些指标的稳健阈值的研究却寥寥无几。借鉴金融行业等受监管行业的传统模型风险管理（MRM）指南，我们提出了一种逐步选择LLM评估指标阈值的方法。我们强调，这种方法应从识别LLM应用的风险和利益相关者的风险承受能力开始。随后，我们提出了具体且统计严谨的程序，利用真实数据确定LLM评估指标的阈值。为了展示该方法的应用，我们将其应用于Faithfulness指标，该指标在多个公开库中实现，并使用公开的HaluBench数据集进行验证。我们还为系统化选择阈值奠定了基础，不仅适用于LLMs，也适用于任何生成式AI应用。

> To ensure and monitor large language models (LLMs) reliably, various evaluation metrics have been proposed in the literature. However, there is little research on prescribing a methodology to identify a robust threshold on these metrics even though there are many serious implications of an incorrect choice of the thresholds during deployment of the LLMs. Translating the traditional model risk management (MRM) guidelines within regulated industries such as the financial industry, we propose a step-by-step recipe for picking a threshold for a given LLM evaluation metric. We emphasize that such a methodology should start with identifying the risks of the LLM application under consideration and risk tolerance of the stakeholders. We then propose concrete and statistically rigorous procedures to determine a threshold for the given LLM evaluation metric using available ground-truth data. As a concrete example to demonstrate the proposed methodology at work, we employ it on the Faithfulness metric, as implemented in various publicly available libraries, using the publicly available HaluBench dataset. We also lay a foundation for creating systematic approaches to select thresholds, not only for LLMs but for any GenAI applications.

[Arxiv](https://arxiv.org/abs/2412.12148)