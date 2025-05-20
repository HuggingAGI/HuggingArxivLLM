# SAKURA：探索基于语音和音频信息的大型音频语言模型的多跳推理能力

发布时间：2025年05月19日

`LLM应用

理由：这篇论文探讨了大型音频语言模型（LALMs）在多模态推理，特别是多跳推理方面的能力。它引入了一个新的基准测试SAKURA，用于评估这些模型在整合语音和音频信息进行多跳推理时的表现。虽然论文关注的是多模态模型，但其核心在于评估和应用这些模型在特定任务中的能力，因此归类于LLM应用。` `信息检索` `多模态`

> SAKURA: On the Multi-hop Reasoning of Large Audio-Language Models Based on Speech and Audio Information

# 摘要

> 大型音频语言模型（LALMs）在大型语言模型的基础上，扩展了对语音、音频等多模态的理解。尽管它们在语音和音频处理任务上的表现得到了广泛研究，但推理能力仍待深入探索。尤其是，它们进行多跳推理的能力——即回忆和整合多个事实的能力——尚未得到系统性评估。现有基准测试侧重于通用语音和音频处理任务、对话能力和公平性，却忽视了这一方面。为填补这一空白，我们引入了SAKURA，一个基于语音和音频信息评估LALMs多跳推理能力的基准测试。结果显示，LALMs在整合语音/音频表示进行多跳推理时表现困难，即使正确提取了相关信息，这凸显了多模态推理中的根本性挑战。我们的发现揭示了LALMs的一个关键局限性，并为未来研究提供了见解和资源。

> Large audio-language models (LALMs) extend the large language models with multimodal understanding in speech, audio, etc. While their performances on speech and audio-processing tasks are extensively studied, their reasoning abilities remain underexplored. Particularly, their multi-hop reasoning, the ability to recall and integrate multiple facts, lacks systematic evaluation. Existing benchmarks focus on general speech and audio-processing tasks, conversational abilities, and fairness but overlook this aspect. To bridge this gap, we introduce SAKURA, a benchmark assessing LALMs' multi-hop reasoning based on speech and audio information. Results show that LALMs struggle to integrate speech/audio representations for multi-hop reasoning, even when they extract the relevant information correctly, highlighting a fundamental challenge in multimodal reasoning. Our findings expose a critical limitation in LALMs, offering insights and resources for future research.

[Arxiv](https://arxiv.org/abs/2505.13237)