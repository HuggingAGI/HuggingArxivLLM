# 增强对齐的推测解码，结合对齐采样和条件验证

发布时间：2025年05月19日

`LLM应用` `人工智能`

> Alignment-Augmented Speculative Decoding with Alignment Sampling and Conditional Verification

# 摘要

> 近期研究显示，推测解码在加速大型语言模型自回归生成方面潜力巨大。这些方法的成功关键在于草稿候选与目标模型输出的对齐。现有方法如EAGLE和Medusa主要依赖训练实现对齐，但训练成本高昂。本文提出了一种无需训练的增强对齐推测解码算法。我们创新性地引入对齐采样方法，利用预填充阶段的输出分布生成更对齐的草稿候选。同时，为了充分发挥高质量但未对齐草稿的潜力，我们设计了一种简单而有效的灵活验证策略。通过自适应概率阈值，我们的方法在提升生成准确性的同时，显著提高了推理效率。在涵盖问答、摘要和代码补全等8个数据集的实验中，LLaMA3模型的平均生成得分提升了3.3分。我们的方法实现了平均接受长度高达2.39，并将生成速度提升了2.23倍，展现了显著的性能提升。


> Recent works have revealed the great potential of speculative decoding in accelerating the autoregressive generation process of large language models. The success of these methods relies on the alignment between draft candidates and the sampled outputs of the target model. Existing methods mainly achieve draft-target alignment with training-based methods, e.g., EAGLE, Medusa, involving considerable training costs. In this paper, we present a training-free alignment-augmented speculative decoding algorithm. We propose alignment sampling, which leverages output distribution obtained in the prefilling phase to provide more aligned draft candidates. To further benefit from high-quality but non-aligned draft candidates, we also introduce a simple yet effective flexible verification strategy. Through an adaptive probability threshold, our approach can improve generation accuracy while further improving inference efficiency. Experiments on 8 datasets (including question answering, summarization and code completion tasks) show that our approach increases the average generation score by 3.3 points for the LLaMA3 model. Our method achieves a mean acceptance length up to 2.39 and speed up generation by 2.23.

[Arxiv](https://arxiv.org/abs/2505.13204)