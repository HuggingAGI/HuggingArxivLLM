# LR0.FM：基础模型的低分辨率零-shot分类基准

发布时间：2025年02月06日

`其他

理由：这篇论文主要研究的是视觉-语言基础模型在低分辨率图像上的鲁棒性，并提出了一种新的度量标准和增强模型鲁棒性的策略。虽然涉及到了基础模型（FMs），但主要内容集中在视觉-语言模型的性能评估和改进，而不是直接涉及大型语言模型（LLM）的应用、理论或代理（Agent）相关的内容。因此，将其分类为“其他”更为合适。` `计算机视觉` `图像处理`

> LR0.FM: Low-Resolution Zero-shot Classification Benchmark For Foundation Models

# 摘要

> # 摘要
视觉-语言基础模型（FMs）在各种任务中展现出卓越的零-shot 泛化能力，这主要得益于大规模数据集的广泛预训练。然而，它们在低分辨率/像素化（LR）图像上的鲁棒性，这一现实场景中的常见挑战，仍未被充分研究。我们推出了 LR0.FM，一个全面的基准测试，评估了低分辨率对 10 个 FMs 在 66 个骨干网络和 15 个数据集上零-shot 分类性能的影响。我们提出了一种新的度量标准——加权聚合鲁棒性，以弥补现有度量标准的不足，更好地评估模型在不同分辨率和数据集上的表现。我们的关键发现包括：（i）模型大小与分辨率下降的鲁棒性呈正相关，（ii）预训练数据集的质量比其规模更为重要，（iii）微调和高分辨率模型对 LR 的鲁棒性较差。进一步分析表明，模型在 LR 下能做出语义上合理的预测，且输入中缺乏细粒度细节对模型初始层的影响大于深层。基于这些发现，我们提出了一种简单策略 LR-TK0，在不影响预训练权重的情况下增强模型的鲁棒性。我们展示了 LR-TK0 在多个数据集上对低分辨率的鲁棒性及其在骨干网络和其他方法上的泛化能力。代码可在 https://github.com/shyammarjit/LR0.FM 获取。

> Visual-language foundation Models (FMs) exhibit remarkable zero-shot generalization across diverse tasks, largely attributed to extensive pre-training on large-scale datasets. However, their robustness on low-resolution/pixelated (LR) images, a common challenge in real-world scenarios, remains underexplored. We introduce LR0.FM, a comprehensive benchmark evaluating the impact of low resolution on the zero-shot classification performance of 10 FM(s) across 66 backbones and 15 datasets. We propose a novel metric, Weighted Aggregated Robustness, to address the limitations of existing metrics and better evaluate model performance across resolutions and datasets. Our key findings show that: (i) model size positively correlates with robustness to resolution degradation, (ii) pre-training dataset quality is more important than its size, and (iii) fine-tuned and higher-resolution models are less robust against LR. Our analysis further reveals that the model makes semantically reasonable predictions at LR, and the lack of fine-grained details in input adversely impacts the model's initial layers more than the deeper layers. We use these insights and introduce a simple strategy, LR-TK0, to enhance the robustness of models without compromising their pre-trained weights. We demonstrate the effectiveness of LR-TK0 for robustness against low-resolution across several datasets and its generalization capability across backbones and other approaches. Code is available at this https://github.com/shyammarjit/LR0.FM

[Arxiv](https://arxiv.org/abs/2502.03950)