# 超越可见：面向地球观测的多光谱视觉语言学习

发布时间：2025年03月20日

`LLM应用` `地球观测`

> Beyond the Visible: Multispectral Vision-Language Learning for Earth Observation

# 摘要

> 现有地球观测（EO）领域的视觉-语言模型大多仅依赖视觉光谱作为输入，忽视了卫星多光谱通道中蕴含的丰富光谱信息。为此，我们推出了Llama3-MS-CLIP——首个基于大规模多光谱数据集通过对比学习预训练的视觉-语言模型，展现了扩展光谱范围带来的显著性能提升。

我们还构建了目前规模最大的多光谱图像-文本描述数据集，包含一百万个Sentinel-2样本及其由Llama3-LLaVA-Next和Overture Maps数据生成的文本描述。开发的可扩展图像描述生成管道已通过领域专家验证。

在不同复杂度的三个数据集上进行的多光谱零样本图像分类和检索评估表明，Llama3-MS-CLIP相较于其他RGB基线模型，在分类准确率上平均提升了6.77%，在检索性能上实现了4.63% mAP的提升。这充分证明了多光谱视觉-语言学习的重要性。

我们将图像-文本描述数据集、代码和模型权重以开源形式发布，供研究者们共同探索。


> Vision-language models for Earth observation (EO) typically rely on the visual spectrum of data as the only model input, thus failing to leverage the rich spectral information available in the multispectral channels recorded by satellites. Therefore, in this paper, we introduce Llama3-MS-CLIP, the first vision-language model pre-trained with contrastive learning on a large-scale multispectral dataset and report on the performance gains due to the extended spectral range. Furthermore, we present the largest-to-date image-caption dataset for multispectral data, consisting of one million Sentinel-2 samples and corresponding textual descriptions generated with Llama3-LLaVA-Next and Overture Maps data. We develop a scalable captioning pipeline, which is validated by domain experts. We evaluate Llama3-MS-CLIP on multispectral zero-shot image classification and retrieval using three datasets of varying complexity. Our results demonstrate that Llama3-MS-CLIP significantly outperforms other RGB-based approaches, improving classification accuracy by 6.77% on average and retrieval performance by 4.63% mAP compared to the second-best model. Our results emphasize the relevance of multispectral vision-language learning. We release the image-caption dataset, code, and model weights under an open-source license.

[Arxiv](https://arxiv.org/abs/2503.15969)