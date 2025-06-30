# 投影压缩：通过可训练投影实现高效的Transformer压缩

发布时间：2025年06月27日

`LLM应用` `模型压缩`

> Projected Compression: Trainable Projection for Efficient Transformer Compression

# 摘要

> 大型语言模型的规模稳步增长，带来了更优性能，但也导致推理时间和计算需求激增。因此，模型压缩方法成为研究热点。我们提出了一种新型压缩技术——投影压缩（Projected Compression），通过投影模块减少模型权重。具体而言，我们首先训练额外的可训练投影权重，同时保留对所有原始参数的访问。随后，将这些投影合并到一个低维乘积矩阵中，从而得到更小的标准Transformer模型。与需要额外计算开销的其他方法不同，我们的方法在每token计算步骤的FLOPs上与基础模型一致。实验结果表明，投影压缩在更高质量的模型上优于硬剪枝和重新训练方法。此外，性能差距随token数量增加而良好扩展。

> Large language models have steadily increased in size to achieve improved performance; however, this growth has also led to greater inference time and computational demands. Consequently, there is rising interest in model size reduction methods. To address this issue, we propose Projected Compression, a novel model compression technique, that reduces model weights by utilizing projection modules. Specifically, we first train additional trainable projections weights and preserve access to all the original model parameters. Subsequently, these projections are merged into a lower-dimensional product matrix, resulting in a reduced-size standard Transformer-based model. Unlike alternative approaches that require additional computational overhead, our method matches the base model's per-token computation step in FLOPs. Experimental results show that Projected Compression outperforms the comparable hard pruning and retraining approach on higher quality models. Moreover, the performance margin scales well with the number of tokens.

[Arxiv](https://arxiv.org/abs/2506.22255)