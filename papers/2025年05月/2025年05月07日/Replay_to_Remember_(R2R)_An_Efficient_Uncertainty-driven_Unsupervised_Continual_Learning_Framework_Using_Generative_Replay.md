# 重放以记住（R2R）：一个高效、基于不确定性驱动的无监督持续学习框架，采用生成式重放技术

发布时间：2025年05月07日

`其他` `人工智能` `机器学习`

> Replay to Remember (R2R): An Efficient Uncertainty-driven Unsupervised Continual Learning Framework Using Generative Replay

# 摘要

> 持续学习旨在在获取新知识的同时保留旧知识，从而有效缓解神经网络中的“灾难性遗忘”问题。我们提出了一种名为“Replay to Remember (R2R)”的不确定性驱动无监督持续学习新框架，基于生成式重放技术。R2R架构通过集群级不确定性驱动反馈机制和视觉语言模型（VLM）驱动的生成式重放模块，高效利用无标签和合成标签数据。与依赖预训练模型和伪标签的传统内存缓冲方法不同，我们的R2R框架无需任何前期训练。它利用无标签数据的视觉特征，并通过基于聚类的不确定性估计结合动态阈值调整，实现持续适应。同时，生成式重放机制配合DeepSeek-R1驱动的CLIP视觉语言模型，生成代表过去经验的标签合成数据，类似于生物视觉思维通过重放记忆来应对新任务。我们在CIFAR-10、CIFAR-100、CINIC-10、SVHN和TinyImageNet数据集上进行了广泛实验分析。我们的R2R方法显著提升了知识保留能力，分别达到了98.13%、73.06%、93.41%、95.18%和59.74%的最先进性能，超越现有最先进方法超过4.36%。

> Continual Learning entails progressively acquiring knowledge from new data while retaining previously acquired knowledge, thereby mitigating ``Catastrophic Forgetting'' in neural networks. Our work presents a novel uncertainty-driven Unsupervised Continual Learning framework using Generative Replay, namely ``Replay to Remember (R2R)''. The proposed R2R architecture efficiently uses unlabelled and synthetic labelled data in a balanced proportion using a cluster-level uncertainty-driven feedback mechanism and a VLM-powered generative replay module. Unlike traditional memory-buffer methods that depend on pretrained models and pseudo-labels, our R2R framework operates without any prior training. It leverages visual features from unlabeled data and adapts continuously using clustering-based uncertainty estimation coupled with dynamic thresholding. Concurrently, a generative replay mechanism along with DeepSeek-R1 powered CLIP VLM produces labelled synthetic data representative of past experiences, resembling biological visual thinking that replays memory to remember and act in new, unseen tasks. Extensive experimental analyses are carried out in CIFAR-10, CIFAR-100, CINIC-10, SVHN and TinyImageNet datasets. Our proposed R2R approach improves knowledge retention, achieving a state-of-the-art performance of 98.13%, 73.06%, 93.41%, 95.18%, 59.74%, respectively, surpassing state-of-the-art performance by over 4.36%.

[Arxiv](https://arxiv.org/abs/2505.04787)