# SimCroP：相似性驱动的跨粒度预训练放射影像表征学习

发布时间：2025年09月10日

`其他` `医疗健康`

> SimCroP: Radiograph Representation Learning with Similarity-driven Cross-granularity Pre-training

# 摘要

> 医学视觉语言预训练在从海量配对影像报告中学习代表性特征方面展现出巨大潜力。然而，在计算机断层扫描（CT）中，含复杂结构的病变在空间分布上具有稀疏性。此外，报告各句不同病理描述与其影像对应子区域间的复杂隐性关联，进一步增加了任务难度。本文提出一种用于胸部CT的相似度驱动跨粒度预训练（SimCroP）框架，通过融合相似度驱动对齐与跨粒度融合机制，提升影像解读能力。该框架首先采用多模态掩码建模优化编码器，从影像中提取精确的低级语义；接着设计相似度驱动对齐模块，预训练编码器自适应筛选并对齐报告中每个句子对应的图像补丁；跨粒度融合模块则整合实例级与词-补丁级的多模态信息，助力模型精准捕捉稀疏影像中的关键病理结构，进而提升多尺度下游任务的性能。SimCroP在大规模CT-报告配对数据集上完成预训练，并在五个公共数据集上的图像分类与分割任务中验证效果。实验结果表明，其性能超越了当前主流的医学自监督学习方法与医学视觉语言预训练方法。代码与模型已开源至https://github.com/ToniChopp/SimCroP。

> Medical vision-language pre-training shows great potential in learning representative features from massive paired radiographs and reports. However, in computed tomography (CT) scans, the distribution of lesions which contain intricate structures is characterized by spatial sparsity. Besides, the complex and implicit relationships between different pathological descriptions in each sentence of the report and their corresponding sub-regions in radiographs pose additional challenges. In this paper, we propose a Similarity-Driven Cross-Granularity Pre-training (SimCroP) framework on chest CTs, which combines similarity-driven alignment and cross-granularity fusion to improve radiograph interpretation. We first leverage multi-modal masked modeling to optimize the encoder for understanding precise low-level semantics from radiographs. Then, similarity-driven alignment is designed to pre-train the encoder to adaptively select and align the correct patches corresponding to each sentence in reports. The cross-granularity fusion module integrates multimodal information across instance level and word-patch level, which helps the model better capture key pathology structures in sparse radiographs, resulting in improved performance for multi-scale downstream tasks. SimCroP is pre-trained on a large-scale paired CT-reports dataset and validated on image classification and segmentation tasks across five public datasets. Experimental results demonstrate that SimCroP outperforms both cutting-edge medical self-supervised learning methods and medical vision-language pre-training methods. Codes and models are available at https://github.com/ToniChopp/SimCroP.

[Arxiv](https://arxiv.org/abs/2509.08311)