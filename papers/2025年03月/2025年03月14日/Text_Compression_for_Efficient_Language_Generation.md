# 文本压缩助力高效语言生成

发布时间：2025年03月14日

`LLM理论` `计算效率`

> Text Compression for Efficient Language Generation

# 摘要

> 我们质疑大型语言模型（LLMs）必须完全依赖子词令牌进行高质量文本生成的主流观点。为此，我们提出了“生成式预训练思考器”（GPTHF），这是一种分层的Transformer语言模型，通过将文本压缩为句子嵌入并采用句子注意力机制实现文本生成。GPTHF保留了GPT的核心架构，仅通过动态稀疏注意力掩码调整了令牌交互方式。

实验结果表明，在小规模模型范围内，GPTHF较同规模GPT模型实现了数量级的FLOPs效率提升，且运行速度提升了三倍。这一突破得益于独特的生成方法，通过缓存并复用句子嵌入，使输入的大部分内容能够绕过网络的大部分计算，从而实现显著性能提升。

> We challenge the prevailing assumption that LLMs must rely fully on sub-word tokens for high-quality text generation. To this end, we propose the "Generative Pretrained Thoughtformer" (GPTHF), a hierarchical transformer language model capable of text generation by compressing text into sentence embeddings and employing a sentence attention mechanism. GPTHF retains GPT's architecture, modifying only token interactions via dynamic sparse attention masks.
  Our experiments show that GPTHF achieves an up to an order of magnitude improvement in FLOPs efficiency and a threefold increase in runtime speed compared to equally-sized GPT models in the low-size regime. This is achieved through a unique generation method that caches and reuses sentence embeddings, allowing significant portions of the input to bypass large parts of the network.

[Arxiv](https://arxiv.org/abs/2503.11426)