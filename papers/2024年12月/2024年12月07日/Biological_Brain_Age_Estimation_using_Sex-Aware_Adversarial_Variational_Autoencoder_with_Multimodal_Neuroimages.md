# 利用具有多模态神经影像的性别感知对抗变分自编码器来估计生物大脑年龄

发布时间：2024年12月07日

`其他` `神经科学`

> Biological Brain Age Estimation using Sex-Aware Adversarial Variational Autoencoder with Multimodal Neuroimages

# 摘要

> 大脑老化会带来结构和功能的改变，所以是大脑健康的关键生物标志物。将结构磁共振成像（sMRI）与功能磁共振成像（fMRI）相结合，有望借助互补数据优化大脑年龄的估算。然而，fMRI 数据比 sMRI 更嘈杂，这让多模态融合变得复杂。传统融合方法引入的噪声往往多于有用信息，与单独使用 sMRI 相比，可能会降低准确性。在本文中，我们提出了一种用于生物大脑年龄估算的新型多模态框架，采用了性别感知的对抗变分自编码器（SA-AVAE）。我们的框架融合了对抗和变分学习，能有效地从两种模态中分离出潜在特征。具体而言，我们把潜在空间分解为模态特定代码和共享代码，分别代表跨模态的互补信息和共同信息。为增强分离效果，我们引入了交叉重建和共享-不同距离比损失作为正则化项。重要的是，我们把性别信息纳入学习的潜在代码中，使模型能够通过集成回归器模块捕捉特定性别的大脑老化模式来估算大脑年龄。我们使用公开的 OpenBHB 数据集对模型进行评估，这是一个用于大脑年龄估算的综合多站点数据集。消融研究结果以及与前沿方法的对比表明，我们的框架优于现有方法，在不同年龄组中都表现出显著的稳健性，凸显了其在神经退行性疾病早期检测实时临床应用方面的潜力。

> Brain aging involves structural and functional changes and therefore serves as a key biomarker for brain health. Combining structural magnetic resonance imaging (sMRI) and functional magnetic resonance imaging (fMRI) has the potential to improve brain age estimation by leveraging complementary data. However, fMRI data, being noisier than sMRI, complicates multimodal fusion. Traditional fusion methods often introduce more noise than useful information, which can reduce accuracy compared to using sMRI alone. In this paper, we propose a novel multimodal framework for biological brain age estimation, utilizing a sex-aware adversarial variational autoencoder (SA-AVAE). Our framework integrates adversarial and variational learning to effectively disentangle the latent features from both modalities. Specifically, we decompose the latent space into modality-specific codes and shared codes to represent complementary and common information across modalities, respectively. To enhance the disentanglement, we introduce cross-reconstruction and shared-distinct distance ratio loss as regularization terms. Importantly, we incorporate sex information into the learned latent code, enabling the model to capture sex-specific aging patterns for brain age estimation via an integrated regressor module. We evaluate our model using the publicly available OpenBHB dataset, a comprehensive multi-site dataset for brain age estimation. The results from ablation studies and comparisons with state-of-the-art methods demonstrate that our framework outperforms existing approaches and shows significant robustness across various age groups, highlighting its potential for real-time clinical applications in the early detection of neurodegenerative diseases.

[Arxiv](https://arxiv.org/abs/2412.05632)