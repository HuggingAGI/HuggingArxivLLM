# 大型语言模型的深度困境

发布时间：2025年02月09日

`LLM理论` `机器学习` `人工智能`

> The Curse of Depth in Large Language Models

# 摘要

> 本文引入了“深度诅咒”这一概念，旨在揭示并解决现代大型语言模型（LLMs）中近半数层表现不如预期的现象。我们通过分析发现，这一现象在Llama、Mistral、DeepSeek和Qwen等流行模型家族中普遍存在。理论与实证研究表明，深层层表现不佳的根本原因在于Pre-Layer Normalization（Pre-LN）的广泛应用。尽管Pre-LN有助于稳定Transformer LLMs的训练，但其输出方差随模型深度呈指数级增长，导致深层Transformer块的导数接近单位矩阵，从而无法有效参与训练。为解决这一问题，我们提出了LayerNorm Scaling方法，通过将层归一化输出的方差按深度的平方根进行逆比例缩放，有效缓解了深层层的输出方差爆炸问题，提升了其贡献度。实验结果表明，LayerNorm Scaling在1.3亿到10亿参数规模的模型上显著提升了预训练性能，并且这一改进在监督微调中同样有效。这一切得益于LayerNorm Scaling使深层层在训练中能够更有效地发挥作用。

> In this paper, we introduce the Curse of Depth, a concept that highlights, explains, and addresses the recent observation in modern Large Language Models(LLMs) where nearly half of the layers are less effective than expected. We first confirm the wide existence of this phenomenon across the most popular families of LLMs such as Llama, Mistral, DeepSeek, and Qwen. Our analysis, theoretically and empirically, identifies that the underlying reason for the ineffectiveness of deep layers in LLMs is the widespread usage of Pre-Layer Normalization (Pre-LN). While Pre-LN stabilizes the training of Transformer LLMs, its output variance exponentially grows with the model depth, which undesirably causes the derivative of the deep Transformer blocks to be an identity matrix, and therefore barely contributes to the training. To resolve this training pitfall, we propose LayerNorm Scaling, which scales the variance of output of the layer normalization inversely by the square root of its depth. This simple modification mitigates the output variance explosion of deeper Transformer layers, improving their contribution. Our experimental results, spanning model sizes from 130M to 1B, demonstrate that LayerNorm Scaling significantly enhances LLM pre-training performance compared to Pre-LN. Moreover, this improvement seamlessly carries over to supervised fine-tuning. All these gains can be attributed to the fact that LayerNorm Scaling enables deeper layers to contribute more effectively during training.

[Arxiv](https://arxiv.org/abs/2502.05795)