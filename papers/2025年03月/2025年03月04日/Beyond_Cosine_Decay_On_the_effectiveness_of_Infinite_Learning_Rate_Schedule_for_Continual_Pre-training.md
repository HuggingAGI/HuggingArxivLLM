# 超越余弦衰减：无限学习率计划在持续预训练中的有效性研究

发布时间：2025年03月04日

`LLM理论` `人工智能` `自监督学习`

> Beyond Cosine Decay: On the effectiveness of Infinite Learning Rate Schedule for Continual Pre-training

# 摘要

> 无标签数据的日益丰富为人工智能训练带来了机遇与挑战。自监督学习（SSL）虽能有效从大量无标签数据中提取特征，但现有方法难以应对真实数据流的非平稳、非独立同分布特性，同时避免遗忘已有知识。近期研究采用了大规模持续预训练的重复余弦退火计划，但存在两大问题：（1）重新加热阶段会导致遗忘，（2）未与现有持续SSL方法进行系统性对比。本研究系统性对比了广泛使用的余弦计划与新提出的无限学习率计划，实证发现后者表现更优。通过在多样化的图像和语言数据集上的广泛评估，我们发现与重复余弦衰减相比，无限学习率计划在持续预训练性能上始终更优，且不受固定迭代预算限制。例如，在小规模MAE预训练中，它超越了多个强劲基线。进一步扩展到更大规模的MAE预训练和自回归语言模型预训练，结果显示无限学习率计划在大规模下依然有效，超越了重复余弦衰减在MAE预训练和零样本LM基准上的表现。

> The ever-growing availability of unlabeled data presents both opportunities and challenges for training artificial intelligence systems. While self-supervised learning (SSL) has emerged as a powerful paradigm for extracting meaningful representations from vast amounts of unlabeled data, existing methods still struggle to adapt to the non-stationary, non-IID nature of real-world data streams without forgetting previously learned knowledge. Recent works have adopted a repeated cosine annealing schedule for large-scale continual pre-training; however, these schedules (1) inherently cause forgetting during the re-warming phase and (2) have not been systematically compared to existing continual SSL methods. In this work, we systematically compare the widely used cosine schedule with the recently proposed infinite learning rate schedule and empirically find the latter to be a more effective alternative. Our extensive empirical evaluation across diverse image and language datasets demonstrates that the infinite learning rate schedule consistently enhances continual pre-training performance compared to a repeated cosine decay without being restricted to a fixed iteration budget. For instance, in a small-scale MAE pre-training setup, it outperforms several strong baselines from the literature. We then scale up our experiments to larger MAE pre-training and autoregressive language model pre-training. Our results show that the infinite learning rate schedule remains effective at scale, surpassing repeated cosine decay for both MAE pre-training and zero-shot LM benchmarks.

[Arxiv](https://arxiv.org/abs/2503.02844)