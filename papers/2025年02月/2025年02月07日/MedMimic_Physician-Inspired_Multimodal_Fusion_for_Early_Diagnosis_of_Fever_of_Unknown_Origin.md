# <翻译失败>

发布时间：2025年02月07日

`LLM应用

解释：这篇论文描述了一个名为MedMimic的多模态框架，它利用预训练模型（如DINOv2、Vision Transformer和ResNet-18）来处理高维医学影像数据，并结合临床数据进行分类。虽然论文中提到了预训练大模型，但主要关注的是如何将这些模型应用于医学影像和临床数据的融合分类任务，属于LLM在具体应用场景中的应用。因此，分类为LLM应用。` `影像诊断`

> MedMimic: Physician-Inspired Multimodal Fusion for Early Diagnosis of Fever of Unknown Origin

# 摘要

> 不明原因发热（FUO）的诊断依然充满挑战。MedMimic 是一个受真实诊断过程启发的多模态框架，利用 DINOv2、Vision Transformer 和 ResNet-18 等预训练模型，将高维 18F-FDG PET/CT 影像转化为低维语义特征。随后，一个基于自注意力的可学习融合网络将这些影像特征与临床数据结合，进行分类。基于四川大学华西医院 2017 年至 2023 年的 416 例 FUO 患者数据，多模态融合分类网络（MFCN）在七项任务中取得了 0.8654 到 0.9291 的宏 AUROC 分数，表现优于传统机器学习和单模态深度学习方法。消融实验和五折交叉验证进一步证明了其有效性。MedMimic 结合了预训练大模型和深度学习的优势，为疾病分类提供了极具潜力的解决方案。

> Fever of unknown origin FUO remains a diagnostic challenge. MedMimic is introduced as a multimodal framework inspired by real-world diagnostic processes. It uses pretrained models such as DINOv2, Vision Transformer, and ResNet-18 to convert high-dimensional 18F-FDG PET/CT imaging into low-dimensional, semantically meaningful features. A learnable self-attention-based fusion network then integrates these imaging features with clinical data for classification. Using 416 FUO patient cases from Sichuan University West China Hospital from 2017 to 2023, the multimodal fusion classification network MFCN achieved macro-AUROC scores ranging from 0.8654 to 0.9291 across seven tasks, outperforming conventional machine learning and single-modality deep learning methods. Ablation studies and five-fold cross-validation further validated its effectiveness. By combining the strengths of pretrained large models and deep learning, MedMimic offers a promising solution for disease classification.

[Arxiv](https://arxiv.org/abs/2502.04794)