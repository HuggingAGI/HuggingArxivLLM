# GCA-3D：致力于实现 3D 生成器的广义且一致的领域适应

发布时间：2024年12月19日

`其他` `3D 生成` `图像领域`

> GCA-3D: Towards Generalized and Consistent Domain Adaptation of 3D Generators

# 摘要

> 近来，3D 生成领域适应崭露头角，无需收集海量数据集和相机姿态分布，就能让预训练的生成器适配其他领域。一般来说，它们借助大规模预训练的文本到图像扩散模型为目标领域合成图像，再对 3D 模型进行微调。但它们受困于数据生成的繁琐流程，不可避免地在源域和合成数据集之间产生姿态偏差。而且，它们无法普遍支持一次性图像引导的领域适应，由于单个图像参考引入了更严重的姿态偏差和额外的身份偏差，这更具挑战性。为应对这些问题，我们提出 GCA-3D，一种通用且一致的 3D 领域适应方法，无需复杂的数据生成流程。与以往的流程方法不同，我们引入多模态深度感知分数蒸馏采样损失，以非对抗的方式高效适配 3D 生成模型。这种多模态损失让 GCA-3D 能在文本提示和一次性图像提示适应中发挥作用。此外，它利用体积渲染模块中的每个实例深度图来减轻过拟合问题，并保持结果的多样性。为增强姿态和身份的一致性，我们还进一步提出分层空间一致性损失，以对齐源域和目标域中生成图像的空间结构。实验表明，GCA-3D 在效率、泛化能力、姿态准确性和身份一致性方面均优于以往方法。

> Recently, 3D generative domain adaptation has emerged to adapt the pre-trained generator to other domains without collecting massive datasets and camera pose distributions. Typically, they leverage large-scale pre-trained text-to-image diffusion models to synthesize images for the target domain and then fine-tune the 3D model. However, they suffer from the tedious pipeline of data generation, which inevitably introduces pose bias between the source domain and synthetic dataset. Furthermore, they are not generalized to support one-shot image-guided domain adaptation, which is more challenging due to the more severe pose bias and additional identity bias introduced by the single image reference. To address these issues, we propose GCA-3D, a generalized and consistent 3D domain adaptation method without the intricate pipeline of data generation. Different from previous pipeline methods, we introduce multi-modal depth-aware score distillation sampling loss to efficiently adapt 3D generative models in a non-adversarial manner. This multi-modal loss enables GCA-3D in both text prompt and one-shot image prompt adaptation. Besides, it leverages per-instance depth maps from the volume rendering module to mitigate the overfitting problem and retain the diversity of results. To enhance the pose and identity consistency, we further propose a hierarchical spatial consistency loss to align the spatial structure between the generated images in the source and target domain. Experiments demonstrate that GCA-3D outperforms previous methods in terms of efficiency, generalization, pose accuracy, and identity consistency.

[Arxiv](https://arxiv.org/abs/2412.15491)