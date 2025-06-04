# 大型语言模型在视觉语音识别中的应用：模型扩展、上下文感知解码与迭代打磨

发布时间：2025年05月27日

`LLM应用` `视觉语音识别` `语音识别`

> Leveraging Large Language Models in Visual Speech Recognition: Model Scaling, Context-Aware Decoding, and Iterative Polishing

# 摘要

> 视觉语音识别（VSR）通过分析嘴唇动作来转录语音。近年来，大型语言模型（LLMs）被引入VSR系统后，性能得到了显著提升。然而，LLMs的潜力尚未被充分挖掘，如何在VSR任务中有效利用LLMs仍是一个未解之谜。本文系统性地探索了如何更好地利用LLMs进行VSR任务，并提出了三大关键贡献：(1) 缩放测试：我们研究了LLM规模对VSR性能的影响，证实了VSR任务中存在缩放规律。 (2) 上下文感知解码：我们在解码过程中引入上下文文本，显著提高了识别准确性。 (3) 迭代抛光：我们提出了一种迭代优化LLM输出的方法，逐步减少识别错误。通过这些创新设计，实验结果表明LLMs的巨大潜力得到了充分释放，VSR性能得到了显著提升。

> Visual Speech Recognition (VSR) transcribes speech by analyzing lip movements. Recently, Large Language Models (LLMs) have been integrated into VSR systems, leading to notable performance improvements. However, the potential of LLMs has not been extensively studied, and how to effectively utilize LLMs in VSR tasks remains unexplored. This paper systematically explores how to better leverage LLMs for VSR tasks and provides three key contributions: (1) Scaling Test: We study how the LLM size affects VSR performance, confirming a scaling law in the VSR task. (2) Context-Aware Decoding: We add contextual text to guide the LLM decoding, improving recognition accuracy. (3) Iterative Polishing: We propose iteratively refining LLM outputs, progressively reducing recognition errors. Extensive experiments demonstrate that by these designs, the great potential of LLMs can be largely harnessed, leading to significant VSR performance improvement.

[Arxiv](https://arxiv.org/abs/2506.02012)