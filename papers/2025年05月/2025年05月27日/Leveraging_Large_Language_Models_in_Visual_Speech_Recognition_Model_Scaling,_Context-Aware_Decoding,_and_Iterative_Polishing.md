# 利用大型语言模型进行视觉语音识别：模型扩展、上下文感知解码与迭代打磨

发布时间：2025年05月27日

`LLM应用` `计算机视觉` `语音识别`

> Leveraging Large Language Models in Visual Speech Recognition: Model Scaling, Context-Aware Decoding, and Iterative Polishing

# 摘要

> 视觉语音识别 (VSR) 通过分析口型来转录语音。近期，大型语言模型 (LLMs) 已被整合到 VSR 系统中，带来了显著的性能提升。然而，LLMs 的潜力尚未得到充分研究，如何在 VSR 任务中有效利用 LLMs 仍待探索。本文系统性地研究了如何更好地利用 LLMs 进行 VSR 任务，并提供了三个关键贡献：(1) 规模测试：我们研究了 LLM 规模对 VSR 性能的影响，证实了 VSR 任务中存在规模法则。 (2) 上下文感知解码：我们在解码过程中添加了上下文文本，提高了识别准确率。 (3) 迭代优化：我们提出通过迭代精炼 LLM 输出，逐步减少识别错误。大量实验表明，通过这些设计，可以充分挖掘 LLMs 的巨大潜力，显著提升 VSR 性能。

> Visual Speech Recognition (VSR) transcribes speech by analyzing lip movements. Recently, Large Language Models (LLMs) have been integrated into VSR systems, leading to notable performance improvements. However, the potential of LLMs has not been extensively studied, and how to effectively utilize LLMs in VSR tasks remains unexplored. This paper systematically explores how to better leverage LLMs for VSR tasks and provides three key contributions: (1) Scaling Test: We study how the LLM size affects VSR performance, confirming a scaling law in the VSR task. (2) Context-Aware Decoding: We add contextual text to guide the LLM decoding, improving recognition accuracy. (3) Iterative Polishing: We propose iteratively refining LLM outputs, progressively reducing recognition errors. Extensive experiments demonstrate that by these designs, the great potential of LLMs can be largely harnessed, leading to significant VSR performance improvement.

[Arxiv](https://arxiv.org/abs/2506.02012)