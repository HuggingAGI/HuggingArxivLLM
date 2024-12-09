# 借助检索增强先验实现鲁棒的贝叶斯场景重建

发布时间：2024年11月28日

`其他` `3D 重建` `计算机视觉`

> Robust Bayesian Scene Reconstruction by Leveraging Retrieval-Augmented Priors

# 摘要

> 构建物体几何的 3D 表征对众多下游操作任务意义重大。这些表征得从可能含噪的局部观测中构建。在本研究中，我们聚焦于从单个 RGBD 图像重建多物体场景这一问题。当下针对此问题的深度学习方法面对有噪的真实世界观测和分布外物体时可能较为脆弱。其他不依赖训练数据的方法难以准确推断物体背面。我们提出了 BRRP 这一重建方法，它能够借助已有的网格数据集在稳健的概率重建中构建有价值的先验。为让我们的方法更高效，我们引入了检索增强先验的概念，即在推理过程中检索先验分布的相关组件。我们的方法生成了物体形状的分布，可用于重建或衡量不确定性。我们在程序生成的场景和真实世界场景中对我们的方法进行了评估。结果表明，我们的方法比深度学习方法更稳健，也比具有无价值先验的方法更精确。

> Constructing 3D representations of object geometry is critical for many downstream manipulation tasks. These representations must be built from potentially noisy partial observations. In this work we focus on the problem of reconstructing a multi-object scene from a single RGBD image. Current deep learning approaches to this problem can be brittle to noisy real world observations and out-of-distribution objects. Other approaches that do not rely on training data cannot accurately infer the backside of objects. We propose BRRP, a reconstruction method that can leverage preexisting mesh datasets to build an informative prior during robust probabilistic reconstruction. In order to make our method more efficient, we introduce the concept of retrieval-augmented prior, where we retrieve relevant components of our prior distribution during inference. Our method produces a distribution over object shape that can be used for reconstruction or measuring uncertainty. We evaluate our method in both procedurally generated scenes and in real world scenes. We show our method is more robust than a deep learning approach while being more accurate than a method with an uninformative prior.

[Arxiv](https://arxiv.org/abs/2411.19461)