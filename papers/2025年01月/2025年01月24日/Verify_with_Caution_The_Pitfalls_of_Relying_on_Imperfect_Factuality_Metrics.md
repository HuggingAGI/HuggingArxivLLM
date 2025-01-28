# 小心验证：依赖不完美事实性指标的潜在风险

发布时间：2025年01月24日

`LLM理论

理由：这篇论文主要探讨了大型语言模型在自然语言生成输出评估中的局限性，特别是对真实性指标的重新评估。这涉及到对LLM的理论理解和评估方法的批判性分析，属于对LLM理论的研究范畴。` `评估系统`

> Verify with Caution: The Pitfalls of Relying on Imperfect Factuality Metrics

# 摘要

> 大型语言模型的进步让人们对其作为自然语言生成输出的可靠评估者充满期待。然而，本文通过对11个数据集上的五种顶尖真实性指标的全面重新评估，揭示了这种乐观的局限性。这些数据集涉及摘要、检索增强生成和问答任务。我们发现，这些评估者之间缺乏一致性，且常常误判系统性能，可能导致多种问题。此外，这些指标对高度改写的输出和依赖源文档较远部分的输出存在偏见。因此，我们建议用户在使用这些真实性指标时保持谨慎，并在应用前手动验证其在自己领域的可靠性。

> Improvements in large language models have led to increasing optimism that they can serve as reliable evaluators of natural language generation outputs. In this paper, we challenge this optimism by thoroughly re-evaluating five state-of-the-art factuality metrics on a collection of 11 datasets for summarization, retrieval-augmented generation, and question answering. We find that these evaluators are inconsistent with each other and often misestimate system-level performance, both of which can lead to a variety of pitfalls. We further show that these metrics exhibit biases against highly paraphrased outputs and outputs that draw upon faraway parts of the source documents. We urge users of these factuality metrics to proceed with caution and manually validate the reliability of these metrics in their domain of interest before proceeding.

[Arxiv](https://arxiv.org/abs/2501.14883)