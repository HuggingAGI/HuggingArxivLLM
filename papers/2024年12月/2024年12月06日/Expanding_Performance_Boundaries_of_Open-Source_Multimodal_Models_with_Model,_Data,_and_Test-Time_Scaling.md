# 利用模型、数据和测试时缩放拓展开源多模态模型的性能边界

发布时间：2024年12月06日

`LLM应用` `多模态` `人工智能`

> Expanding Performance Boundaries of Open-Source Multimodal Models with Model, Data, and Test-Time Scaling

# 摘要

> 我们推出了 InternVL 2.5，这一先进的多模态大型语言模型（MLLM）系列是在 InternVL 2.0 的基础上发展而来的。它保持了核心模型架构，同时在训练、测试策略和数据质量方面有显著提升。在此次研究中，我们深入探究了模型缩放与性能的关系，系统地考察了视觉编码器、语言模型、数据集规模和测试时配置的性能走向。通过在众多基准测试上的广泛评估，涵盖多学科推理、文档理解、多图像/视频理解、现实世界理解、多模态幻觉检测、视觉基础、多语言能力和纯语言处理等方面，InternVL 2.5 展现出了极具竞争力的性能，足以与 GPT-4o 和 Claude-3.5-Sonnet 等领先的商业模型比肩。尤为值得一提的是，我们的模型是首个在 MMMU 基准上超过 70%的开源 MLLM，借助思维链（CoT）推理实现了 3.7 个点的进步，展现出测试时缩放的强大潜力。我们期望这个模型能为开源社区贡献力量，为开发和应用多模态人工智能系统树立新的标准。HuggingFace 演示请见 https://huggingface.co/spaces/OpenGVLab/InternVL

> We introduce InternVL 2.5, an advanced multimodal large language model (MLLM) series that builds upon InternVL 2.0, maintaining its core model architecture while introducing significant enhancements in training and testing strategies as well as data quality. In this work, we delve into the relationship between model scaling and performance, systematically exploring the performance trends in vision encoders, language models, dataset sizes, and test-time configurations. Through extensive evaluations on a wide range of benchmarks, including multi-discipline reasoning, document understanding, multi-image / video understanding, real-world comprehension, multimodal hallucination detection, visual grounding, multilingual capabilities, and pure language processing, InternVL 2.5 exhibits competitive performance, rivaling leading commercial models such as GPT-4o and Claude-3.5-Sonnet. Notably, our model is the first open-source MLLMs to surpass 70% on the MMMU benchmark, achieving a 3.7-point improvement through Chain-of-Thought (CoT) reasoning and showcasing strong potential for test-time scaling. We hope this model contributes to the open-source community by setting new standards for developing and applying multimodal AI systems. HuggingFace demo see https://huggingface.co/spaces/OpenGVLab/InternVL

[Arxiv](https://arxiv.org/abs/2412.05271)