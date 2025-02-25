# # PrivaCI-Bench：评估隐私时结合上下文完整性和法律合规性

发布时间：2025年02月24日

`LLM理论

摘要中提到的论文主要探讨了生成式大语言模型（LLMs）在隐私保护方面的评估和合规性，提出了一个新的评估基准PrivaCI-Bench，并研究了模型在隐私方面的表现。这属于对LLM的理论分析和评估，因此归类为LLM理论。` `隐私保护` `法律合规`

> PrivaCI-Bench: Evaluating Privacy with Contextual Integrity and Legal Compliance

# 摘要

> 生成式大语言模型（LLMs）的最新进展显著扩展了其应用范围、易用性和灵活性。然而，它们的可靠性和可信度，尤其是在个人数据隐私方面，仍然受到质疑。尽管在隐私保护方面，人们通过建立各种评估基准做出了巨大努力，以研究LLMs在生成输出到隐藏表示中的隐私感知和鲁棒性，但大多数工作仅关注个人身份信息（PII），采用了狭窄的隐私定义。在这篇论文中，我们遵循情境完整性（CI）理论的主张，即隐私评估不仅应涵盖传输的属性，还应通过私人信息流涵盖整个相关社会背景。为此，我们提出了PrivaCI-Bench——一个全面的情境隐私评估基准，旨在针对法律合规性，涵盖标注良好的隐私和安全法规、真实法院案例、隐私政策以及由官方工具包构建的合成数据，以研究LLMs的隐私和安全合规性。我们评估了包括最新推理模型QwQ-32B和Deepseek R1在内的最新LLMs。实验结果表明，尽管LLMs能够有效捕捉给定上下文中的关键CI参数，但它们仍需进一步发展以实现隐私合规。

> Recent advancements in generative large language models (LLMs) have enabled wider applicability, accessibility, and flexibility. However, their reliability and trustworthiness are still in doubt, especially for concerns regarding individuals' data privacy. Great efforts have been made on privacy by building various evaluation benchmarks to study LLMs' privacy awareness and robustness from their generated outputs to their hidden representations. Unfortunately, most of these works adopt a narrow formulation of privacy and only investigate personally identifiable information (PII). In this paper, we follow the merit of the Contextual Integrity (CI) theory, which posits that privacy evaluation should not only cover the transmitted attributes but also encompass the whole relevant social context through private information flows. We present PrivaCI-Bench, a comprehensive contextual privacy evaluation benchmark targeted at legal compliance to cover well-annotated privacy and safety regulations, real court cases, privacy policies, and synthetic data built from the official toolkit to study LLMs' privacy and safety compliance. We evaluate the latest LLMs, including the recent reasoner models QwQ-32B and Deepseek R1. Our experimental results suggest that though LLMs can effectively capture key CI parameters inside a given context, they still require further advancements for privacy compliance.

[Arxiv](https://arxiv.org/abs/2502.17041)