# # 零样本生物特征任务中的基础模型基准测试

发布时间：2025年05月30日

`LLM应用

摘要：这篇论文探讨了视觉语言模型（VLMs）和多模态大型语言模型（MLLMs）在生物识别任务中的应用，展示了这些模型在零样本和小样本情况下的性能。论文评估了模型在人脸识别、虹膜识别、软生物特征预测、防伪攻击检测和人脸操作检测等任务中的表现，并展示了这些模型生成的特征嵌入在多种任务中的有效性。研究结果表明，这些模型在生物识别任务中表现出色，进一步证明了预训练模型在实现通用人工智能（AGI）方面的潜力。因此，这篇论文属于LLM应用类别。` `生物识别` `多模态`

> Benchmarking Foundation Models for Zero-Shot Biometric Tasks

# 摘要

> # 摘要
视觉语言模型（VLMs）与多模态大型语言模型（MLLMs）的问世，正在重新定义人工智能的边界，这些模型无需或只需极少监督即可实现跨任务的卓越泛化能力。然而，它们在生物识别与分析领域的潜力尚未得到充分挖掘。本研究介绍了一个全面的基准测试，旨在评估当前最先进的公开视觉语言模型（VLMs）和多模态大型语言模型（MLLMs）在六个生物识别任务上的零样本和小样本性能，这些任务涵盖了面部和虹膜两种模态：人脸识别、软生物特征预测（性别和种族）、虹膜识别、防伪攻击检测（PAD）以及人脸操作检测（Morphs 和 Deepfakes）。本研究共采用了 41 种 VLMs 进行评估。实验结果表明，这些基础模型生成的特征嵌入可以在多种生物识别任务中取得不同程度的成功。例如，在人脸识别任务中，无需任何微调，在 LFW 数据集上达到了 1% 的错误匹配率（FMR）下 96.77% 的真实匹配率（TMR）。在虹膜识别任务中，同样无需微调，在 IITD-R-Full 数据集上达到了 1% FMR 下 97.55% 的 TMR。此外，我们还展示了，通过在这些特征嵌入上应用一个简单的分类器头部，可以有效地进行人脸的深度伪造检测、虹膜的防伪攻击检测（PAD），以及从面部提取性别和种族等软生物特征，且准确度相当高。这项研究再次证明了预训练模型在实现人工智能长期愿景——通用人工智能（AGI）方面的巨大潜力。


> The advent of foundation models, particularly Vision-Language Models (VLMs) and Multi-modal Large Language Models (MLLMs), has redefined the frontiers of artificial intelligence, enabling remarkable generalization across diverse tasks with minimal or no supervision. Yet, their potential in biometric recognition and analysis remains relatively underexplored. In this work, we introduce a comprehensive benchmark that evaluates the zero-shot and few-shot performance of state-of-the-art publicly available VLMs and MLLMs across six biometric tasks spanning the face and iris modalities: face verification, soft biometric attribute prediction (gender and race), iris recognition, presentation attack detection (PAD), and face manipulation detection (morphs and deepfakes). A total of 41 VLMs were used in this evaluation. Experiments show that embeddings from these foundation models can be used for diverse biometric tasks with varying degrees of success. For example, in the case of face verification, a True Match Rate (TMR) of 96.77 percent was obtained at a False Match Rate (FMR) of 1 percent on the Labeled Face in the Wild (LFW) dataset, without any fine-tuning. In the case of iris recognition, the TMR at 1 percent FMR on the IITD-R-Full dataset was 97.55 percent without any fine-tuning. Further, we show that applying a simple classifier head to these embeddings can help perform DeepFake detection for faces, Presentation Attack Detection (PAD) for irides, and extract soft biometric attributes like gender and ethnicity from faces with reasonably high accuracy. This work reiterates the potential of pretrained models in achieving the long-term vision of Artificial General Intelligence.

[Arxiv](https://arxiv.org/abs/2505.24214)