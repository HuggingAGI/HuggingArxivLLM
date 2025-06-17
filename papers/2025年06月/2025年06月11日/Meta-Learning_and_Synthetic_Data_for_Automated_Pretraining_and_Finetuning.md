# 元学习与合成数据：用于自动化预训练与微调的创新方法

发布时间：2025年06月11日

`其他` `计算机视觉`

> Meta-Learning and Synthetic Data for Automated Pretraining and Finetuning

# 摘要

> 机器学习中预训练模型的激增为从业者带来了双重挑战：面对新数据集，需手动选择最优模型并调整超参数；同时，随着模型规模扩大，数据需求激增，传统自动机器学习难以应对。本论文采用元学习，将自动机器学习扩展到深度学习领域。我们提出基于任务知识的实证方法，用于计算机视觉任务中自动化 DL 管道选择，并通过学习代理模型对管道进行排名。将这些方法扩展到语言领域，我们学习如何微调大型语言模型，实验证明其表现超越基础模型。此外，我们通过元学习数据增强和合成数据，提升上流和下游任务性能。研究发现，自监督学习中数据增强的重要性被低估，我们元学习了先进的数据增强策略。利用合成数据，我们提出元学习神经合成数据生成器作为强化学习环境的代理。最后，我们通过仅使用随机采样的合成数据，以 in-context learning 方式学习多环境世界模型。

> The growing number of pretrained models in Machine Learning (ML) presents significant challenges for practitioners. Given a new dataset, they need to determine the most suitable deep learning (DL) pipeline, consisting of the pretrained model and the hyperparameters for finetuning to it. Moreover, as models grow in scale, the increasing reliance on real-world data poses a bottleneck for training and requires leveraging data more effectively. Addressing the first challenge often involves manual model selection and hyperparameter tuning. At the same time, as models grow larger and more and more of the available human-generated data is being used for training, data augmentation and synthetic data become critical elements. Automated machine learning offers a path to address these challenges but is traditionally designed for tabular data and classical ML methods. This dissertation adopts meta-learning to extend automated machine learning to the deep learning domain. We propose empirical approaches to automate DL pipeline selection for Computer Vision tasks using prior task knowledge to learn surrogate models for pipeline ranking. Extending these methods to the language domain, we learn to finetune large language models. As a result, we show that our approach can outperform finetuning foundation models. Additionally, we meta-learn data augmentation and synthetic data to enhance performance in up-stream and down-stream tasks. We empirically show the underestimated importance of data augmentation when using Self-Supervised Learning and meta-learn advanced data augmentation strategies. Leveraging synthetic data, we also propose to meta-learn neural synthetic data generators as proxies for Reinforcement Learning (RL) environments. Additionally, we learn a multiple-environment world model in an in-context learning fashion by purely using synthetic, randomly sampled data.

[Arxiv](https://arxiv.org/abs/2506.12161)