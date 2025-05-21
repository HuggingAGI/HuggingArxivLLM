# 压缩视角：探讨量化对 LLM 可解释性与可理解性的影响

发布时间：2025年05月20日

`LLM应用` `人工智能`

> Through a Compressed Lens: Investigating the Impact of Quantization on LLM Explainability and Interpretability

# 摘要

> 量化方法广泛应用于加速大型语言模型（LLMs）推理并简化部署。尽管先前研究深入探讨了量化对LLM能力的降级影响，但其对模型可解释性和可理解性的影响仍未被探索。为填补这一空白，我们采用三种量化技术在不同位宽下，结合反事实示例、自然语言解释、知识记忆分析和潜在多跳推理分析，进行了全面实验。通过深入用户研究评估可解释性方法，发现量化对模型可解释性和可理解性有显著影响，且影响方向因量化方法、解释方法和评估协议而异。有时量化会降低可解释性，有时甚至带来改进。我们的研究揭示量化对模型透明度的不可预测影响，这对需要高透明度的LLM应用具有重要启示。

> Quantization methods are widely used to accelerate inference and streamline the deployment of large language models (LLMs). While prior research has extensively investigated the degradation of various LLM capabilities due to quantization, its effects on model explainability and interpretability, which are crucial for understanding decision-making processes, remain unexplored. To address this gap, we conduct comprehensive experiments using three common quantization techniques at distinct bit widths, in conjunction with two explainability methods, counterfactual examples and natural language explanations, as well as two interpretability approaches, knowledge memorization analysis and latent multi-hop reasoning analysis. We complement our analysis with a thorough user study, evaluating selected explainability methods. Our findings reveal that, depending on the configuration, quantization can significantly impact model explainability and interpretability. Notably, the direction of this effect is not consistent, as it strongly depends on (1) the quantization method, (2) the explainability or interpretability approach, and (3) the evaluation protocol. In some settings, human evaluation shows that quantization degrades explainability, while in others, it even leads to improvements. Our work serves as a cautionary tale, demonstrating that quantization can unpredictably affect model transparency. This insight has important implications for deploying LLMs in applications where transparency is a critical requirement.

[Arxiv](https://arxiv.org/abs/2505.13963)