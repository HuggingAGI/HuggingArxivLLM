# # 通过LLM智能体和条件概念瓶颈模型提升图像分类的可解释性

发布时间：2025年06月02日

`LLM应用` `计算机视觉`

> Enhancing Interpretable Image Classification Through LLM Agents and Conditional Concept Bottleneck Models

# 摘要

> 概念瓶颈模型（CBMs）将图像分类过程分解为由可解释、可读性概念主导的步骤。近年来，CBMs领域通过利用大型语言模型（LLMs）生成候选概念取得了进展。然而，一个关键问题仍然存在：究竟应使用多少个概念才是最佳的？当前的概念库往往存在冗余或覆盖不足的问题。为了解决这一难题，我们提出了一种动态的基于代理的方法，该方法能够根据环境反馈调整概念库，以在保证足够覆盖的同时实现概念数量的简洁性。此外，我们还提出了条件概念瓶颈模型（CoCoBMs），以克服传统CBMs在概念评分机制上的局限性。该方法不仅提升了评估每个概念对分类任务贡献的准确性，还引入了一个可编辑矩阵，允许LLMs修正与其内部知识相冲突的概念评分。我们的实验结果表明，在6个数据集上，与传统方法相比，我们的方法不仅将分类准确率提升了6%，还将可解释性评估提升了30%。

> Concept Bottleneck Models (CBMs) decompose image classification into a process governed by interpretable, human-readable concepts. Recent advances in CBMs have used Large Language Models (LLMs) to generate candidate concepts. However, a critical question remains: What is the optimal number of concepts to use? Current concept banks suffer from redundancy or insufficient coverage. To address this issue, we introduce a dynamic, agent-based approach that adjusts the concept bank in response to environmental feedback, optimizing the number of concepts for sufficiency yet concise coverage. Moreover, we propose Conditional Concept Bottleneck Models (CoCoBMs) to overcome the limitations in traditional CBMs' concept scoring mechanisms. It enhances the accuracy of assessing each concept's contribution to classification tasks and feature an editable matrix that allows LLMs to correct concept scores that conflict with their internal knowledge. Our evaluations across 6 datasets show that our method not only improves classification accuracy by 6% but also enhances interpretability assessments by 30%.

[Arxiv](https://arxiv.org/abs/2506.01334)