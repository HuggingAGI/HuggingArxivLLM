# 循环视觉特征提取与立体注意力机制应用于CT报告生成

发布时间：2025年06月24日

`LLM应用` `人工智能`

> Recurrent Visual Feature Extraction and Stereo Attentions for CT Report Generation

# 摘要

> 生成CT图像报告是一项具有挑战性的任务，尽管与现有医学图像报告生成研究类似，但CT图像报告生成具有其独特特点，如多张图像的空间编码、图像体积与文本的对齐等。现有解决方案通常采用通用的2D或3D图像处理技术从CT体积中提取特征，其中他们首先压缩体积，然后将压缩后的CT切片分割成补丁进行视觉编码。这些方法并未明确考虑CT切片之间的变换关系，也未能有效整合多级图像特征，特别是那些包含特定器官病变的特征，以指导CT报告生成（CTRG）。考虑到CT扫描中连续切片之间的强相关性，在本文中，我们提出了一种基于大型语言模型（LLM）的CTRG方法，通过循环视觉特征提取和立体注意力机制实现层次化特征建模。具体而言，我们使用视觉Transformer循环处理CT体积中的每一张切片，并从不同角度对编码后的切片应用一组注意力机制，以选择性地获取重要视觉信息并将其与文本特征对齐，从而更好地指导LLM进行CTRG。在基准M3D-Cap数据集上的实验结果和进一步分析表明，我们的方法优于强基线模型，并达到了目前最优的性能，证明了其有效性和实用性。

> Generating reports for computed tomography (CT) images is a challenging task, while similar to existing studies for medical image report generation, yet has its unique characteristics, such as spatial encoding of multiple images, alignment between image volume and texts, etc. Existing solutions typically use general 2D or 3D image processing techniques to extract features from a CT volume, where they firstly compress the volume and then divide the compressed CT slices into patches for visual encoding. These approaches do not explicitly account for the transformations among CT slices, nor do they effectively integrate multi-level image features, particularly those containing specific organ lesions, to instruct CT report generation (CTRG). In considering the strong correlation among consecutive slices in CT scans, in this paper, we propose a large language model (LLM) based CTRG method with recurrent visual feature extraction and stereo attentions for hierarchical feature modeling. Specifically, we use a vision Transformer to recurrently process each slice in a CT volume, and employ a set of attentions over the encoded slices from different perspectives to selectively obtain important visual information and align them with textual features, so as to better instruct an LLM for CTRG. Experiment results and further analysis on the benchmark M3D-Cap dataset show that our method outperforms strong baseline models and achieves state-of-the-art results, demonstrating its validity and effectiveness.

[Arxiv](https://arxiv.org/abs/2506.19665)