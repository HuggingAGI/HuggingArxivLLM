# CAMA：利用因果知识提升大型语言模型的数学推理能力

发布时间：2025年08月04日

`LLM应用`

> CAMA: Enhancing Mathematical Reasoning in Large Language Models with Causal Knowledge

# 摘要

> 大型语言模型（LLMs）在广泛的任务中表现出色，但在复杂数学推理方面仍然存在困难，这一挑战的根本原因在于深层次的结构依赖。为了解决这一挑战，我们提出了因果数学家（CAMA），这是一个两阶段的因果框架，为LLMs配备了明确且可重用的数学结构。在学习阶段，CAMA结合LLMs的先验知识和因果发现算法，从问题-解答对的语料库中构建数学因果图（MCG），这是解决方案策略的高层表示。生成的MCG编码了关键的知识点及其因果依赖关系。为了使图更好地与下游推理任务对齐，CAMA通过从问题-解答对的子集中迭代反馈进一步优化MCG。在推理阶段，给定一个新的问题，CAMA根据问题内容和LLMs的中间推理轨迹，从MCG中动态提取与任务相关的子图。这个子图编码了最相关的关键知识点及其因果依赖关系，并将其重新注入到LLMs中，以引导其推理过程。实证结果表明，CAMA显著提升了LLMs在具有挑战性的数学问题上的性能。此外，我们的实验表明，结构化指导始终优于非结构化替代方案，而引入非对称因果关系比单独使用对称关联能带来更大的改进。

> Large Language Models (LLMs) have demonstrated strong performance across a wide range of tasks, yet they still struggle with complex mathematical reasoning, a challenge fundamentally rooted in deep structural dependencies. To address this challenge, we propose \textbf{CA}usal \textbf{MA}thematician (\textbf{CAMA}), a two-stage causal framework that equips LLMs with explicit, reusable mathematical structure. In the learning stage, CAMA first constructs the \textbf{M}athematical \textbf{C}ausal \textbf{G}raph (\textbf{MCG}), a high-level representation of solution strategies, by combining LLM priors with causal discovery algorithms applied to a corpus of question-solution pairs. The resulting MCG encodes essential knowledge points and their causal dependencies. To better align the graph with downstream reasoning tasks, CAMA further refines the MCG through iterative feedback derived from a selected subset of the question-solution pairs. In the reasoning stage, given a new question, CAMA dynamically extracts a task-relevant subgraph from the MCG, conditioned on both the question content and the LLM's intermediate reasoning trace. This subgraph, which encodes the most pertinent knowledge points and their causal dependencies, is then injected back into the LLM to guide its reasoning process. Empirical results on real-world datasets show that CAMA significantly improves LLM performance on challenging mathematical problems. Furthermore, our experiments demonstrate that structured guidance consistently outperforms unstructured alternatives, and that incorporating asymmetric causal relationships yields greater improvements than using symmetric associations alone.

[Arxiv](https://arxiv.org/abs/2508.02583)