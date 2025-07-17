# # 内部价值对齐：可控价值向量激活实现大型语言模型内部价值对齐

发布时间：2025年07月15日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）与人类价值观对齐，并提出了一种新的方法（ConVA）来实现这一目标。该方法通过解析LLMs在潜在表示中如何编码价值观，并调整相关激活，以直接对齐模型内部的价值观。同时，该研究设计了基于上下文控制的价值向量识别方法，并引入了门控价值向量激活方法，以实现持续的价值控制且不损害模型性能。这些内容属于LLM的应用层面，因此将其归类为LLM应用。` `人工智能伦理` `模型价值观对齐`

> Internal Value Alignment in Large Language Models through Controlled Value Vector Activation

# 摘要

> 将大型语言模型（LLMs）与人类价值观对齐近年来备受关注，因其具有清晰性、透明度和适应动态场景的能力。本文提出了一种可控价值向量激活（ConVA）方法，通过解析LLMs在潜在表示中如何编码价值观，并调整相关激活，以直接对齐模型内部的价值观。为确保准确无偏的解释，我们设计了基于上下文控制的价值向量识别方法。同时，为实现持续的价值控制且不损害模型性能，我们引入了门控价值向量激活方法，以最小干预实现有效控制。实验结果表明，ConVA在10个基本价值观上实现了最高控制成功率，且不会影响LLMs的性能和流畅度。即使面对相反甚至潜在恶意的输入提示，仍能确保目标价值观的实现。源代码和数据可在~ https://github.com/hr-jin/ConVA获取。

> Aligning Large Language Models (LLMs) with human values has attracted increasing attention since it provides clarity, transparency, and the ability to adapt to evolving scenarios. In this paper, we introduce a Controlled Value Vector Activation (ConVA) method that directly aligns the internal values of LLMs by interpreting how a value is encoded in their latent representations and modifies relevant activations to ensure consistent values in LLMs. To ensure an accurate and unbiased interpretation, we propose a context-controlled value vector identification method. To consistently control values without sacrificing model performance, we introduce a gated value vector activation method for effective and minimum degree of value control. Experiments show that our method achieves the highest control success rate across 10 basic values without hurting LLM performance and fluency, and ensures target values even with opposite and potentially malicious input prompts. Source code and data are available at~ https://github.com/hr-jin/ConVA.

[Arxiv](https://arxiv.org/abs/2507.11316)