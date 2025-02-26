# DRAMA：将大型语言模型的多样化增强应用于小型密集检索器

发布时间：2025年02月25日

`LLM应用` `信息检索`

> DRAMA: Diverse Augmentation from Large Language Models to Smaller Dense Retrievers

# 摘要

> 大型语言模型（LLMs）作为密集检索器时表现出色，但其庞大的规模导致推理效率受限。我们提出DRAMA框架，利用剪枝后的LLMs和多样化数据，通过对比学习训练高效且可泛化的轻量检索器。实验显示，DRAMA在多语言和长文本处理上优于传统方法，展现了将小型检索器与LLMs技术结合的潜力，实现了效率与泛化的平衡。

> Large language models (LLMs) have demonstrated strong effectiveness and robustness while fine-tuned as dense retrievers. However, their large parameter size brings significant inference time computational challenges, including high encoding costs for large-scale corpora and increased query latency, limiting their practical deployment. While smaller retrievers offer better efficiency, they often fail to generalize effectively with limited supervised fine-tuning data. In this work, we introduce DRAMA, a training framework that leverages LLMs to train smaller generalizable dense retrievers. In particular, we adopt pruned LLMs as the backbone and train on diverse LLM-augmented data in a single-stage contrastive learning setup. Experiments show that DRAMA offers better multilingual and long-context capabilities than traditional encoder-based retrievers, and achieves strong performance across multiple tasks and languages. These highlight the potential of connecting the training of smaller retrievers with the growing advancements in LLMs, bridging the gap between efficiency and generalization.

[Arxiv](https://arxiv.org/abs/2502.18460)