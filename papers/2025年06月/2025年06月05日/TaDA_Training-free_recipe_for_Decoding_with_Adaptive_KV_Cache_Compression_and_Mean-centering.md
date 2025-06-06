# TaDA：无训练方法，实现自适应KV缓存压缩与均值中心化解码

发布时间：2025年06月05日

`LLM理论` `计算机体系结构`

> TaDA: Training-free recipe for Decoding with Adaptive KV Cache Compression and Mean-centering

# 摘要

> 键值（KV）缓存是Transformer模型中实现高效解码或推理的核心组件，但其内存需求随序列长度增长而显著增加，这对大型语言模型的可扩展部署构成了重大挑战。在多种KV缓存压缩方法中，对键和值激活进行量化已被广泛探索。大多数KV缓存量化方法仍需单独处理稀疏且非连续的异常值。为解决这一问题，我们提出了TaDA，一种无需训练的KV缓存压缩方法。该方法通过根据各层的误差敏感性自适应调整量化精度，并采用均值中心化技术，从而无需单独处理异常值。我们的方法显著提升了支持多种上下文长度的多个模型的准确性。此外，我们的方法无需单独管理异常元素——这是大多数传统量化方法长期存在的难题。在标准基准上的实验表明，我们的技术将KV缓存内存占用降至原16位基线的27%，同时实现可比的准确性。通过潜在支持更长上下文长度的模型、推理模型以及更长的推理链，我们的方法为语言模型的可扩展和高性能推理铺平了道路。

> The key-value (KV) cache in transformer models is a critical component for efficient decoding or inference, yet its memory demands scale poorly with sequence length, posing a major challenge for scalable deployment of large language models. Among several approaches to KV cache compression, quantization of key and value activations has been widely explored. Most KV cache quantization methods still need to manage sparse and noncontiguous outliers separately. To address this, we introduce TaDA, a training-free recipe for KV cache compression with quantization precision that adapts to error sensitivity across layers and a mean centering to eliminate separate outlier handling. Our approach yields substantial accuracy improvements for multiple models supporting various context lengths. Moreover, our approach does not need to separately manage outlier elements -- a persistent hurdle in most traditional quantization methods. Experiments on standard benchmarks demonstrate that our technique reduces KV cache memory footprint to 27% of the original 16-bit baseline while achieving comparable accuracy. Our method paves the way for scalable and high-performance reasoning in language models by potentially enabling inference for longer context length models, reasoning models, and longer chain of thoughts.

[Arxiv](https://arxiv.org/abs/2506.04642)