# 人类基于单视图模型的多视图合成：转移的身体与面部表征

发布时间：2024年12月03日

`其他` `图像生成` `人体模型`

> Human Multi-View Synthesis from a Single-View Model:Transferred Body and Face Representations

# 摘要

> 从单一视图生成多视图人体图像颇具难度且意义重大。尽管多视图对象生成领域的最新进展在扩散模型方面成果斐然，但由于 3D 人体数据集的可用性有限，人类新视图的合成仍受制约。正因如此，众多现有模型难以塑造逼真的人体形态，也无法精准捕捉面部的细微细节。为应对这些难题，我们提出了一个创新框架，借助转移的身体和面部表征来实现多视图人体合成。具体来说，我们利用在大规模人体数据集上预训练的单视图模型来开发多视图身体表征，旨在将单视图模型的 2D 知识拓展至多视图扩散模型。另外，为提升模型的细节还原能力，我们把转移的多模态面部特征融入到训练的人体扩散模型中。在基准数据集上的实验评估显示，我们的方法优于当前的先进方法，在多视图人体合成方面表现卓越。

> Generating multi-view human images from a single view is a complex and significant challenge. Although recent advancements in multi-view object generation have shown impressive results with diffusion models, novel view synthesis for humans remains constrained by the limited availability of 3D human datasets. Consequently, many existing models struggle to produce realistic human body shapes or capture fine-grained facial details accurately. To address these issues, we propose an innovative framework that leverages transferred body and facial representations for multi-view human synthesis. Specifically, we use a single-view model pretrained on a large-scale human dataset to develop a multi-view body representation, aiming to extend the 2D knowledge of the single-view model to a multi-view diffusion model. Additionally, to enhance the model's detail restoration capability, we integrate transferred multimodal facial features into our trained human diffusion model. Experimental evaluations on benchmark datasets demonstrate that our approach outperforms the current state-of-the-art methods, achieving superior performance in multi-view human synthesis.

[Arxiv](https://arxiv.org/abs/2412.03011)