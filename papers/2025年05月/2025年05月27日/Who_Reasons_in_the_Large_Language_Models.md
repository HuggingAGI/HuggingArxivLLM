# 谁在大型语言模型中进行推理？探索模型内部的推理机制。

发布时间：2025年05月27日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）内部结构中推理能力的来源，特别是输出投影模块（oproj）的作用。研究者使用诊断工具SfN来分析模型内部行为，属于对LLM工作原理的理论研究，因此归类为LLM理论。` `计算机科学` `人工智能`

> Who Reasons in the Large Language Models?

# 摘要

> 尽管大型语言模型（LLMs）表现卓越，但赋予它们新能力——如数学推理——的过程仍充满神秘感。一个关键问题是：推理能力究竟源于整个模型、特定模块，还是仅仅是过拟合的产物？本研究提出，经过良好训练的LLMs的推理能力主要归功于Transformer多头自注意力机制中的输出投影模块（oproj）。为了验证这一假设，我们开发了Stethoscope for Networks（SfN），一套用于深入分析LLMs内部行为的诊断工具。通过SfN，我们发现：oproj在推理能力中扮演了核心角色，而其他模块则更多地贡献于流畅对话。这些发现不仅为理解LLM的可解释性提供了新视角，更为开发更高效、更专业的LLMs铺平了道路。

> Despite the impressive performance of large language models (LLMs), the process of endowing them with new capabilities--such as mathematical reasoning--remains largely empirical and opaque. A critical open question is whether reasoning abilities stem from the entire model, specific modules, or are merely artifacts of overfitting. In this work, we hypothesize that the reasoning capabilities in well-trained LLMs are primarily attributed to the output projection module (oproj) in the Transformer's multi-head self-attention (MHSA) mechanism. To support this hypothesis, we introduce Stethoscope for Networks (SfN), a suite of diagnostic tools designed to probe and analyze the internal behaviors of LLMs. Using SfN, we provide both circumstantial and empirical evidence suggesting that oproj plays a central role in enabling reasoning, whereas other modules contribute more to fluent dialogue. These findings offer a new perspective on LLM interpretability and open avenues for more targeted training strategies, potentially enabling more efficient and specialized LLMs.

[Arxiv](https://arxiv.org/abs/2505.20993)