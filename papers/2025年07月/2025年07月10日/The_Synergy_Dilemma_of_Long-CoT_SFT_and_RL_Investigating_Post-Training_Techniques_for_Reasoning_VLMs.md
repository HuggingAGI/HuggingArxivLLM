# 长上下文 CoT 监督微调与强化学习的协同难题：探究推理视觉语言模型的后训练技术

发布时间：2025年07月10日

`LLM应用` `视觉语言模型` `多模态推理`

> The Synergy Dilemma of Long-CoT SFT and RL: Investigating Post-Training Techniques for Reasoning VLMs

# 摘要

> 大型视觉语言模型（VLMs）正越来越多地采用长链式思维（CoT）监督微调（SFT）和强化学习（RL）等后训练技术，以激发更复杂的推理能力。尽管这些方法在纯语言模型中展现出协同效应，但它们在VLMs中的协同效果仍不明朗。我们系统研究了长链式思维SFT和RL在多个多模态推理基准测试中的不同作用及其相互作用。研究发现，SFT通过深入的结构化推理提升了在困难问题上的表现，但引入了冗长并降低了在简单问题上的性能。相比之下，RL促进了概括性和简洁性，在所有难度级别上都带来了持续改进，尽管在最难的问题上改进不如SFT显著。令人意外的是，通过两阶段、交错、渐进式训练策略，以及数据混合和模型融合，将SFT和RL结合在一起，并未产生叠加效益，反而导致了在准确性、推理风格和响应长度上的权衡。这种“协同困境”凸显了开发更无缝和自适应方法的必要性，以充分发挥结合后训练技术对推理VLMs的潜力。

> Large vision-language models (VLMs) increasingly adopt post-training techniques such as long chain-of-thought (CoT) supervised fine-tuning (SFT) and reinforcement learning (RL) to elicit sophisticated reasoning. While these methods exhibit synergy in language-only models, their joint effectiveness in VLMs remains uncertain. We present a systematic investigation into the distinct roles and interplay of long-CoT SFT and RL across multiple multimodal reasoning benchmarks. We find that SFT improves performance on difficult questions by in-depth, structured reasoning, but introduces verbosity and degrades performance on simpler ones. In contrast, RL promotes generalization and brevity, yielding consistent improvements across all difficulty levels, though the improvements on the hardest questions are less prominent compared to SFT. Surprisingly, combining them through two-staged, interleaved, or progressive training strategies, as well as data mixing and model merging, all fails to produce additive benefits, instead leading to trade-offs in accuracy, reasoning style, and response length. This ``synergy dilemma'' highlights the need for more seamless and adaptive approaches to unlock the full potential of combined post-training techniques for reasoning VLMs.

[Arxiv](https://arxiv.org/abs/2507.07562)