# # **Efficient Long CoT Reasoning in Small Language Models**  
高效长链式推理：小型语言模型的突破

发布时间：2025年05月23日

`LLM应用` `学术研究`

> Efficient Long CoT Reasoning in Small Language Models

# 摘要

> 近期的大型推理模型，如DeepSeek-R1，通过生成长链式思考（CoT）推理步骤展现出了强大的复杂问题解决能力。然而，直接训练小型语言模型（SLMs）以生成长链式思考推理步骤颇具挑战性。因此，蒸馏技术成为赋予SLMs此类推理能力的一种实用方法。然而，长链式思考推理步骤中常包含大量冗余内容（如过度思考步骤），这可能使SLMs难以学习，因为它们的容量和泛化能力相对有限。为了解决这一问题，我们提出了一种简单而有效的方法，用于修剪长链式思考推理步骤中的不必要的步骤，然后采用一种基于策略的方法，为SLMs整理有效且有用的长链式思考推理训练数据。通过这种方法，SLMs能够有效学习高效的长链式思考推理，并同时保持竞争力。在一系列数学推理基准测试中的实验结果证明，所提出的方法在将长链式思考推理能力蒸馏到SLMs方面是有效的，同时保持了竞争力，但显著减少了生成冗余推理步骤的情况。

> Recent large reasoning models such as DeepSeek-R1 exhibit strong complex problems solving abilities by generating long chain-of-thought (CoT) reasoning steps. It is challenging to directly train small language models (SLMs) to emerge long CoT. Thus, distillation becomes a practical method to enable SLMs for such reasoning ability. However, the long CoT often contains a lot of redundant contents (e.g., overthinking steps) which may make SLMs hard to learn considering their relatively poor capacity and generalization. To address this issue, we propose a simple-yet-effective method to prune unnecessary steps in long CoT, and then employ an on-policy method for the SLM itself to curate valid and useful long CoT training data. In this way, SLMs can effectively learn efficient long CoT reasoning and preserve competitive performance at the same time. Experimental results across a series of mathematical reasoning benchmarks demonstrate the effectiveness of the proposed method in distilling long CoT reasoning ability into SLMs which maintains the competitive performance but significantly reduces generating redundant reasoning steps.

[Arxiv](https://arxiv.org/abs/2505.18440)