# 基于标记的最优传输方法实现眼科疾病分级与诊断的鲁棒不完全模态对齐

发布时间：2025年07月07日

`其他` `计算机视觉`

> Robust Incomplete-Modality Alignment for Ophthalmic Disease Grading and Diagnosis via Labeled Optimal Transport

# 摘要

> 基于多模态眼科成像的诊断通过整合彩色眼底图像与光学相干断层扫描（OCT），为眼部疾病提供了全面的视角。然而，全球医疗资源分布的不均衡常常导致实际临床中遇到不完整多模态数据，这大大降低了诊断的准确性。现有常用的管线，如模态插补和蒸馏方法，存在明显局限性：1)插补方法难以准确重构关键病灶特征，因为OCT病灶具有局部性，而眼底图像风格多样。2)蒸馏方法严重依赖完全配对的多模态训练数据。为了解决这些问题，我们提出了一种新型的多模态对齐与融合框架，能够 robustly 处理眼科诊断任务中缺失的模态。通过考虑OCT和眼底图像的特征特性，我们强调同一类别内语义特征的对齐，并显式地学习模态间的软匹配，使缺失模态能够利用现有模态信息，在缺失模态下实现 robust 的跨模态特征对齐。具体来说，我们利用最优传输进行多尺度模态特征对齐：通过预测的类别原型进行类别级对齐，通过跨模态共享特征传输进行特征级对齐。此外，我们提出了一种非对称融合策略，有效利用OCT和眼底图像模态的独特特性。在三个大型眼科多模态数据集上的广泛评估表明，我们的模型在各种模态不完整场景下表现出色，在完整模态和跨模态不完整条件下均达到 Sota 性能。代码可在 https://github.com/Qinkaiyu/RIMA 获取

> Multimodal ophthalmic imaging-based diagnosis integrates color fundus image with optical coherence tomography (OCT) to provide a comprehensive view of ocular pathologies. However, the uneven global distribution of healthcare resources often results in real-world clinical scenarios encountering incomplete multimodal data, which significantly compromises diagnostic accuracy. Existing commonly used pipelines, such as modality imputation and distillation methods, face notable limitations: 1)Imputation methods struggle with accurately reconstructing key lesion features, since OCT lesions are localized, while fundus images vary in style. 2)distillation methods rely heavily on fully paired multimodal training data. To address these challenges, we propose a novel multimodal alignment and fusion framework capable of robustly handling missing modalities in the task of ophthalmic diagnostics. By considering the distinctive feature characteristics of OCT and fundus images, we emphasize the alignment of semantic features within the same category and explicitly learn soft matching between modalities, allowing the missing modality to utilize existing modality information, achieving robust cross-modal feature alignment under the missing modality. Specifically, we leverage the Optimal Transport for multi-scale modality feature alignment: class-wise alignment through predicted class prototypes and feature-wise alignment via cross-modal shared feature transport. Furthermore, we propose an asymmetric fusion strategy that effectively exploits the distinct characteristics of OCT and fundus modalities. Extensive evaluations on three large ophthalmic multimodal datasets demonstrate our model's superior performance under various modality-incomplete scenarios, achieving Sota performance in both complete modality and inter-modality incompleteness conditions. Code is available at https://github.com/Qinkaiyu/RIMA

[Arxiv](https://arxiv.org/abs/2507.04999)