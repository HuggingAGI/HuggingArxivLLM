# # 利用神经元元架构获取并适应新任务的先验知识

发布时间：2025年07月07日

`LLM应用` `计算化学` `计算免疫学`

> Acquiring and Adapting Priors for Novel Tasks via Neural Meta-Architectures

# 摘要

> 知识迁移能力是人类与计算模型等智能体的核心能力，它构成了迁移学习的基础。迁移学习通过微调大型预训练神经网络来适应下游任务，在任务适应速度与性能方面取得了巨大成功。然而，计算化学、计算免疫学和医学成像等领域由于数据匮乏，难以训练大型预训练模型。为应对这一挑战，我们专注于设计高效获取先验知识的架构。我们利用神经记忆实现仅凭少量样本即可适应非平稳分布，并通过元学习（MAML）训练的超网络设计获得更通用的先验知识。我们将超网络应用于3D场景生成，证明其能仅凭少量训练场景高效获取先验知识，从而实现更快的文本到3D生成。随后，我们将超网络框架扩展到有限数据下的3D场景分割，通过有效转移先前场景的先验知识实现这一目标。最后，我们将现有分子生成方法重新定位为预训练框架，提升分子性质预测能力，解决计算免疫学中的关键挑战。

> The ability to transfer knowledge from prior experiences to novel tasks stands as a pivotal capability of intelligent agents, including both humans and computational models. This principle forms the basis of transfer learning, where large pre-trained neural networks are fine-tuned to adapt to downstream tasks. Transfer learning has demonstrated tremendous success, both in terms of task adaptation speed and performance. However there are several domains where, due to lack of data, training such large pre-trained models or foundational models is not a possibility - computational chemistry, computational immunology, and medical imaging are examples. To address these challenges, our work focuses on designing architectures to enable efficient acquisition of priors when large amounts of data are unavailable. In particular, we demonstrate that we can use neural memory to enable adaptation on non-stationary distributions with only a few samples. Then we demonstrate that our hypernetwork designs (a network that generates another network) can acquire more generalizable priors than standard networks when trained with Model Agnostic Meta-Learning (MAML). Subsequently, we apply hypernetworks to 3D scene generation, demonstrating that they can acquire priors efficiently on just a handful of training scenes, thereby leading to faster text-to-3D generation. We then extend our hypernetwork framework to perform 3D segmentation on novel scenes with limited data by efficiently transferring priors from earlier viewed scenes. Finally, we repurpose an existing molecular generative method as a pre-training framework that facilitates improved molecular property prediction, addressing critical challenges in computational immunology

[Arxiv](https://arxiv.org/abs/2507.10446)