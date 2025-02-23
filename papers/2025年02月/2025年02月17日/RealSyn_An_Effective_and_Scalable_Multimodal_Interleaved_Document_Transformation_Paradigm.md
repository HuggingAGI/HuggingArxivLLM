# RealSyn：高效且可扩展的多模态交错文档转换范式

发布时间：2025年02月17日

`其他` `计算机视觉` `数据科学`

> RealSyn: An Effective and Scalable Multimodal Interleaved Document Transformation Paradigm

# 摘要

> CLIP在大量图像-文本配对数据预训练后，在多种基准测试中表现优异。然而，多模态交错文档等未配对数据在视觉语言学习中尚未得到充分利用。为此，我们首先开发了一个真实数据提取管道，高效提取高质量图像和文本。接着，设计了层次化检索方法，将每张图像与多个语义相关的现实文本关联。为增强细粒度视觉信息，我们提出了图像语义增强生成模块，用于生成合成文本。此外，采用语义平衡采样策略，提升数据多样性，助力长尾概念学习。基于这些创新，我们构建了结合现实与合成文本的RealSyn数据集，提供15M、30M和100M三种规模。实验证明，RealSyn显著提升了视觉语言表示学习，并展现出强大的扩展性。在RealSyn上预训练的模型在多个下游任务中达到了顶尖水平。为促进研究，RealSyn数据集和预训练模型权重已开源，地址为https://github.com/deepglint/RealSyn。

> After pre-training on extensive image-text pairs, Contrastive Language-Image Pre-training (CLIP) demonstrates promising performance on a wide variety of benchmarks. However, a substantial volume of non-paired data, such as multimodal interleaved documents, remains underutilized for vision-language representation learning. To fully leverage these unpaired documents, we initially establish a Real-World Data Extraction pipeline to extract high-quality images and texts. Then we design a hierarchical retrieval method to efficiently associate each image with multiple semantically relevant realistic texts. To further enhance fine-grained visual information, we propose an image semantic augmented generation module for synthetic text production. Furthermore, we employ a semantic balance sampling strategy to improve dataset diversity, enabling better learning of long-tail concepts. Based on these innovations, we construct RealSyn, a dataset combining realistic and synthetic texts, available in three scales: 15M, 30M, and 100M. Extensive experiments demonstrate that RealSyn effectively advances vision-language representation learning and exhibits strong scalability. Models pre-trained on RealSyn achieve state-of-the-art performance on multiple downstream tasks. To facilitate future research, the RealSyn dataset and pre-trained model weights are released at https://github.com/deepglint/RealSyn.

[Arxiv](https://arxiv.org/abs/2502.12513)