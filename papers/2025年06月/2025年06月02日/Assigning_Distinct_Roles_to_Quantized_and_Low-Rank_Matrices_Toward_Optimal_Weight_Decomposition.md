# 探索量化矩阵与低秩矩阵的分工，实现最优权重分解

发布时间：2025年06月02日

`LLM理论` `人工智能`

> Assigning Distinct Roles to Quantized and Low-Rank Matrices Toward Optimal Weight Decomposition

# 摘要

> 将权重矩阵分解为量化和低秩组件（$\mathbf{W} pprox \mathbf{Q} + \mathbf{L}\mathbf{R}$）是压缩大型语言模型（LLMs）的重要技术。现有方法通过在量化和低秩近似之间交替优化，但往往顾此失彼，难以充分发挥各组件优势。我们提出基于异常值的低秩初始化方法（ODLRI），专为捕捉激活敏感权重设计。该方法通过结构化分解缓解异常值对量化的负面影响，实现量化与低秩近似的有效平衡。实验结果表明，ODLRI在Llama2（7B、13B、70B）、Llama3-8B和Mistral-7B上显著提升了压缩效果，在低比特设置下优化了模型性能。

> Decomposing weight matrices into quantization and low-rank components ($\mathbf{W} \approx \mathbf{Q} + \mathbf{L}\mathbf{R}$) is a widely used technique for compressing large language models (LLMs). Existing joint optimization methods iteratively alternate between quantization and low-rank approximation. However, these methods tend to prioritize one component at the expense of the other, resulting in suboptimal decompositions that fail to leverage each component's unique strengths. In this work, we introduce Outlier-Driven Low-Rank Initialization (ODLRI), which assigns low-rank components the specific role of capturing activation-sensitive weights. This structured decomposition mitigates outliers' negative impact on quantization, enabling more effective balance between quantization and low-rank approximation. Experiments on Llama2 (7B, 13B, 70B), Llama3-8B, and Mistral-7B demonstrate that incorporating ODLRI into the joint optimization framework consistently reduces activation-aware error, minimizes quantization scale, and improves perplexity and zero-shot accuracy in low-bit settings.

[Arxiv](https://arxiv.org/abs/2506.02077)