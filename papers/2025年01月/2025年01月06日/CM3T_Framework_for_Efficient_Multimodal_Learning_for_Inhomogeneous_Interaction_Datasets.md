# CM3T：非均匀交互数据集的高效多模态学习框架

发布时间：2025年01月06日

`LLM应用

理由：这篇论文提出了一种新的模型无关插件架构CM3T，用于跨学习，使基于Transformer的模型能够适应新信息或缺失信息。虽然论文中提到了迁移学习和适配器等技术，但核心内容是关于如何改进和扩展基于Transformer的模型（如LLM）以适应新的任务和数据。因此，这篇论文应归类为LLM应用。` `视频分类` `多模态学习`

> CM3T: Framework for Efficient Multimodal Learning for Inhomogeneous Interaction Datasets

# 摘要

> 跨学习的挑战在于训练数据的不均匀甚至不足，以及缺乏重新训练大型预训练模型的资源。受NLP中迁移学习技术、适配器和前缀调优的启发，本文提出了一种新的模型无关插件架构CM3T，用于跨学习，使基于Transformer的模型能够适应新信息或缺失信息。我们引入了两个适配器模块：用于迁移学习的多头视觉适配器和用于多模态学习的交叉注意力适配器。由于骨干网络和其他插件无需与这些新增部分一起微调，训练效率大幅提升。在Epic-Kitchens-100、MPIIGroupInteraction和UDIVA v0.5三个数据集上的比较和消融研究表明，该框架在不同记录设置和任务中表现出色。与处理视频输入的骨干网络相比，仅需12.8%的可训练参数，对于两种额外模态，仅需22.3%的可训练参数，我们实现了与最先进技术相当甚至更好的结果。CM3T对训练或预训练无特定要求，是迈向弥合通用模型与视频分类具体实际应用之间差距的重要一步。

> Challenges in cross-learning involve inhomogeneous or even inadequate amount of training data and lack of resources for retraining large pretrained models. Inspired by transfer learning techniques in NLP, adapters and prefix tuning, this paper presents a new model-agnostic plugin architecture for cross-learning, called CM3T, that adapts transformer-based models to new or missing information. We introduce two adapter blocks: multi-head vision adapters for transfer learning and cross-attention adapters for multimodal learning. Training becomes substantially efficient as the backbone and other plugins do not need to be finetuned along with these additions. Comparative and ablation studies on three datasets Epic-Kitchens-100, MPIIGroupInteraction and UDIVA v0.5 show efficacy of this framework on different recording settings and tasks. With only 12.8% trainable parameters compared to the backbone to process video input and only 22.3% trainable parameters for two additional modalities, we achieve comparable and even better results than the state-of-the-art. CM3T has no specific requirements for training or pretraining and is a step towards bridging the gap between a general model and specific practical applications of video classification.

[Arxiv](https://arxiv.org/abs/2501.03332)