# SCENEFORGE：借助结构化场景组合提升3D-文本对齐

发布时间：2025年09月19日

`LLM应用` `工业与制造`

> SCENEFORGE: Enhancing 3D-text alignment with Structured Scene Compositions

# 摘要

> 整体大于部分之和——这一理念在3D-文本对比学习中同样适用。为此，我们提出SceneForge——一种新颖框架，它通过结构化的多物体场景组合增强3D点云和文本间的对比对齐。SceneForge借助单个3D形状构建具有明确空间关系的多物体场景，并为其匹配由大型语言模型优化的连贯多物体描述。通过这类结构化组合样本增强对比训练，SceneForge有效缓解了大规模3D-文本数据集稀缺的难题，大幅提升了数据的复杂性与多样性。我们还系统探究了关键设计要素，包括单一场景的最佳物体数量、训练批次中组合样本的占比以及场景构建策略。大量实验证实，SceneForge在多项任务中均实现了显著性能提升，涵盖ModelNet、ScanObjNN、Objaverse-LVIS和ScanNet上的零样本分类，以及ShapeNetPart上的少样本部分分割。SceneForge的组合增强方法具有模型无关性，能在多种编码器架构上稳定提升性能。此外，SceneForge在ScanQA数据集上提升了3D视觉问答表现，面对场景复杂性递增的检索任务时泛化能力稳健，还能通过调整空间配置精确匹配文本指令，展现出强大的空间推理能力。

> The whole is greater than the sum of its parts-even in 3D-text contrastive learning. We introduce SceneForge, a novel framework that enhances contrastive alignment between 3D point clouds and text through structured multi-object scene compositions. SceneForge leverages individual 3D shapes to construct multi-object scenes with explicit spatial relations, pairing them with coherent multi-object descriptions refined by a large language model. By augmenting contrastive training with these structured, compositional samples, SceneForge effectively addresses the scarcity of large-scale 3D-text datasets, significantly enriching data complexity and diversity. We systematically investigate critical design elements, such as the optimal number of objects per scene, the proportion of compositional samples in training batches, and scene construction strategies. Extensive experiments demonstrate that SceneForge delivers substantial performance gains across multiple tasks, including zero-shot classification on ModelNet, ScanObjNN, Objaverse-LVIS, and ScanNet, as well as few-shot part segmentation on ShapeNetPart. SceneForge's compositional augmentations are model-agnostic, consistently improving performance across multiple encoder architectures. Moreover, SceneForge improves 3D visual question answering on ScanQA, generalizes robustly to retrieval scenarios with increasing scene complexity, and showcases spatial reasoning capabilities by adapting spatial configurations to align precisely with textual instructions.

[Arxiv](https://arxiv.org/abs/2509.15693)