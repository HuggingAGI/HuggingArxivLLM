# 统一的 HT-CNNs 架构：实现从神经胶质瘤到儿科肿瘤等各类脑瘤在 MRI 中的分割迁移学习

发布时间：2024年12月11日

`其他` `医学图像分割`

> Unified HT-CNNs Architecture: Transfer Learning for Segmenting Diverse Brain Tumors in MRI from Gliomas to Pediatric Tumors

# 摘要

> 从 3D 多模态 MRI 中精确分割脑肿瘤，对各类脑肿瘤的诊断和治疗规划意义重大。本文应对 BraTS 2023 带来的挑战，给出了一种适用于更广泛脑肿瘤的统一迁移学习方法。我们引入了 HT-CNNs，它是混合变压器与卷积神经网络通过迁移学习优化后的集成体，用于多种脑肿瘤的分割。此方法能从 MRI 数据中捕捉空间和上下文细节，并在代表常见肿瘤类型的不同数据集上进行微调。借助迁移学习，HT-CNNs 利用在一个任务中习得的表征来提升在另一任务中的泛化能力，充分发挥在大型数据集上预训练模型的优势，并针对特定肿瘤类型进行微调。我们对来自多个国际来源的不同数据集进行预处理，确保涵盖最常见的脑肿瘤类型。我们严格的评估在所有肿瘤类型中采用标准化定量指标，以保证稳健性和泛化性。所提出的集成模型在 BraTS 验证数据集上的分割结果优于先前的优胜方法。通过 DSC 和 HD95 进行的综合定量评估证明了我们方法的有效性。定性分割预测进一步验证了我们模型生成的高质量输出。我们的研究成果突显了迁移学习和集成方法在医学图像分割中的潜力，表明在临床决策和患者护理方面有显著提升。尽管面临着与后处理和领域差异相关的挑战，我们的研究为脑肿瘤分割的未来研究树立了新标杆。代码和模型的 Docker 镜像已公开可用，https://hub.docker.com/r/razeineldin/ht-cnns。

> Accurate segmentation of brain tumors from 3D multimodal MRI is vital for diagnosis and treatment planning across diverse brain tumors. This paper addresses the challenges posed by the BraTS 2023, presenting a unified transfer learning approach that applies to a broader spectrum of brain tumors. We introduce HT-CNNs, an ensemble of Hybrid Transformers and Convolutional Neural Networks optimized through transfer learning for varied brain tumor segmentation. This method captures spatial and contextual details from MRI data, fine-tuned on diverse datasets representing common tumor types. Through transfer learning, HT-CNNs utilize the learned representations from one task to improve generalization in another, harnessing the power of pre-trained models on large datasets and fine-tuning them on specific tumor types. We preprocess diverse datasets from multiple international distributions, ensuring representativeness for the most common brain tumors. Our rigorous evaluation employs standardized quantitative metrics across all tumor types, ensuring robustness and generalizability. The proposed ensemble model achieves superior segmentation results across the BraTS validation datasets over the previous winning methods. Comprehensive quantitative evaluations using the DSC and HD95 demonstrate the effectiveness of our approach. Qualitative segmentation predictions further validate the high-quality outputs produced by our model. Our findings underscore the potential of transfer learning and ensemble approaches in medical image segmentation, indicating a substantial enhancement in clinical decision-making and patient care. Despite facing challenges related to post-processing and domain gaps, our study sets a new precedent for future research for brain tumor segmentation. The docker image for the code and models has been made publicly available, https://hub.docker.com/r/razeineldin/ht-cnns.

[Arxiv](https://arxiv.org/abs/2412.08240)