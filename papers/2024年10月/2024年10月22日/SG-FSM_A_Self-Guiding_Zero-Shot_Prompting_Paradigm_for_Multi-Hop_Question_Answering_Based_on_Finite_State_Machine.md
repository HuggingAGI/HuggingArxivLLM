# SG-FSM: 基于有限状态机的自引导零-shot提示范式，专为多跳问答设计

发布时间：2024年10月22日

`LLM应用

理由：这篇论文主要讨论了如何通过自引导提示有限状态机（SG-FSM）来提升大型语言模型（LLM）在多跳问答（MHQA）任务中的表现。论文的核心是改进LLM在特定应用场景（即多跳问答）中的性能，因此属于LLM应用类别。` `问答系统`

> SG-FSM: A Self-Guiding Zero-Shot Prompting Paradigm for Multi-Hop Question Answering Based on Finite State Machine

# 摘要

> # 摘要
具备思维链提示的大型语言模型（如 OpenAI-o1）在自然语言推理任务中表现卓越。然而，多跳问答（MHQA）对现有模型仍是一大挑战，主要问题包括幻觉、错误传播和上下文长度限制。为应对这些挑战并提升 LLMs 在 MHQA 上的表现，我们提出了自引导提示有限状态机（SG-FSM），旨在增强多跳推理能力。与传统思维链方法不同，SG-FSM 通过将复杂问题逐步分解为子问题并自我修正来提高准确性。它每次处理一个子问题，根据当前上下文和结果动态决定下一步，运作方式类似自动机。实验表明，该方法在 Musique 等复杂数据集上表现优异，超越了现有基线。SG-FSM 有效减少了幻觉，即使中间步骤出错也能恢复正确答案，同时显著简化了评估流程。

> Large Language Models with chain-of-thought prompting, such as OpenAI-o1, have shown impressive capabilities in natural language inference tasks. However, Multi-hop Question Answering (MHQA) remains challenging for many existing models due to issues like hallucination, error propagation, and limited context length. To address these challenges and enhance LLMs' performance on MHQA, we propose the Self-Guiding prompting Finite State Machine (SG-FSM), designed to strengthen multi-hop reasoning abilities. Unlike traditional chain-of-thought methods, SG-FSM tackles MHQA by iteratively breaking down complex questions into sub-questions, correcting itself to improve accuracy. It processes one sub-question at a time, dynamically deciding the next step based on the current context and results, functioning much like an automaton. Experiments across various benchmarks demonstrate the effectiveness of our approach, outperforming strong baselines on challenging datasets such as Musique. SG-FSM reduces hallucination, enabling recovery of the correct final answer despite intermediate errors. It also improves adherence to specified output formats, simplifying evaluation significantly.

[Arxiv](https://arxiv.org/abs/2410.17021)