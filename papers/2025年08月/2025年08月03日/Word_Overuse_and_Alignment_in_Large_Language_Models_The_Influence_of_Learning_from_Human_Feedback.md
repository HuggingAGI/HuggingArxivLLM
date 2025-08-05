# 大型语言模型中的词汇过度使用与对齐问题：从人类反馈中学习的影响

发布时间：2025年08月03日

`LLM理论` `人工智能`

> Word Overuse and Alignment in Large Language Models: The Influence of Learning from Human Feedback

# 摘要

> 大型语言模型（LLMs）过度使用某些词汇，例如'delve'和'intricate'，这一现象广为人知。然而，这些词汇选择背后的原因至今仍不明确。本研究基于Meta的Llama模型，深入探讨了"从人类反馈中学习"（LHF）的作用，其中包含了"基于人类反馈的强化学习"和"直接偏好优化"两种方法。我们提出了一种简单直接的方法，用于检测LLMs中可能由LHF引发的词汇偏好。通过模拟LHF过程并实验证明参与者系统性地偏好包含某些特定词汇的文本变体，我们更有力地揭示了LHF与词汇过度使用之间的联系。这种词汇的过度使用可以被视为一种对齐上的偏差，但我们的研究也揭示了不同群体在词汇期望上的潜在差异——即LHF工作者与LLM用户之间的差异。本研究为可解释人工智能领域的研究增添了新的视角，并强调了在对齐研究中数据和程序透明度的重要性。

> Large Language Models (LLMs) are known to overuse certain terms like "delve" and "intricate." The exact reasons for these lexical choices, however, have been unclear. Using Meta's Llama model, this study investigates the contribution of Learning from Human Feedback (LHF), under which we subsume Reinforcement Learning from Human Feedback and Direct Preference Optimization. We present a straightforward procedure for detecting the lexical preferences of LLMs that are potentially LHF-induced. Next, we more conclusively link LHF to lexical overuse by experimentally emulating the LHF procedure and demonstrating that participants systematically prefer text variants that include certain words. This lexical overuse can be seen as a sort of misalignment, though our study highlights the potential divergence between the lexical expectations of different populations -- namely LHF workers versus LLM users. Our work contributes to the growing body of research on explainable artificial intelligence and emphasizes the importance of both data and procedural transparency in alignment research.

[Arxiv](https://arxiv.org/abs/2508.01930)