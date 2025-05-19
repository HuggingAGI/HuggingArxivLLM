# KV 缓存的精准量化结合异常标记追踪

发布时间：2025年05月16日

`LLM应用` `人工智能` `计算机系统`

> Accurate KV Cache Quantization with Outlier Tokens Tracing

# 摘要

> 大型语言模型（LLMs）的强大能力需要在部署过程中投入大量计算资源。尽管KV缓存可以在推理过程中显著减少重复计算，但它也会带来额外的内存开销。KV缓存量化提供了一个有前景的解决方案，在内存使用和准确性之间找到了一个很好的平衡点。先前的研究表明，键（Keys）是按通道分布的，而值（Values）是按令牌分布的。因此，常见的做法是对键应用通道量化，对值应用令牌量化。然而，我们的进一步研究表明，一小部分异常令牌表现出与这一模式不同的独特特征，这可能对量化准确性产生重大影响。为了解决这一问题，我们开发了一种简单而有效的方法，能够在解码过程中准确识别这些令牌，并将其作为异常令牌排除在量化之外，从而显著提高整体准确性。大量实验表明，与2位量化相比，我们的方法实现了显著的准确性提升，同时实现了内存使用减少6.4倍，吞吐量增加2.3倍。

> The impressive capabilities of Large Language Models (LLMs) come at the cost of substantial computational resources during deployment. While KV Cache can significantly reduce recomputation during inference, it also introduces additional memory overhead. KV Cache quantization presents a promising solution, striking a good balance between memory usage and accuracy. Previous research has shown that the Keys are distributed by channel, while the Values are distributed by token. Consequently, the common practice is to apply channel-wise quantization to the Keys and token-wise quantization to the Values. However, our further investigation reveals that a small subset of unusual tokens exhibit unique characteristics that deviate from this pattern, which can substantially impact quantization accuracy. To address this, we develop a simple yet effective method to identify these tokens accurately during the decoding process and exclude them from quantization as outlier tokens, significantly improving overall accuracy. Extensive experiments show that our method achieves significant accuracy improvements under 2-bit quantization and can deliver a 6.4 times reduction in memory usage and a 2.3 times increase in throughput.

[Arxiv](https://arxiv.org/abs/2505.10938)