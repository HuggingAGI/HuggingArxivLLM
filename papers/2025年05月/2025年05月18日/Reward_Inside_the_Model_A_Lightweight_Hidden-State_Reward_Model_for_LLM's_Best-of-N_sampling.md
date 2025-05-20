# 模型内置奖励：用于LLM Best-of-N采样的轻量级隐藏状态奖励模型

发布时间：2025年05月18日

`LLM应用` `人工智能`

> Reward Inside the Model: A Lightweight Hidden-State Reward Model for LLM's Best-of-N sampling

# 摘要

> 想要释放大型语言模型（LLMs）的推理潜力，高质量的奖励模型至关重要。其中，最佳的N选1投票机制展现了显著的性能提升。然而，目前的奖励模型通常基于LLMs的文本输出运行，计算成本高昂且参数繁重，限制了它们在实际应用中的部署。为此，我们提出了Efficient Linear Hidden State Reward（ELHSR）模型——一种全新的、高度参数高效的解决方案。ELHSR巧妙地利用了LLM隐藏状态中蕴含的丰富信息，仅需基线模型0.005%的参数量，便能轻松超越现有基线模型。更令人惊喜的是，它仅需少量样本即可完成训练。相较于传统的奖励模型，ELHSR实现了数量级的效率提升，每个样本所需的时间和计算量（FLOPs）大幅减少。此外，即使仅基于logits进行训练，ELHSR依然展现出强大的性能，进一步扩大了其适用范围，包括部分闭源的LLMs。值得一提的是，ELHSR还可与传统奖励模型结合使用，从而实现额外的性能提升。


> High-quality reward models are crucial for unlocking the reasoning potential of large language models (LLMs), with best-of-N voting demonstrating significant performance gains. However, current reward models, which typically operate on the textual output of LLMs, are computationally expensive and parameter-heavy, limiting their real-world applications. We introduce the Efficient Linear Hidden State Reward (ELHSR) model - a novel, highly parameter-efficient approach that leverages the rich information embedded in LLM hidden states to address these issues. ELHSR systematically outperform baselines with less than 0.005% of the parameters of baselines, requiring only a few samples for training. ELHSR also achieves orders-of-magnitude efficiency improvement with significantly less time and fewer FLOPs per sample than baseline reward models. Moreover, ELHSR exhibits robust performance even when trained only on logits, extending its applicability to some closed-source LLMs. In addition, ELHSR can also be combined with traditional reward models to achieve additional performance gains.

[Arxiv](https://arxiv.org/abs/2505.12225)