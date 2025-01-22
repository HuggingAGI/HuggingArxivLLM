# 一个通用的3D框架与模型，助力医学影像自监督学习

发布时间：2025年01月20日

`其他

理由：这篇论文主要讨论的是3D医学影像的自监督学习方法，特别是提出了3DINO框架和3DINO-ViT模型。虽然涉及到了大规模数据集和预训练模型，但其核心内容与Agent、RAG、LLM应用或LLM理论无关，因此应归类为“其他”。` `医学影像`

> A generalizable 3D framework and model for self-supervised learning in medical imaging

# 摘要

> 当前3D医学影像的自监督学习方法依赖简单的预训练任务和特定器官或模态的数据集，限制了其通用性和扩展性。我们提出了3DINO，一种前沿的自监督学习方法，并在包含约10万次3D医学影像扫描的超大规模、多模态、多器官数据集上预训练了通用医学影像模型3DINO-ViT。通过大量实验验证，3DINO-ViT在跨模态、跨器官的任务中表现出色，包括分布外任务和数据集，在大多数评估指标和标注数据集规模上超越了现有最先进的方法。3DINO框架和3DINO-ViT将开源，推动3D基础模型研究及广泛医学影像应用的微调。

> Current self-supervised learning methods for 3D medical imaging rely on simple pretext formulations and organ- or modality-specific datasets, limiting their generalizability and scalability. We present 3DINO, a cutting-edge SSL method adapted to 3D datasets, and use it to pretrain 3DINO-ViT: a general-purpose medical imaging model, on an exceptionally large, multimodal, and multi-organ dataset of ~100,000 3D medical imaging scans from over 10 organs. We validate 3DINO-ViT using extensive experiments on numerous medical imaging segmentation and classification tasks. Our results demonstrate that 3DINO-ViT generalizes across modalities and organs, including out-of-distribution tasks and datasets, outperforming state-of-the-art methods on the majority of evaluation metrics and labeled dataset sizes. Our 3DINO framework and 3DINO-ViT will be made available to enable research on 3D foundation models or further finetuning for a wide range of medical imaging applications.

[Arxiv](https://arxiv.org/abs/2501.11755)