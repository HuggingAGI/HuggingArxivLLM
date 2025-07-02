# 因果提示在大型语言模型中的隐式情感分析应用

发布时间：2025年06月30日

`LLM理论` `情感分析`

> Causal Prompting for Implicit Sentiment Analysis with Large Language Models

# 摘要

> 隐式情感分析（ISA）旨在通过微妙的上下文线索推断未明确表达的情感，要求模型进行更深层次的推理。尽管基于提示的大型语言模型（LLMs）在ISA方面显示出潜力，但它们通常依赖于对思维链（CoT）推理路径进行多数投票，而没有评估其因果有效性，这使得它们容易受到内部偏见和虚假相关性的影响。为了解决这一挑战，我们提出了CAPITAL，一个将前门调整纳入CoT推理的因果提示框架。CAPITAL将整体因果效应分解为两个部分：输入提示对推理链的影响，以及这些链对最终输出的影响。这些部分通过基于编码器的聚类和NWGM近似进行估计，并使用对比学习目标使编码器的表示更好地与LLM的推理空间对齐。在三个LLMs上的基准ISA数据集上的实验表明，CAPITAL在准确性和鲁棒性方面始终优于强大的提示基线，特别是在对抗条件下。这项工作为将因果推断整合到LLM提示中提供了一个原则化的方法，并强调了其对有偏见意识的情感推理的好处。源代码和案例研究可在以下链接获取：https://github.com/whZ62/CAPITAL。


> Implicit Sentiment Analysis (ISA) aims to infer sentiment that is implied rather than explicitly stated, requiring models to perform deeper reasoning over subtle contextual cues. While recent prompting-based methods using Large Language Models (LLMs) have shown promise in ISA, they often rely on majority voting over chain-of-thought (CoT) reasoning paths without evaluating their causal validity, making them susceptible to internal biases and spurious correlations. To address this challenge, we propose CAPITAL, a causal prompting framework that incorporates front-door adjustment into CoT reasoning. CAPITAL decomposes the overall causal effect into two components: the influence of the input prompt on the reasoning chains, and the impact of those chains on the final output. These components are estimated using encoder-based clustering and the NWGM approximation, with a contrastive learning objective used to better align the encoder's representation with the LLM's reasoning space. Experiments on benchmark ISA datasets with three LLMs demonstrate that CAPITAL consistently outperforms strong prompting baselines in both accuracy and robustness, particularly under adversarial conditions. This work offers a principled approach to integrating causal inference into LLM prompting and highlights its benefits for bias-aware sentiment reasoning. The source code and case study are available at: https://github.com/whZ62/CAPITAL.

[Arxiv](https://arxiv.org/abs/2507.00389)