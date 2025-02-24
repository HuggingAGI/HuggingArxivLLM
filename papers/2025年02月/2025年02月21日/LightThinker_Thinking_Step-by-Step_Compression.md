# LightThinker：一步步思考压缩

发布时间：2025年02月21日

`LLM理论`

> LightThinker: Thinking Step-by-Step Compression

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中表现卓越，但生成大量token带来的巨大内存和计算成本却显著影响了其效率。本文提出了一种创新方法——LightThinker，使LLMs能够在推理过程中动态压缩中间思想。受人类认知过程启发，LightThinker将冗长的思想步骤压缩为紧凑的表达形式，并丢弃原始推理链，从而大幅减少了上下文窗口中存储的token数量。这一效果通过在数据构造、将隐藏状态映射到浓缩主旨token以及创建专用注意力掩码这三个方面对模型进行训练来实现。此外，我们引入了Dependency（Dep）指标，通过衡量生成过程中对历史token的依赖程度来量化压缩的程度。在四个数据集和两个模型上的大量实验表明，LightThinker在减少峰值内存使用和推理时间的同时，仍能保持较高的准确性。我们的研究为在不降低性能的前提下提升LLMs在复杂推理任务中的效率提供了新的方向。代码将在https://github.com/zjunlp/LightThinker上发布。

> Large language models (LLMs) have shown remarkable performance in complex reasoning tasks, but their efficiency is hindered by the substantial memory and computational costs associated with generating lengthy tokens. In this paper, we propose LightThinker, a novel method that enables LLMs to dynamically compress intermediate thoughts during reasoning. Inspired by human cognitive processes, LightThinker compresses verbose thought steps into compact representations and discards the original reasoning chains, thereby significantly reducing the number of tokens stored in the context window. This is achieved by training the model on when and how to perform compression through data construction, mapping hidden states to condensed gist tokens, and creating specialized attention masks. Additionally, we introduce the Dependency (Dep) metric to quantify the degree of compression by measuring the reliance on historical tokens during generation. Extensive experiments on four datasets and two models show that LightThinker reduces peak memory usage and inference time, while maintaining competitive accuracy. Our work provides a new direction for improving the efficiency of LLMs in complex reasoning tasks without sacrificing performance. Code will be released at https://github.com/zjunlp/LightThinker.

[Arxiv](https://arxiv.org/abs/2502.15589)