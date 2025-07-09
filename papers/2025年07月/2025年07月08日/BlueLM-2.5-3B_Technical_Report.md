# BlueLM-2.5-3B技术报告

发布时间：2025年07月08日

`LLM应用` `边缘计算` `人工智能`

> BlueLM-2.5-3B Technical Report

# 摘要

> 我们很高兴推出BlueLM-2.5-3B——一款专为高效边缘设备部署设计的紧凑型统一密集多模态大型语言模型（MLLM），它兼具强大的通用能力和推理能力。据我们所知，这是首个支持思考模式与非思考模式的30亿规模MLLM，同时实现了对思考代币预算的显式控制。BlueLM-2.5-3B通过多样化数据整理、关键数据重采样、混合异构强化学习和高性能训练基础设施开发而成。我们的模型在仅29亿参数规模下，实现了卓越的多模态能力，同时保持了与纯文本任务相媲美的竞争力。我们在广泛的多模态和纯文本基准测试中进行了全面评估。在思考模式下，BlueLM-2.5-3B在纯文本基准测试中的表现与Qwen3-4B相当，并在多模态评估中平均仅落后更大的Kimi-VL-A3B-16B约5%。在非思考模式下，它在大多数多模态基准测试中优于Qwen2.5-VL-3B。此外，BlueLM-2.5-3B展现出卓越的数据效率。上述所有性能均在远低于Qwen2.5-VL-3B和Qwen3-4B的总训练数据量下实现。我们希望我们的工作能推动高性能、边缘设备MLLM的发展，并为研究界提供有价值的见解。

> We present BlueLM-2.5-3B, a compact and unified dense Multimodal Large Language Model (MLLM) designed for efficient edge-device deployment, offering strong general-purpose and reasoning capabilities. To the best of our knowledge, this is the first 3B-scale MLLM to support both thinking and non-thinking modes, while also enabling explicit control over thinking token budget. BlueLM-2.5-3B is developed through diversified data curation, key data resampling, hybrid heterogeneous reinforcement learning, and a high-performance training infrastructure. Our model achieves superior multimodal capacity while preserving competitive pure-text performance with only 2.9 billion parameters. We conduct comprehensive evaluations across a broad range of multimodal and text-only benchmarks. In thinking mode, BlueLM-2.5-3B achieves comparable performance to Qwen3-4B on text-only benchmarks, and trails the larger Kimi-VL-A3B-16B by only about 5% on average across multimodal evaluations. In non-thinking mode, it outperforms Qwen2.5-VL-3B on the majority of multimodal benchmarks. Additionally, BlueLM-2.5-3B exhibits exceptional data efficiency. All of the aforementioned performance is achieved with substantially less total training data than Qwen2.5-VL-3B and Qwen3-4B. We hope our work contributes to the advancement of high-performance, on-device MLLMs and provides meaningful insights to the research community.

[Arxiv](https://arxiv.org/abs/2507.05934)