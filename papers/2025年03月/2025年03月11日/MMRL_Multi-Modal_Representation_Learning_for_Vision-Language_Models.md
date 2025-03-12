# MMRL: 视觉-语言模型的多模态表征学习

发布时间：2025年03月11日

`LLM理论` `计算机视觉` `多模态学习`

> MMRL: Multi-Modal Representation Learning for Vision-Language Models

# 摘要

> 大规模预训练的视觉语言模型（VLMs）已成为跨任务迁移学习的重要工具。然而，使用有限的少量样本数据调整这些模型时，往往会导致过拟合，从而降低其在新任务上的表现。为了解决这一问题，我们提出了一种新型的多模态表示学习（MMRL）框架。该框架引入了一个共享的、可学习的、模态无关的表示空间，通过将空间标记投影到文本和图像表示标记，促进更有效的多模态交互。与之前仅优化类标记特征的方法不同，MMRL将表示标记集成到编码器的高层——在这些层中，数据集特定的特征更为突出——同时保留了低层中的通用知识。在训练过程中，同时优化了表示和类特征。对表示标记应用了可训练的投影层，而类标记的投影层保持冻结以保留预训练的知识。此外，引入了一个正则化项，使类特征和文本特征与冻结的VLM的零样本特征对齐，从而保障了模型的泛化能力。在推理时，采用了解耦策略，其中基类同时使用表示和类特征，而新任务仅使用保留了更多通用知识的类特征。在15个数据集上的广泛实验表明，MMRL在特定任务适应和泛化之间取得了平衡，优于现有的最先进方法。代码可在https://github.com/yunncheng/MMRL获取。

> Large-scale pre-trained Vision-Language Models (VLMs) have become essential for transfer learning across diverse tasks. However, adapting these models with limited few-shot data often leads to overfitting, diminishing their performance on new tasks. To tackle this issue, we propose a novel Multi-Modal Representation Learning (MMRL) framework that introduces a shared, learnable, and modality-agnostic representation space. MMRL projects the space tokens to text and image representation tokens, facilitating more effective multi-modal interactions. Unlike previous approaches that solely optimize class token features, MMRL integrates representation tokens at higher layers of the encoders--where dataset-specific features are more prominent--while preserving generalized knowledge in the lower layers. During training, both representation and class features are optimized, with trainable projection layer applied to the representation tokens, whereas the class token projection layer remains frozen to retain pre-trained knowledge. Furthermore, a regularization term is introduced to align the class features and text features with the zero-shot features from the frozen VLM, thereby safeguarding the model's generalization capacity. For inference, a decoupling strategy is employed, wherein both representation and class features are utilized for base classes, while only the class features, which retain more generalized knowledge, are used for new tasks. Extensive experiments across 15 datasets demonstrate that MMRL outperforms state-of-the-art methods, achieving a balanced trade-off between task-specific adaptation and generalization. Code is available at https://github.com/yunncheng/MMRL.

[Arxiv](https://arxiv.org/abs/2503.08497)