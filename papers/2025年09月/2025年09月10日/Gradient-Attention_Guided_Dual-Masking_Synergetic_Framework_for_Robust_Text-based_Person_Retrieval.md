# 梯度注意力引导的双掩码协同框架：面向鲁棒文本行人检索

发布时间：2025年09月10日

`LLM应用` `媒体与娱乐`

> Gradient-Attention Guided Dual-Masking Synergetic Framework for Robust Text-based Person Retrieval

# 摘要

> 尽管对比语言-图像预训练（CLIP）在各类视觉任务中表现出色，但其在人物表征学习中的应用面临两大关键挑战：（i）缺乏大规模以人为中心图像的标注视觉-语言数据；（ii）全局对比学习存在固有局限，难以保留细粒度匹配所需的判别性局部特征，同时易受噪声文本标记的干扰。本研究通过数据整理与模型架构的协同改进，推动CLIP在人物表征学习中的应用。首先，我们构建了抗噪声数据生成管道，利用多模态大型语言模型（MLLMs）的上下文学习能力，自动过滤并标注网络图像，由此得到WebPerson数据集——包含500万高质量以人为中心的图像-文本对的大规模数据集。其次，我们提出GA-DMS（梯度-注意力引导双掩码协同）框架，通过基于梯度-注意力相似度分数自适应掩盖噪声文本标记，提升跨模态对齐效果。此外，我们引入掩码标记预测目标，促使模型预测信息丰富的文本标记，从而增强细粒度语义表征学习。大量实验表明，GA-DMS在多个基准测试中均达到了最先进水平。

> Although Contrastive Language-Image Pre-training (CLIP) exhibits strong performance across diverse vision tasks, its application to person representation learning faces two critical challenges: (i) the scarcity of large-scale annotated vision-language data focused on person-centric images, and (ii) the inherent limitations of global contrastive learning, which struggles to maintain discriminative local features crucial for fine-grained matching while remaining vulnerable to noisy text tokens. This work advances CLIP for person representation learning through synergistic improvements in data curation and model architecture. First, we develop a noise-resistant data construction pipeline that leverages the in-context learning capabilities of MLLMs to automatically filter and caption web-sourced images. This yields WebPerson, a large-scale dataset of 5M high-quality person-centric image-text pairs. Second, we introduce the GA-DMS (Gradient-Attention Guided Dual-Masking Synergetic) framework, which improves cross-modal alignment by adaptively masking noisy textual tokens based on the gradient-attention similarity score. Additionally, we incorporate masked token prediction objectives that compel the model to predict informative text tokens, enhancing fine-grained semantic representation learning. Extensive experiments show that GA-DMS achieves state-of-the-art performance across multiple benchmarks.

[Arxiv](https://arxiv.org/abs/2509.09118)