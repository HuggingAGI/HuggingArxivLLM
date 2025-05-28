# Hard负对比学习方法助力大型多模态模型实现对几何结构的精细理解

发布时间：2025年05月26日

`LLM应用

理由：这篇论文探讨了如何通过改进对比学习方法来提升多模态模型在几何推理任务中的表现，属于模型的实际应用和优化，因此归类为LLM应用。`

> Hard Negative Contrastive Learning for Fine-Grained Geometric Understanding in Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）在视觉感知任务中表现出色，这得益于在大规模自然场景图像上训练的对比视觉编码器。然而，对比学习在总结性描述上的固有局限性限制了模型在关键几何问题解决场景中的细致推理能力。为提升几何理解，我们提出了一种视觉编码器的困难负样本对比学习框架。该框架结合了基于图像的对比学习（利用生成式困难负样本，通过扰动图表生成代码创建）和基于文本的对比学习（利用规则和检索生成的负样本）。我们使用MMCLIP（多模态数学CLIP）这一强负样本学习方法训练CLIP，并随后训练LMM用于几何问题解决。实验显示，我们的MMGeoLM模型在三个几何推理基准测试中显著超越其他开源模型，即使7B规模也能与GPT-4o等强大闭源模型相抗衡。我们进一步研究了不同负样本构建方法及数量对LMM几何推理性能的影响，得出了宝贵结论。代码和数据集可在https://github.com/THU-KEG/MMGeoLM获取。

> Benefiting from contrastively trained visual encoders on large-scale natural scene images, Large Multimodal Models (LMMs) have achieved remarkable performance across various visual perception tasks. However, the inherent limitations of contrastive learning upon summarized descriptions fundamentally restrict the capabilities of models in meticulous reasoning, particularly in crucial scenarios of geometric problem-solving. To enhance geometric understanding, we propose a novel hard negative contrastive learning framework for the vision encoder, which combines image-based contrastive learning using generation-based hard negatives created by perturbing diagram generation code, and text-based contrastive learning using rule-based negatives derived from modified geometric descriptions and retrieval-based negatives selected based on caption similarity. We train CLIP using our strong negative learning method, namely MMCLIP (Multimodal Math CLIP), and subsequently train an LMM for geometric problem-solving. Experiments show that our trained model, MMGeoLM, significantly outperforms other open-source models on three geometric reasoning benchmarks. Even with a size of 7B, it can rival powerful closed-source models like GPT-4o. We further study the impact of different negative sample construction methods and the number of negative samples on the geometric reasoning performance of LMM, yielding fruitful conclusions. The code and dataset are available at https://github.com/THU-KEG/MMGeoLM.

[Arxiv](https://arxiv.org/abs/2505.20152)