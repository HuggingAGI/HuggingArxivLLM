# HQ-CLIP：借助大型视觉-语言模型构建高质量图像-文本数据集和CLIP模型

发布时间：2025年07月30日

`LLM应用` `计算机视觉` `数据科学`

> HQ-CLIP: Leveraging Large Vision-Language Models to Create High-Quality Image-Text Datasets and CLIP Models

# 摘要

> 大规模但带有噪声的图像-文本配对数据为对比语言-图像预训练（CLIP）的成功铺就了道路。作为视觉编码器的基础，CLIP成为大多数大型视觉语言模型（LVLMs）的基石。这种相互依赖关系引发了一个有趣的问题：我们能否通过LVLMs提升图像-文本配对数据质量，开启自我增强的循环？我们提出了一种由LVLM驱动的数据精炼管道，利用LVLMs处理图像和原始替代文本，生成四种互补文本公式：长正描述、长负描述、短正标签和短负标签。将其应用于DFN-Large数据集，得到VLM-150M，一个带有丰富多粒度标注的精炼数据集。基于此，我们提出了一种扩展传统对比学习的训练范式，将负描述和短标签作为额外监督信号。由此产生的HQ-CLIP模型在各种基准测试中表现出色。在训练数据规模相当的情况下，HQ-CLIP在零样本分类、跨模态检索和细粒度视觉理解任务中均达到最先进水平。在检索基准测试中，HQ-CLIP甚至超越了基于DFN-2B数据集训练的标准CLIP模型，而该数据集的训练数据量是我们的10倍。所有代码、数据和模型均可在https://zxwei.site/hqclip获取。

> Large-scale but noisy image-text pair data have paved the way for the success of Contrastive Language-Image Pretraining (CLIP). As the foundation vision encoder, CLIP in turn serves as the cornerstone for most large vision-language models (LVLMs). This interdependence naturally raises an interesting question: Can we reciprocally leverage LVLMs to enhance the quality of image-text pair data, thereby opening the possibility of a self-reinforcing cycle for continuous improvement? In this work, we take a significant step toward this vision by introducing an LVLM-driven data refinement pipeline. Our framework leverages LVLMs to process images and their raw alt-text, generating four complementary textual formulas: long positive descriptions, long negative descriptions, short positive tags, and short negative tags. Applying this pipeline to the curated DFN-Large dataset yields VLM-150M, a refined dataset enriched with multi-grained annotations. Based on this dataset, we further propose a training paradigm that extends conventional contrastive learning by incorporating negative descriptions and short tags as additional supervised signals. The resulting model, namely HQ-CLIP, demonstrates remarkable improvements across diverse benchmarks. Within a comparable training data scale, our approach achieves state-of-the-art performance in zero-shot classification, cross-modal retrieval, and fine-grained visual understanding tasks. In retrieval benchmarks, HQ-CLIP even surpasses standard CLIP models trained on the DFN-2B dataset, which contains 10$\times$ more training data than ours. All code, data, and models are available at https://zxwei.site/hqclip.

[Arxiv](https://arxiv.org/abs/2507.22431)