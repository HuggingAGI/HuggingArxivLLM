# GraDeT-HTR：基于字符素分词器与纯解码器Transformer的资源高效型孟加拉语手写文本识别系统

发布时间：2025年09月22日

`其他` `基础理论`

> GraDeT-HTR: A Resource-Efficient Bengali Handwritten Text Recognition System utilizing Grapheme-based Tokenizer and Decoder-only Transformer

# 摘要

> 尽管孟加拉语是世界第六大使用语言，但其手写文本识别（HTR）系统的发展仍严重滞后。孟加拉文字母体系复杂——存在连写字符、变音符号，且手写风格差异极大——加之标注数据集稀缺，使得这项任务极具挑战性。为此，我们提出了GraDeT-HTR——一种资源高效的孟加拉语手写文本识别系统，其核心是基于字形感知的仅解码器Transformer架构。为攻克孟加拉文字母的独特难题，我们通过集成基于字形的分词器来提升仅解码器Transformer的性能，结果显示：与传统子词分词器相比，新方法的识别准确率显著提高。该模型先在大规模合成数据上预训练，再经真实人工标注样本微调，最终在多个基准数据集上均达到了当前最优性能。

> Despite Bengali being the sixth most spoken language in the world, handwritten text recognition (HTR) systems for Bengali remain severely underdeveloped. The complexity of Bengali script--featuring conjuncts, diacritics, and highly variable handwriting styles--combined with a scarcity of annotated datasets makes this task particularly challenging. We present GraDeT-HTR, a resource-efficient Bengali handwritten text recognition system based on a Grapheme-aware Decoder-only Transformer architecture. To address the unique challenges of Bengali script, we augment the performance of a decoder-only transformer by integrating a grapheme-based tokenizer and demonstrate that it significantly improves recognition accuracy compared to conventional subword tokenizers. Our model is pretrained on large-scale synthetic data and fine-tuned on real human-annotated samples, achieving state-of-the-art performance on multiple benchmark datasets.

[Arxiv](https://arxiv.org/abs/2509.18081)