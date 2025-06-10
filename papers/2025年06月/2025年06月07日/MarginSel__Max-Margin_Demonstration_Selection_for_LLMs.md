# MarginSel：大型语言模型的最优边缘范例选择方案

发布时间：2025年06月07日

`LLM理论` `大型语言模型`

> MarginSel : Max-Margin Demonstration Selection for LLMs

# 摘要

> 大型语言模型 (LLMs) 在通过上下文学习 (ICL) 进行少量样本学习方面表现优异。然而，ICL 的效果往往受到演示示例选择和排序的影响。为此，我们提出 MarginSel：一种针对 LLMs 的最大间隔演示示例选择方法。该方法通过两步流程，为 ICL 提示选择困难的演示示例，并根据每个测试实例进行调整。与随机选择示例相比，我们的方法在分类任务中实现了 F1 分数 2-7% 的绝对提升。我们还提供了理论见解和实证证据，表明 MarginSel 通过有效增加困难示例的间隔（类似于支持向量），在 LLMs 中诱导出最大间隔行为，从而将决策边界向有益的方向移动。

> Large Language Models (LLMs) excel at few-shot learning via in-context learning (ICL). However, the effectiveness of ICL is often sensitive to the selection and ordering of demonstration examples. To address this, we present MarginSel: Max-Margin Demonstration Selection for LLMs, a two-step method that selects hard demonstration examples for the ICL prompt, adapting to each test instance. Our approach achieves 2-7% absolute improvement in F1-score across classification tasks, compared to a random selection of examples. We also provide theoretical insights and empirical evidence showing that MarginSel induces max-margin behavior in LLMs by effectively increasing the margin for hard examples, analogous to support vectors, thereby shifting the decision boundary in a beneficial direction.

[Arxiv](https://arxiv.org/abs/2506.06699)