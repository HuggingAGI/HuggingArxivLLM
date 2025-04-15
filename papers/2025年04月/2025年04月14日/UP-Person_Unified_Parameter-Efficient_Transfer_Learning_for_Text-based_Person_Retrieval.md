# # UP-Person：统一参数高效迁移学习用于基于文本的人员检索

发布时间：2025年04月14日

`LLM应用` `图像检索` `计算机视觉`

> UP-Person: Unified Parameter-Efficient Transfer Learning for Text-based Person Retrieval

# 摘要

> 文本到人检索（TPR）作为一种多模态任务，旨在根据文本描述从候选图像池中检索出目标人物，近期因对比视觉-语言预训练模型的进展而受到广泛关注。以往研究主要依赖预训练的CLIP模型提取人物视觉和文本特征，并对整个网络进行全参数微调，与单模态预训练模型相比展现出显著性能提升。然而，对大型模型进行全参数微调易导致过拟合，影响模型泛化能力。本文提出了一种新颖的基于参数高效迁移学习（PETL）的文本到人检索统一方法（UP-Person），旨在全面迁移CLIP的多模态知识。具体而言，UP-Person同时集成了三种轻量级PETL组件，包括Prefix、LoRA和Adapter，其中Prefix和LoRA协同设计，用于挖掘任务特定信息提示的局部信息，而Adapter则旨在调整全局特征表示。此外，还针对TPR任务的统一架构优化了两个基础子模块。一方面，提出了S-Prefix以增强前缀注意力并改进前缀令牌的梯度传播，从而提升基础前缀的灵活性和性能；另一方面，设计了与层归一化并行的L-Adapter，用于调节整体特征分布，有效解决多子模块之间重叠和交互引发的冲突。大量实验结果表明，我们的UP-Person在CUHK-PEDES、ICFG-PEDES和RSTPReid等多个人体检索数据集上均取得了当前最优的检索效果，且仅需微调4.7%的模型参数。代码已开源，地址为https://github.com/Liu-Yating/UP-Person。


> Text-based Person Retrieval (TPR) as a multi-modal task, which aims to retrieve the target person from a pool of candidate images given a text description, has recently garnered considerable attention due to the progress of contrastive visual-language pre-trained model. Prior works leverage pre-trained CLIP to extract person visual and textual features and fully fine-tune the entire network, which have shown notable performance improvements compared to uni-modal pre-training models. However, full-tuning a large model is prone to overfitting and hinders the generalization ability. In this paper, we propose a novel Unified Parameter-Efficient Transfer Learning (PETL) method for Text-based Person Retrieval (UP-Person) to thoroughly transfer the multi-modal knowledge from CLIP. Specifically, UP-Person simultaneously integrates three lightweight PETL components including Prefix, LoRA and Adapter, where Prefix and LoRA are devised together to mine local information with task-specific information prompts, and Adapter is designed to adjust global feature representations. Additionally, two vanilla submodules are optimized to adapt to the unified architecture of TPR. For one thing, S-Prefix is proposed to boost attention of prefix and enhance the gradient propagation of prefix tokens, which improves the flexibility and performance of the vanilla prefix. For another thing, L-Adapter is designed in parallel with layer normalization to adjust the overall distribution, which can resolve conflicts caused by overlap and interaction among multiple submodules. Extensive experimental results demonstrate that our UP-Person achieves state-of-the-art results across various person retrieval datasets, including CUHK-PEDES, ICFG-PEDES and RSTPReid while merely fine-tuning 4.7\% parameters. Code is available at https://github.com/Liu-Yating/UP-Person.

[Arxiv](https://arxiv.org/abs/2504.10084)