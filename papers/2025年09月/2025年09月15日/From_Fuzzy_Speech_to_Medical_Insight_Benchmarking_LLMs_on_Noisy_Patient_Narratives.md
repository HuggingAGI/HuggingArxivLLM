# 从模糊语音到医学洞察：大型语言模型（LLMs）在嘈杂患者叙述上的基准测试

发布时间：2025年09月15日

`LLM应用` `医疗健康`

> From Fuzzy Speech to Medical Insight: Benchmarking LLMs on Noisy Patient Narratives

# 摘要

> 大型语言模型（LLMs）在医疗领域的广泛应用，引发了人们对其解读患者叙述能力的质疑——这类叙述往往不规范、模糊且充斥噪声。现有评估基准多依赖干净、结构化的临床文本，难以揭示模型在真实场景下的表现。为此，本研究构建了一个全新的合成数据集，专门模拟患者自我描述中常见的语言噪声、模糊表达及非专业术语，并涵盖不同程度的此类特征。该数据集包含临床一致性场景，标注了真实诊断结果，覆盖不同沟通清晰度水平，以反映现实中多样化的报告风格。基于此基准，我们对多个最先进的LLM模型（包括基于BERT的模型和编码器-解码器T5模型）进行了微调与评估。为支持研究的可重复性及后续探索，我们发布了噪声诊断基准（NDB）。这是一个结构化的合成数据集，包含带噪声的患者描述，旨在测试并比较大型语言模型在真实语言环境下的诊断能力。该基准已向科研社区开放，获取链接：https://github.com/lielsheri/PatientSignal

> The widespread adoption of large language models (LLMs) in healthcare raises critical questions about their ability to interpret patient-generated narratives, which are often informal, ambiguous, and noisy. Existing benchmarks typically rely on clean, structured clinical text, offering limited insight into model performance under realistic conditions. In this work, we present a novel synthetic dataset designed to simulate patient self-descriptions characterized by varying levels of linguistic noise, fuzzy language, and layperson terminology. Our dataset comprises clinically consistent scenarios annotated with ground-truth diagnoses, spanning a spectrum of communication clarity to reflect diverse real-world reporting styles. Using this benchmark, we fine-tune and evaluate several state-of-the-art models (LLMs), including BERT-based and encoder-decoder T5 models. To support reproducibility and future research, we release the Noisy Diagnostic Benchmark (NDB), a structured dataset of noisy, synthetic patient descriptions designed to stress-test and compare the diagnostic capabilities of large language models (LLMs) under realistic linguistic conditions. We made the benchmark available for the community: https://github.com/lielsheri/PatientSignal

[Arxiv](https://arxiv.org/abs/2509.11803)