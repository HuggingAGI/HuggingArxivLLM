# NoLoCo: 无all-reduce的低通信训练方法，适用于大规模模型

发布时间：2025年06月12日

`LLM理论` `人工智能` `分布式计算`

> NoLoCo: No-all-reduce Low Communication Training Method for Large Models

# 摘要

> 训练大型语言模型通常需要在包含数万加速器的集群上通过优化方法进行，这些加速器通过高速互联网络进行通信。然而，扩展这些集群的成本高昂，且可能变得不切实际，从而限制了可训练模型的规模。近期的一些研究提出了通信开销较低的训练方法，避免了对高度互联计算集群的需求。这些最新的低通信训练方法仍然采用了一个模型参数同步步骤，当在所有模型副本上执行时，在低带宽网络上可能会变得昂贵。

在本研究中，我们提出了一种新颖的优化方法NoLoCo，在训练过程中不显式地同步所有模型参数，因此不需要任何集体通信。NoLoCo通过一种Nesterov动量优化器的新变体，通过部分平均模型权重与随机选择的另一个模型权重，从而隐式地同步模型权重。我们为我们的优化器提供了理论收敛性分析，并通过语言模型训练的实证结果进行了验证。

我们在不同数量的加速器和不同规模的模型上对NoLoCo进行了基准测试，范围从1.25亿到68亿个参数。我们的方法在通信开销上表现出显著优势，相比完全分片的数据并行训练，甚至是最广泛应用的低通信训练方法DiLoCo，都需要显著更高的通信开销。在几百个加速器通过互联网进行训练时，同步步骤本身的估计速度比DiLoCo中使用的all-reduce快一个数量级。我们也没有任何全局阻塞通信，从而减少了加速器的空闲时间。与DiLoCo相比，我们在广泛的模型规模和加速器数量范围内观察到高达4%的更快收敛速度。


> Training large language models is generally done via optimization methods on clusters containing tens of thousands of accelerators, communicating over a high-bandwidth interconnect. Scaling up these clusters is expensive and can become impractical, imposing limits on the size of models that can be trained. Several recent studies have proposed training methods that are less communication intensive, avoiding the need for a highly connected compute cluster. These state-of-the-art low communication training methods still employ a synchronization step for model parameters, which, when performed over all model replicas, can become costly on a low-bandwidth network.
  In this work, we propose a novel optimization method, NoLoCo, that does not explicitly synchronize all model parameters during training and, as a result, does not require any collective communication. NoLoCo implicitly synchronizes model weights via a novel variant of the Nesterov momentum optimizer by partially averaging model weights with a randomly selected other one. We provide both a theoretical convergence analysis for our proposed optimizer as well as empirical results from language model training.
  We benchmark NoLoCo on a wide range of accelerator counts and model sizes, between 125M to 6.8B parameters. Our method requires significantly less communication overhead than fully sharded data parallel training or even widely used low communication training method, DiLoCo. The synchronization step itself is estimated to be one magnitude faster than the all-reduce used in DiLoCo for few hundred accelerators training over the internet. We also do not have any global blocking communication that reduces accelerator idling time. Compared to DiLoCo, we also observe up to $4\%$ faster convergence rate with wide range of model sizes and accelerator counts.

[Arxiv](https://arxiv.org/abs/2506.10911)