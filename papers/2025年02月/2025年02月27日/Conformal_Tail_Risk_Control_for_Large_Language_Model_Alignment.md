# # 大型语言模型对齐的一致性尾部风险控制

发布时间：2025年02月27日

`LLM理论` `风险评估` `模型校准`

> Conformal Tail Risk Control for Large Language Model Alignment

# 摘要

> 大型语言模型（LLMs）的最新进展已使其在各类任务中得到广泛应用。其在社会中的普及促使我们对模型性能的可靠性给予更多关注。特别是在风险敏感型应用中，我们需要对意外的不良结果（即尾部事件）给予细致关注，例如毒性回答、令人尴尬的语言以及冒犯性输出等。由于获取人工标注的成本较高，通用评分模型应运而生，旨在自动化量化这些尾部事件。这一现象可能导致人类与机器在各自的评分机制之间出现潜在的不一致。在此研究中，我们提出了一种针对黑盒模型的轻量级校准框架，该框架能够确保人类与机器之间的评分机制达到一致，并提供可证明的保证。我们的框架提供了一种严谨的方法，用于控制任何失真风险度量，这些度量由LLM所造成损失的分位数的加权平均值表征，并且在高置信度下进行。我们的方法的理论基础建立在符合性风险控制与统计学中一个传统家族（即L-统计量）之间的联系上。为了展示我们框架的实用性，我们进行了全面的实验，以解决人类与机器之间的不一致问题。

> Recent developments in large language models (LLMs) have led to their widespread usage for various tasks. The prevalence of LLMs in society implores the assurance on the reliability of their performance. In particular, risk-sensitive applications demand meticulous attention to unexpectedly poor outcomes, i.e., tail events, for instance, toxic answers, humiliating language, and offensive outputs. Due to the costly nature of acquiring human annotations, general-purpose scoring models have been created to automate the process of quantifying these tail events. This phenomenon introduces potential human-machine misalignment between the respective scoring mechanisms. In this work, we present a lightweight calibration framework for blackbox models that ensures the alignment of humans and machines with provable guarantees. Our framework provides a rigorous approach to controlling any distortion risk measure that is characterized by a weighted average of quantiles of the loss incurred by the LLM with high confidence. The theoretical foundation of our method relies on the connection between conformal risk control and a traditional family of statistics, i.e., L-statistics. To demonstrate the utility of our framework, we conduct comprehensive experiments that address the issue of human-machine misalignment.

[Arxiv](https://arxiv.org/abs/2502.20285)