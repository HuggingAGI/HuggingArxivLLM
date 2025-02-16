# 在 KV 缓存压缩下，大型语言模型能否保持基本能力？

发布时间：2025年02月03日

`LLM理论

论文摘要探讨了大型语言模型（LLM）中键值缓存压缩方法对模型基础能力的影响，分析了不同压缩方法在多样化任务中的表现，并提出了一种新的压缩方法ShotKV。这属于对LLM内部机制和优化的研究，因此归类为LLM理论。` `大型语言模型` `模型优化`

> Can LLMs Maintain Fundamental Abilities under KV Cache Compression?

# 摘要

> 本文探讨了大型语言模型中一个尚未被充分研究的重要问题：键值缓存压缩方法对模型基础能力的影响。尽管现有压缩方法在长上下文基准测试中表现优异，但它们对模型核心能力的影响仍需深入研究。我们开展了一项全面的实证研究，评估了世界知识、常识推理、算术推理、代码生成、安全性和长上下文理解和生成等多样化任务中，各种主流键值缓存压缩方法的表现。分析发现，这些压缩方法在特定任务上的性能会出现不同程度的下降。其中，算术推理任务对激进压缩尤为敏感，不同方法的性能下降幅度在【数学公式】之间。值得注意的是，DeepSeek R1 Distill模型相较于指令微调模型表现出了更强的压缩容忍度，性能下降幅度仅为【数学公式】。基于对注意力模式和跨任务压缩性能的分析，我们提出了一种新型压缩方法ShotKV，该方法在保持shot级别语义连贯性的同时，对预填和解码阶段进行了区分处理。实验结果表明，在激进压缩比率下，ShotKV在长上下文生成任务中实现了【数学公式】的性能提升。

> This paper investigates an under-explored challenge in large language models (LLMs): the impact of KV cache compression methods on LLMs' fundamental capabilities. While existing methods achieve impressive compression ratios on long-context benchmarks, their effects on core model capabilities remain understudied. We present a comprehensive empirical study evaluating prominent KV cache compression methods across diverse tasks, spanning world knowledge, commonsense reasoning, arithmetic reasoning, code generation, safety, and long-context understanding and generation.Our analysis reveals that KV cache compression methods exhibit task-specific performance degradation. Arithmetic reasoning tasks prove particularly sensitive to aggressive compression, with different methods showing performance drops of $17.4\%$-$43.3\%$. Notably, the DeepSeek R1 Distill model exhibits more robust compression tolerance compared to instruction-tuned models, showing only $9.67\%$-$25.53\%$ performance degradation. Based on our analysis of attention patterns and cross-task compression performance, we propose ShotKV, a novel compression approach that distinctly handles prefill and decoding phases while maintaining shot-level semantic coherence. Empirical results show that ShotKV achieves $9\%$-$18\%$ performance improvements on long-context generation tasks under aggressive compression ratios.

[Arxiv](https://arxiv.org/abs/2502.01941)