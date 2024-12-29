# 用于图像分类的 LMM 正则化 CLIP 嵌入

发布时间：2024年12月16日

`LLM应用` `图像分类` `视觉语言模型`

> LMM-Regularized CLIP Embeddings for Image Classification

# 摘要

> 在本文中，我们借助强大的 CLIP 视觉语言模型来处理图像分类任务。我们旨在通过提出一种新颖的基于大型多模态模型（LMM）的正则化方法，提升 CLIP 图像编码器的分类性能。该方法利用 LMM 为数据集中的图像提取语义描述，然后使用冻结的 CLIP 文本编码器获取相应的文本嵌入并计算平均语义类别描述。接着，我们给 CLIP 图像编码器添加分类头，并将其与图像编码器的输出一同训练，除了主要的分类目标外，还设有一个额外的辅助目标。这个额外目标促使图像编码器输出的嵌入与相应的 LMM 生成的平均语义类别描述趋于相似。如此一来，便能生成判别能力更强的嵌入，进而提高分类性能。所提正则化方法的有效性在三个图像分类数据集上的大量实验中得到了验证。

> In this paper we deal with image classification tasks using the powerful CLIP vision-language model. Our goal is to advance the classification performance using the CLIP's image encoder, by proposing a novel Large Multimodal Model (LMM) based regularization method. The proposed method uses an LMM to extract semantic descriptions for the images of the dataset. Then, it uses the CLIP's text encoder, frozen, in order to obtain the corresponding text embeddings and compute the mean semantic class descriptions. Subsequently, we adapt the CLIP's image encoder by adding a classification head, and we train it along with the image encoder output, apart from the main classification objective, with an additional auxiliary objective. The additional objective forces the embeddings at the image encoder's output to become similar to their corresponding LMM-generated mean semantic class descriptions. In this way, it produces embeddings with enhanced discrimination ability, leading to improved classification performance. The effectiveness of the proposed regularization method is validated through extensive experiments on three image classification datasets.

[Arxiv](https://arxiv.org/abs/2412.11663)