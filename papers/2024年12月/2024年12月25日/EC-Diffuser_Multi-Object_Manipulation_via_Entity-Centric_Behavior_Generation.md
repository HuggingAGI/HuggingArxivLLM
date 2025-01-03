# EC-Diffuser: 基于实体行为生成的多对象操控

发布时间：2024年12月25日

`Agent

理由：这篇论文主要讨论了一种新颖的行为克隆（BC）方法，用于从高维观察中学习操控物体，特别是在多物体环境中。该方法利用物体中心表示和基于扩散优化的实体中心Transformer，能够从离线图像数据中高效学习，并实现组合泛化。论文的核心是开发一种能够处理复杂任务的智能代理（Agent），因此将其分类为Agent。` `机器人` `物体操控`

> EC-Diffuser: Multi-Object Manipulation via Entity-Centric Behavior Generation

# 摘要

> # 摘要
物体操控是日常任务中的常见部分，但从高维观察中学习操控物体面临巨大挑战。在多物体环境中，由于状态空间和期望行为的组合复杂性，这些挑战尤为突出。尽管最近的方法利用大规模离线数据从像素观察中训练模型，通过扩展实现性能提升，但这些方法在未见过的物体配置中，由于网络和数据集的规模限制，难以实现组合泛化。为此，我们提出了一种新颖的行为克隆（BC）方法，利用物体中心表示和基于扩散优化的实体中心Transformer，能够从离线图像数据中高效学习。我们的方法首先将观察分解为物体中心表示，然后由实体中心Transformer处理，该Transformer在物体级别计算注意力，同时预测物体动态和代理的动作。结合扩散模型捕捉多模态行为分布的能力，这显著提升了多物体任务的性能，更重要的是，实现了组合泛化。我们展示了能够在训练中未见过的物体和目标组合任务中实现零-shot泛化的BC代理，包括比训练中见过的更多数量的物体。更多视频展示请访问我们的网页：https://sites.google.com/view/ec-diffuser。

> Object manipulation is a common component of everyday tasks, but learning to manipulate objects from high-dimensional observations presents significant challenges. These challenges are heightened in multi-object environments due to the combinatorial complexity of the state space as well as of the desired behaviors. While recent approaches have utilized large-scale offline data to train models from pixel observations, achieving performance gains through scaling, these methods struggle with compositional generalization in unseen object configurations with constrained network and dataset sizes. To address these issues, we propose a novel behavioral cloning (BC) approach that leverages object-centric representations and an entity-centric Transformer with diffusion-based optimization, enabling efficient learning from offline image data. Our method first decomposes observations into an object-centric representation, which is then processed by our entity-centric Transformer that computes attention at the object level, simultaneously predicting object dynamics and the agent's actions. Combined with the ability of diffusion models to capture multi-modal behavior distributions, this results in substantial performance improvements in multi-object tasks and, more importantly, enables compositional generalization. We present BC agents capable of zero-shot generalization to tasks with novel compositions of objects and goals, including larger numbers of objects than seen during training. We provide video rollouts on our webpage: https://sites.google.com/view/ec-diffuser.

[Arxiv](https://arxiv.org/abs/2412.18907)