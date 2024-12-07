# LamRA：大型多模态模型充当您的高级检索助手

发布时间：2024年12月02日

`LLM应用` `信息检索` `多模态`

> LamRA: Large Multimodal Model as Your Advanced Retrieval Assistant

# 摘要

> 随着多模态信息检索的迅猛发展，愈发复杂的检索任务纷纷涌现。现有的方法大多依赖针对特定任务对视觉语言模型进行微调，通常是那些通过图像 - 文本对比学习训练出来的模型。在本文中，我们探究了将生成式大型多模态模型（LMMs）重新用于检索的可能性。这种方式能够把所有检索任务统一在相同的公式之下，更关键的是，无需额外训练就能对未曾见过的检索任务进行外推。我们的贡献可概括为以下几个方面：（i）我们引入了 LamRA，这是一个多用途框架，旨在赋予 LMMs 强大的检索和重排序能力。（ii）在检索方面，我们采用了包含仅语言预训练和多模态指令调整的两阶段训练策略，逐步提升 LMM 的检索性能。（iii）在重排序方面，我们进行针对逐点和列表重排序的联合训练，提供了两种不同的途径来进一步增强检索性能。（iv）大量的实验结果凸显了我们的方法在处理十多个检索任务时的有效性，在有监督和零样本的设定中均展现出强劲的性能，包括涉及之前未曾见过的检索任务的情形。

> With the rapid advancement of multimodal information retrieval, increasingly complex retrieval tasks have emerged. Existing methods predominately rely on task-specific fine-tuning of vision-language models, often those trained with image-text contrastive learning. In this paper, we explore the possibility of re-purposing generative Large Multimodal Models (LMMs) for retrieval. This approach enables unifying all retrieval tasks under the same formulation and, more importantly, allows for extrapolation towards unseen retrieval tasks without additional training. Our contributions can be summarised in the following aspects: (i) We introduce LamRA, a versatile framework designed to empower LMMs with sophisticated retrieval and reranking capabilities. (ii) For retrieval, we adopt a two-stage training strategy comprising language-only pre-training and multimodal instruction tuning to progressively enhance LMM's retrieval performance. (iii) For reranking, we employ joint training for both pointwise and listwise reranking, offering two distinct ways to further boost the retrieval performance. (iv) Extensive experimental results underscore the efficacy of our method in handling more than ten retrieval tasks, demonstrating robust performance in both supervised and zero-shot settings, including scenarios involving previously unseen retrieval tasks.

[Arxiv](https://arxiv.org/abs/2412.01720)