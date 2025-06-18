# # GRAM：一款专为奖励泛化打造的生成式基础奖励模型

发布时间：2025年06月17日

`LLM理论

摘要中讨论了奖励模型的训练方法，包括结合无监督和监督学习，优化策略，以及生成模型与判别模型的统一，这些都是关于LLM的理论和训练方法的研究，属于LLM理论类别。` `人工智能` `机器学习`

> GRAM: A Generative Foundation Reward Model for Reward Generalization

# 摘要

> 在对齐大型语言模型（LLMs）的过程中，奖励模型虽扮演了关键角色，但传统上仅依赖标注的人类偏好数据进行训练。本文提出了一种创新方法，通过结合未标注和标注数据共同训练奖励模型。基于LLMs的生成能力，我们开发了一种生成式奖励模型，该模型首先通过大规模无监督学习进行训练，随后通过监督学习进行微调。我们还发现，通过标签平滑技术，实际上是在优化一个正则化的成对排名损失。这一发现为训练奖励模型提供了全新视角，将生成模型和判别模型统一在相同的训练目标框架下。最终，我们构建了一个基础奖励模型，它几乎无需额外微调即可广泛应用于多种任务。实验结果表明，该模型在响应排序、基于人类反馈的强化学习以及通过微调进行任务适应等多个任务中表现优异，显著超越了多个强大基线模型的性能。

> In aligning large language models (LLMs), reward models have played an important role, but are standardly trained as discriminative models and rely only on labeled human preference data. In this paper, we explore methods that train reward models using both unlabeled and labeled data. Building on the generative models in LLMs, we develop a generative reward model that is first trained via large-scale unsupervised learning and then fine-tuned via supervised learning. We also show that by using label smoothing, we are in fact optimizing a regularized pairwise ranking loss. This result, in turn, provides a new view of training reward models, which links generative models and discriminative models under the same class of training objectives. The outcome of these techniques is a foundation reward model, which can be applied to a wide range of tasks with little or no further fine-tuning effort. Extensive experiments show that this model generalizes well across several tasks, including response ranking, reinforcement learning from human feedback, and task adaptation with fine-tuning, achieving significant performance improvements over several strong baseline models.

[Arxiv](https://arxiv.org/abs/2506.14175)