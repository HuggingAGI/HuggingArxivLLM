# 利用半非负矩阵分解解析MLP激活，提取可解释特征

发布时间：2025年06月12日

`LLM理论` `人工智能` `神经网络`

> Decomposing MLP Activations into Interpretable Features via Semi-Nonnegative Matrix Factorization

# 摘要

> 机制可解释性研究的核心目标是识别大型语言模型（LLMs）中能够因果解释其输出的正确分析单元。早期研究集中于单个神经元，但神经元往往编码多个概念这一事实促使研究转向分析激活空间中的方向。一个关键问题是，如何以无监督的方式发现能够捕捉可解释特征的方向。当前方法依赖于基于稀疏自动编码器（SAEs）的字典学习，通常在残差流激活上进行训练以从头学习方向。然而，SAEs在因果评估中常常表现不佳，且缺乏内在可解释性，因为其学习过程并未与模型的计算明确关联。在这里，我们通过直接利用半非负矩阵分解（SNMF）分解MLP的激活来克服这些限制，使得所学特征（a）是共激活神经元的稀疏线性组合，并且（b）能够映射到其激活输入，从而实现直接可解释性。在Llama 3.1、Gemma 2和GPT-2上的实验表明，基于SNMF的特征在因果引导方面优于SAEs和强大的监督基线（差异均值），同时与人类可解释的概念相一致。进一步分析揭示，特定神经元组合在语义相关的特征之间被重复使用，揭示了MLP激活空间中存在层次结构。综上所述，这些结果将SNMF定位为一种简单而有效的工具，用于识别可解释特征和剖析LLMs中的概念表示。

> A central goal for mechanistic interpretability has been to identify the right units of analysis in large language models (LLMs) that causally explain their outputs. While early work focused on individual neurons, evidence that neurons often encode multiple concepts has motivated a shift toward analyzing directions in activation space. A key question is how to find directions that capture interpretable features in an unsupervised manner. Current methods rely on dictionary learning with sparse autoencoders (SAEs), commonly trained over residual stream activations to learn directions from scratch. However, SAEs often struggle in causal evaluations and lack intrinsic interpretability, as their learning is not explicitly tied to the computations of the model. Here, we tackle these limitations by directly decomposing MLP activations with semi-nonnegative matrix factorization (SNMF), such that the learned features are (a) sparse linear combinations of co-activated neurons, and (b) mapped to their activating inputs, making them directly interpretable. Experiments on Llama 3.1, Gemma 2 and GPT-2 show that SNMF derived features outperform SAEs and a strong supervised baseline (difference-in-means) on causal steering, while aligning with human-interpretable concepts. Further analysis reveals that specific neuron combinations are reused across semantically-related features, exposing a hierarchical structure in the MLP's activation space. Together, these results position SNMF as a simple and effective tool for identifying interpretable features and dissecting concept representations in LLMs.

[Arxiv](https://arxiv.org/abs/2506.10920)