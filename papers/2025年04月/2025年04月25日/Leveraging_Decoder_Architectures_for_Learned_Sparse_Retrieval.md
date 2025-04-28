# 利用解码器架构实现学习型稀疏检索

发布时间：2025年04月25日

`LLM理论` `信息检索`

> Leveraging Decoder Architectures for Learned Sparse Retrieval

# 摘要

> 传统上，学习型稀疏检索（LSR）专注于小型规模的仅编码器型 transformer 架构。随着大规模预训练语言模型的出现，它们在不同 transformer 架构（包括仅编码器、仅解码器和编码器-解码器模型）上生成稀疏表示的能力，仍未得到充分探索。本研究探讨了 LSR 在这些架构中的有效性，探索了各种稀疏表示头部和模型规模。我们的结果突显了在零样本设置中使用大型语言模型生成有效稀疏表示的局限性，识别出如不适当术语扩展和因缺乏扩展而导致的性能下降等挑战。我们发现，采用多令牌解码方法的编码器-解码器架构在三个主干模型中表现最佳。虽然仅解码器模型的表现劣于仅编码器模型，但其在扩展到高参数数量时展现出超越后者的潜力。

> Learned Sparse Retrieval (LSR) has traditionally focused on small-scale encoder-only transformer architectures. With the advent of large-scale pre-trained language models, their capability to generate sparse representations for retrieval tasks across different transformer-based architectures, including encoder-only, decoder-only, and encoder-decoder models, remains largely unexplored. This study investigates the effectiveness of LSR across these architectures, exploring various sparse representation heads and model scales. Our results highlight the limitations of using large language models to create effective sparse representations in zero-shot settings, identifying challenges such as inappropriate term expansions and reduced performance due to the lack of expansion. We find that the encoder-decoder architecture with multi-tokens decoding approach achieves the best performance among the three backbones. While the decoder-only model performs worse than the encoder-only model, it demonstrates the potential to outperform when scaled to a high number of parameters.

[Arxiv](https://arxiv.org/abs/2504.18151)