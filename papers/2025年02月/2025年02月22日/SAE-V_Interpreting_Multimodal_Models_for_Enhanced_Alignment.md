# SAE-V: 解读多模态模型，优化对齐效果

发布时间：2025年02月22日

`LLM理论` `多模态大型语言模型` `模型可解释性`

> SAE-V: Interpreting Multimodal Models for Enhanced Alignment

# 摘要

> 图像模态的整合使得多模态大型语言模型（MLLMs）的语义空间比纯文本模型更加复杂，导致其可解释性更具挑战性，对齐稳定性更弱，尤其容易受到低质量数据的影响，从而引发模态间不一致、幻觉以及偏见输出等问题。因此，开发适用于MLLMs的可解释性方法对于提升对齐质量和效率至关重要。在纯文本的LLMs中，稀疏自动编码器（SAEs）因其能够解释潜在表示而受到关注。然而，将SAEs扩展到多模态环境由于模态融合和跨模态表示分离的难度而带来了新的挑战。为了解决这些挑战，我们引入了SAE-V，这是一个将SAE范式扩展到MLLMs的机制可解释性框架。通过识别和分析可解释特征及其对应的数据，SAE-V实现了对模型行为和数据质量的细粒度解释，从而促进了对跨模态交互和对齐动态的更深入理解。此外，通过利用跨模态特征加权，SAE-V提供了一种固有的数据过滤机制，可以在不使用额外模型的情况下提升模型对齐。具体而言，当应用于MLLMs的对齐过程时，基于SAE-V的数据过滤方法可以在使用不到50%的数据的情况下实现超过110%的性能提升。我们的结果突显了SAE-V在提升MLLMs的可解释性和对齐方面的有效性，为理解其内部机制提供了有价值的见解。


> With the integration of image modality, the semantic space of multimodal large language models (MLLMs) is more complex than text-only models, making their interpretability more challenging and their alignment less stable, particularly susceptible to low-quality data, which can lead to inconsistencies between modalities, hallucinations, and biased outputs. As a result, developing interpretability methods for MLLMs is crucial for improving alignment quality and efficiency. In text-only LLMs, Sparse Autoencoders (SAEs) have gained attention for their ability to interpret latent representations. However, extending SAEs to multimodal settings presents new challenges due to modality fusion and the difficulty of isolating cross-modal representations. To address these challenges, we introduce SAE-V, a mechanistic interpretability framework that extends the SAE paradigm to MLLMs. By identifying and analyzing interpretable features along with their corresponding data, SAE-V enables fine-grained interpretation of both model behavior and data quality, facilitating a deeper understanding of cross-modal interactions and alignment dynamics. Moreover, by utilizing cross-modal feature weighting, SAE-V provides an intrinsic data filtering mechanism to enhance model alignment without requiring additional models. Specifically, when applied to the alignment process of MLLMs, SAE-V-based data filtering methods could achieve more than 110% performance with less than 50% data. Our results highlight SAE-V's ability to enhance interpretability and alignment in MLLMs, providing insights into their internal mechanisms.

[Arxiv](https://arxiv.org/abs/2502.17514)