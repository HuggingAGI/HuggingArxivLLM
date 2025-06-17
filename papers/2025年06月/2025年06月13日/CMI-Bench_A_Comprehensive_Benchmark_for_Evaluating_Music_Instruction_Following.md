# CMI-Bench：全面评估音乐指令遵循能力的基准测试

发布时间：2025年06月13日

`LLM应用` `音乐信息检索`

> CMI-Bench: A Comprehensive Benchmark for Evaluating Music Instruction Following

# 摘要

> 音频-文本大型语言模型（LLMs）的最新进展为音乐理解和生成带来了新的可能性。然而，现有基准测试在范围上存在局限性，往往依赖于简化的任务或多项选择评估，无法反映真实世界音乐分析的复杂性。我们重新诠释了传统音乐信息检索（MIR）注释为指令遵循格式，并推出了CMI-Bench——一个全面的音乐指令遵循基准测试，用于评估音频-文本LLMs在多样化的MIR任务中的表现。这些任务涵盖音乐类型分类、情感回归、情感标签、乐器分类、音高估计、调式检测、歌词转录、旋律提取、vocal技巧识别、乐器演奏技巧检测、音乐标签、音乐描述以及（下）拍点追踪，反映了MIR研究的核心挑战。与以往基准测试不同，CMI-Bench采用与先前最先进的MIR模型一致的标准评估指标，确保了与监督学习方法的直接可比性。我们提供了一个支持所有开源音频-文本LLMs的评估工具包，包括LTU、Qwen-audio、SALMONN、MusiLingo等。实验结果揭示了LLMs与监督模型之间显著的性能差距，同时揭示了它们在文化、时间以及性别方面的偏见，突显了当前模型在应对MIR任务方面的潜力与局限。CMI-Bench为评估音乐指令遵循能力奠定了统一的基础，推动了具有音乐感知能力的LLMs的发展。

> Recent advances in audio-text large language models (LLMs) have opened new possibilities for music understanding and generation. However, existing benchmarks are limited in scope, often relying on simplified tasks or multi-choice evaluations that fail to reflect the complexity of real-world music analysis. We reinterpret a broad range of traditional MIR annotations as instruction-following formats and introduce CMI-Bench, a comprehensive music instruction following benchmark designed to evaluate audio-text LLMs on a diverse set of music information retrieval (MIR) tasks. These include genre classification, emotion regression, emotion tagging, instrument classification, pitch estimation, key detection, lyrics transcription, melody extraction, vocal technique recognition, instrument performance technique detection, music tagging, music captioning, and (down)beat tracking: reflecting core challenges in MIR research. Unlike previous benchmarks, CMI-Bench adopts standardized evaluation metrics consistent with previous state-of-the-art MIR models, ensuring direct comparability with supervised approaches. We provide an evaluation toolkit supporting all open-source audio-textual LLMs, including LTU, Qwen-audio, SALMONN, MusiLingo, etc. Experiment results reveal significant performance gaps between LLMs and supervised models, along with their culture, chronological and gender bias, highlighting the potential and limitations of current models in addressing MIR tasks. CMI-Bench establishes a unified foundation for evaluating music instruction following, driving progress in music-aware LLMs.

[Arxiv](https://arxiv.org/abs/2506.12285)