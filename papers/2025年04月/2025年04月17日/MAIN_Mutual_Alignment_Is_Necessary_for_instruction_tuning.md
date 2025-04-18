# 主要：指令微调中，相互对齐是必要的

发布时间：2025年04月17日

`LLM应用` `人工智能`

> MAIN: Mutual Alignment Is Necessary for instruction tuning

# 摘要

> 指令微调让大语言模型（LLMs）展现出了令人惊叹的能力，但它的成功离不开大量高质量指令-响应对的支持。然而，现有的数据生成方法往往忽视了一个关键点：指令与响应的对齐程度。我们认为，高质量的指令-响应对并非由单个部分的质量决定，而是取决于它们之间的对齐程度。为此，我们提出了一种互对齐框架（MAIN），通过相互约束确保指令与响应的一致性。实验结果表明，在此框架下微调的LLaMA和Mistral等模型，在多个基准测试中均超越了传统方法。这一发现凸显了指令-响应对齐在实现可扩展、高质量指令微调中的关键作用。


> Instruction tuning has enabled large language models (LLMs) to achieve remarkable performance, but its success heavily depends on the availability of large-scale, high-quality instruction-response pairs. However, current methods for scaling up data generation often overlook a crucial aspect: the alignment between instructions and responses. We hypothesize that high-quality instruction-response pairs are not defined by the individual quality of each component, but by the extent of their alignment with each other. To address this, we propose a Mutual Alignment Framework (MAIN) that ensures coherence between the instruction and response through mutual constraints. Experiments demonstrate that models such as LLaMA and Mistral, fine-tuned within this framework, outperform traditional methods across multiple benchmarks. This approach underscores the critical role of instruction-response alignment in enabling scalable and high-quality instruction tuning for LLMs.

[Arxiv](https://arxiv.org/abs/2504.12913)