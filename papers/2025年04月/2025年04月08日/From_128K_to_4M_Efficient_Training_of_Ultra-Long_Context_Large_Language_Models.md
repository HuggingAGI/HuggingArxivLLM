# 从128K到4M：超长上下文窗口大型语言模型的高效训练

发布时间：2025年04月08日

`LLM应用` `大型语言模型`

> From 128K to 4M: Efficient Training of Ultra-Long Context Large Language Models

# 摘要

> 长上下文能力在文档理解、视频分析、上下文学习及推理扩展等众多领域发挥着关键作用，要求模型能够处理和推理长序列的文本与多模态数据。本研究提出了一种高效训练方案，从对齐的指令模型出发，构建支持超长上下文的大型语言模型，将上下文长度极限从128K扩展至1M、2M乃至4M个令牌。我们的方法通过高效的持续预训练策略扩展上下文窗口，并借助有效的指令微调保持模型的指令理解和推理能力。基于Llama3.1-Instruct构建的UltraLong-8B模型，采用我们的训练方案，在多种长上下文基准测试中展现出卓越性能。值得注意的是，我们的模型在标准基准上同样表现优异，实现了长上下文与短上下文任务的均衡提升。我们深入分析了关键设计选择，揭示了扩展策略与数据构成的影响。我们的研究为高效扩展上下文长度同时保持模型通用能力提供了坚实框架。模型权重已发布于：https://ultralong.github.io/。


> Long-context capabilities are essential for a wide range of applications, including document and video understanding, in-context learning, and inference-time scaling, all of which require models to process and reason over long sequences of text and multimodal data. In this work, we introduce a efficient training recipe for building ultra-long context LLMs from aligned instruct model, pushing the boundaries of context lengths from 128K to 1M, 2M, and 4M tokens. Our approach leverages efficient continued pretraining strategies to extend the context window and employs effective instruction tuning to maintain the instruction-following and reasoning abilities. Our UltraLong-8B, built on Llama3.1-Instruct with our recipe, achieves state-of-the-art performance across a diverse set of long-context benchmarks. Importantly, models trained with our approach maintain competitive performance on standard benchmarks, demonstrating balanced improvements for both long and short context tasks. We further provide an in-depth analysis of key design choices, highlighting the impacts of scaling strategies and data composition. Our findings establish a robust framework for efficiently scaling context lengths while preserving general model capabilities. We release all model weights at: https://ultralong.github.io/.

[Arxiv](https://arxiv.org/abs/2504.06214)