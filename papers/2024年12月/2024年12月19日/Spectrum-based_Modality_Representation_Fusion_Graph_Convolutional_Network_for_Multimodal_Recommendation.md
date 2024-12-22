# 用于多模态推荐的基于频谱的模态表示融合图卷积网络

发布时间：2024年12月19日

`其他` `推荐系统` `多模态`

> Spectrum-based Modality Representation Fusion Graph Convolutional Network for Multimodal Recommendation

# 摘要

> 将多模态特征作为辅助信息融入推荐系统，近来已成为一种趋势。为了阐明用户与项目的偏好，近期的研究着重通过拼接、元素求和或注意力机制来融合模态。尽管成果显著，但现有的方法没有考虑到每个模态所包含的特定噪声。所以，直接融合模态会导致跨模态噪声的放大。而且，每个模态中独特的噪声变化，让噪声的缓解与融合更具难度。在本研究中，我们提出了一种新的基于频谱的模态表示（SMORE）融合图推荐器，旨在捕捉单模态和融合偏好的同时，抑制模态噪声。具体来说，SMORE 将多模态特征投射到频域，并利用频谱空间进行融合。为降低每个模态特有的动态污染，我们引入了一个滤波器，自适应地减弱和抑制模态噪声，同时有效地捕获通用模态模式。此外，我们通过设计一个新的多模态图学习模块来探索项目的潜在结构，以捕捉相似项目之间的关联语义相关性和通用融合模式。最后，我们制定了一个新的模态感知偏好模块，它融入行为特征，平衡单模态和多模态特征，进行精准的偏好建模。这使得 SMORE 能够更准确地推断用户特定模态和融合偏好。在三个真实世界数据集上的实验证明了我们所提出模型的有效性。本研究的源代码已在 https://github.com/kennethorq/SMORE 公开。

> Incorporating multi-modal features as side information has recently become a trend in recommender systems. To elucidate user-item preferences, recent studies focus on fusing modalities via concatenation, element-wise sum, or attention mechanisms. Despite having notable success, existing approaches do not account for the modality-specific noise encapsulated within each modality. As a result, direct fusion of modalities will lead to the amplification of cross-modality noise. Moreover, the variation of noise that is unique within each modality results in noise alleviation and fusion being more challenging. In this work, we propose a new Spectrum-based Modality Representation (SMORE) fusion graph recommender that aims to capture both uni-modal and fusion preferences while simultaneously suppressing modality noise. Specifically, SMORE projects the multi-modal features into the frequency domain and leverages the spectral space for fusion. To reduce dynamic contamination that is unique to each modality, we introduce a filter to attenuate and suppress the modality noise adaptively while capturing the universal modality patterns effectively. Furthermore, we explore the item latent structures by designing a new multi-modal graph learning module to capture associative semantic correlations and universal fusion patterns among similar items. Finally, we formulate a new modality-aware preference module, which infuses behavioral features and balances the uni- and multi-modal features for precise preference modeling. This empowers SMORE with the ability to infer both user modality-specific and fusion preferences more accurately. Experiments on three real-world datasets show the efficacy of our proposed model. The source code for this work has been made publicly available at https://github.com/kennethorq/SMORE.

[Arxiv](https://arxiv.org/abs/2412.14978)