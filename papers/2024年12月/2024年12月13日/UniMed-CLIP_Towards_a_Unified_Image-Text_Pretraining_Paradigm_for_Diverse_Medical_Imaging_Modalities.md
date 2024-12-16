# UniMed-CLIP：致力于打造适用于多种医学成像模式的统一图像 - 文本预训练范式

发布时间：2024年12月13日

`LLM应用` `图像识别`

> UniMed-CLIP: Towards a Unified Image-Text Pretraining Paradigm for Diverse Medical Imaging Modalities

# 摘要

> 通过对比学习训练的视觉语言模型（VLMs）在自然图像任务中成绩斐然。然而，因公开可用的大规模医学图像-文本数据集稀缺，其在医学领域的应用受限。现有的医学 VLMs 要么基于闭源专有或规模较小的开源数据集训练，泛化能力欠佳；要么仅适用于单一或有限的医学成像领域，限制了在其他模式中的应用。为弥补这一差距，我们推出了 UniMed，这是一个大规模的开源多模态医学数据集，涵盖超过 530 万对六种不同成像模式（X 射线、CT、MRI、超声、病理学和眼底）的图像-文本对。UniMed 借助数据收集框架开发而成，该框架利用大型语言模型（LLMs）将特定模式的分类数据集转化为图像-文本格式，同时整合医学领域现有的图像-文本数据，助力可扩展的 VLM 预训练。基于 UniMed，我们训练了 UniMed-CLIP，这是一个适用于六种模式的统一 VLM，其表现远超现有的通才 VLMs，与特定模式的医学 VLMs 旗鼓相当，在零样本评估中收获显著成效。比如，UniMed-CLIP 在 21 个数据集上的平均绝对增益比 BiomedCLIP（基于专有数据训练）高出 +12.61，且训练数据用量减少 3 倍。为推动未来研究，我们在 https://github.com/mbzuai-oryx/UniMed-CLIP 上发布了 UniMed 数据集、训练代码及模型。

> Vision-Language Models (VLMs) trained via contrastive learning have achieved notable success in natural image tasks. However, their application in the medical domain remains limited due to the scarcity of openly accessible, large-scale medical image-text datasets. Existing medical VLMs either train on closed-source proprietary or relatively small open-source datasets that do not generalize well. Similarly, most models remain specific to a single or limited number of medical imaging domains, again restricting their applicability to other modalities. To address this gap, we introduce UniMed, a large-scale, open-source multi-modal medical dataset comprising over 5.3 million image-text pairs across six diverse imaging modalities: X-ray, CT, MRI, Ultrasound, Pathology, and Fundus. UniMed is developed using a data-collection framework that leverages Large Language Models (LLMs) to transform modality-specific classification datasets into image-text formats while incorporating existing image-text data from the medical domain, facilitating scalable VLM pretraining. Using UniMed, we trained UniMed-CLIP, a unified VLM for six modalities that significantly outperforms existing generalist VLMs and matches modality-specific medical VLMs, achieving notable gains in zero-shot evaluations. For instance, UniMed-CLIP improves over BiomedCLIP (trained on proprietary data) by an absolute gain of +12.61, averaged over 21 datasets, while using 3x less training data. To facilitate future research, we release UniMed dataset, training codes, and models at https://github.com/mbzuai-oryx/UniMed-CLIP.

[Arxiv](https://arxiv.org/abs/2412.10372)