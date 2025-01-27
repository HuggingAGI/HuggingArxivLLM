# 单神经元深度生成模型揭示了钙成像数据中神经元活动的底层物理规律

发布时间：2025年01月24日

`其他

理由：这篇论文主要讨论的是钙成像技术和深度生成模型在神经科学中的应用，特别是自回归变分自编码器（AVAEs）在单神经元表示学习中的应用。虽然涉及深度生成模型，但内容与Agent、RAG、LLM应用或LLM理论无关，因此归类为“其他”。` `神经科学`

> Single-neuron deep generative model uncovers underlying physics of neuronal activity in Ca imaging data

# 摘要

> # 摘要
钙成像技术以其高空间分辨率和微创测量大量神经元的能力，成为研究神经元活动的有力工具，广泛应用于神经科学、神经工程和医学领域。近年来，深度生成模型（DGMs）的突破使得神经元群体动态建模成为可能，揭示了潜在表示，为行为预测和神经元变异提供了新视角。然而，这些模型通常依赖尖峰推断算法，且主要关注群体层面的动态，限制了其在单神经元分析中的应用。为此，我们提出了一种基于自回归变分自编码器（AVAEs）的单神经元表示学习框架。该方法无需尖峰推断算法，即可将单个神经元的时空信号嵌入到降维空间中。AVAEs生成的潜在表示更具信息性和区分性，显著提升了可视化、聚类和神经元活动理解等任务的效果。此外，AVAEs在重建性能上超越了现有技术，能够从学习到的表示中准确恢复原始荧光信号。通过真实模拟，我们展示了该模型能够捕捉潜在的物理特性和连接模式，从而区分不同的放电和连接类型。这些发现表明，AVAEs是推进单神经元分析的多功能强大工具，并为未来整合多模态单细胞数据集奠定了基础。

> Calcium imaging has become a powerful alternative to electrophysiology for studying neuronal activity, offering spatial resolution and the ability to measure large populations of neurons in a minimally invasive manner. This technique has broad applications in neuroscience, neuroengineering, and medicine, enabling researchers to explore the relationship between neuron location and activity. Recent advancements in deep generative models (DGMs) have facilitated the modeling of neuronal population dynamics, uncovering latent representations that provide insights into behavior prediction and neuronal variance. However, these models often rely on spike inference algorithms and primarily focus on population-level dynamics, limiting their applicability for single-neuron analyses. To address this gap, we propose a novel framework for single-neuron representation learning using autoregressive variational autoencoders (AVAEs). Our approach embeds individual neurons' spatiotemporal signals into a reduced-dimensional space without the need for spike inference algorithms. The AVAE excels over traditional linear methods by generating more informative and discriminative latent representations, improving tasks such as visualization, clustering, and the understanding of neuronal activity. Additionally, the reconstruction performance of the AVAE outperforms the state of the art, demonstrating its ability to accurately recover the original fluorescence signal from the learned representation. Using realistic simulations, we show that our model captures underlying physical properties and connectivity patterns, enabling it to distinguish between different firing and connectivity types. These findings position the AVAE as a versatile and powerful tool for advancing single-neuron analysis and lays the groundwork for future integration of multimodal single-cell datasets in neuroscience.

[Arxiv](https://arxiv.org/abs/2501.14615)