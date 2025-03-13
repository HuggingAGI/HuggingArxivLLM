# 地理空间基础模型的参数高效适配方法论：通过嵌入偏转实现

发布时间：2025年03月12日

`LLM应用` `地球科学` `环境科学`

> Parameter-Efficient Adaptation of Geospatial Foundation Models through Embedding Deflection

# 摘要

> 大规模异构数据集的普及使低成本适配基础模型成为重要议题。自然语言处理领域的开创性工作如低秩适配（LoRA）利用了参数更新过程中的固有低秩特性。本文提出，通过在数据和模型中引入更强的归纳偏置，可以提升基于RGB卫星图像预训练的地理空间基础模型（GFMs）对其他光学卫星数据的适配能力。具体而言，GFMs的预训练参数为多光谱图像的空间结构提供了一个强大的先验。为此，我们提出DEFLECT（用于地球与气候任务的潜在表征微调嵌入偏转），这是一种仅需极少额外参数即可将GFMs适配到多光谱卫星图像的新型策略。DEFLECT提升了提取特征的表现能力，尤其是增强了光谱信息的处理，这对地球科学和环境相关任务至关重要。我们在三种不同的GFMs和五个多样化的数据集上验证了方法的有效性，涵盖森林监测到海洋环境分割等领域。与现有方法相比，DEFLECT在分类和分割任务中以5到10倍更少的参数实现了相当或更高的精度。代码将公开发布。

> As large-scale heterogeneous data sets become increasingly available, adapting foundation models at low cost has become a key issue. Seminal works in natural language processing, e.g. Low-Rank Adaptation (LoRA), leverage the low "intrinsic rank" of parameter updates during adaptation. In this paper, we argue that incorporating stronger inductive biases in both data and models can enhance the adaptation of Geospatial Foundation Models (GFMs), pretrained on RGB satellite images, to other types of optical satellite data. Specifically, the pretrained parameters of GFMs serve as a strong prior for the spatial structure of multispectral images. For this reason, we introduce DEFLECT (Deflecting Embeddings for Finetuning Latent representations for Earth and Climate Tasks), a novel strategy for adapting GFMs to multispectral satellite imagery with very few additional parameters. DEFLECT improves the representation capabilities of the extracted features, particularly enhancing spectral information, which is essential for geoscience and environmental-related tasks. We demonstrate the effectiveness of our method across three different GFMs and five diverse datasets, ranging from forest monitoring to marine environment segmentation. Compared to competing methods, DEFLECT achieves on-par or higher accuracy with 5-10$\times$ fewer parameters for classification and segmentation tasks. The code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2503.09493)