# 多模态潜在变量用于跨个体的初级视觉皮层建模与分析

发布时间：2024年12月19日

`其他` `神经科学` `计算模型`

> Multi-Modal Latent Variables for Cross-Individual Primary Visual Cortex Modeling and Analysis

# 摘要

> 阐明初级视觉皮层（V1）的功能机制，在系统神经科学中一直是个基础难题。当下的计算模型存在两大关键局限，一是部分神经记录与复杂视觉刺激间的跨模态整合难题，二是个体神经特征的内在差异，包括神经元群体和放电模式的不同。为应对这些挑战，我们推出了一种多模态可识别变分自编码器（miVAE），它运用两级解缠策略，将神经活动和视觉刺激映射至统一的潜在空间。此框架通过精细的潜在空间建模，能够有力识别跨模态的相关性。我们还增添了一种新的基于分数的归因分析，能将潜在变量追溯至其在源数据空间的源头。在大规模小鼠 V1 数据集上的评估显示，我们的方法在跨个体潜在表示和对齐方面达到了领先水平，无需针对特定对象进行微调，且随着数据规模增大，性能更优。尤为重要的是，我们的归因算法成功识别出具有独特时间模式和刺激辨别特性的不同神经元亚群，同时揭示出对边缘特征和亮度变化具有特定敏感性的刺激区域。这种可扩展的框架不仅为 V1 研究的推进带来希望，也为神经科学更广泛的探索提供了可能。

> Elucidating the functional mechanisms of the primary visual cortex (V1) remains a fundamental challenge in systems neuroscience. Current computational models face two critical limitations, namely the challenge of cross-modal integration between partial neural recordings and complex visual stimuli, and the inherent variability in neural characteristics across individuals, including differences in neuron populations and firing patterns. To address these challenges, we present a multi-modal identifiable variational autoencoder (miVAE) that employs a two-level disentanglement strategy to map neural activity and visual stimuli into a unified latent space. This framework enables robust identification of cross-modal correlations through refined latent space modeling. We complement this with a novel score-based attribution analysis that traces latent variables back to their origins in the source data space. Evaluation on a large-scale mouse V1 dataset demonstrates that our method achieves state-of-the-art performance in cross-individual latent representation and alignment, without requiring subject-specific fine-tuning, and exhibits improved performance with increasing data size. Significantly, our attribution algorithm successfully identifies distinct neuronal subpopulations characterized by unique temporal patterns and stimulus discrimination properties, while simultaneously revealing stimulus regions that show specific sensitivity to edge features and luminance variations. This scalable framework offers promising applications not only for advancing V1 research but also for broader investigations in neuroscience.

[Arxiv](https://arxiv.org/abs/2412.14536)