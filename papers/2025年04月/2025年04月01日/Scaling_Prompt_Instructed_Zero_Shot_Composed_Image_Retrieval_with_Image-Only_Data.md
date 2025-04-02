# # 通过仅图像数据扩展提示指令下的零样本合成图像检索

发布时间：2025年04月01日

`LLM应用

摘要讨论了利用大型语言模型（LLMs）在合成图像检索任务中的应用，展示了LLMs在生成数据和结合图像-文本模态方面的有效性，属于LLM的应用研究。` `计算机视觉`

> Scaling Prompt Instructed Zero Shot Composed Image Retrieval with Image-Only Data

# 摘要

> 合成图像检索 (CIR) 是一项基于参考图像和自然语言描述的图像检索任务。传统方法依赖于包含参考图像、改写文本和目标图像的三元组数据进行训练。然而，这类数据的整理需要大量人工干预，导致成本高昂且难以扩展。借助基础模型的最新进展，我们提出了一种全新的 CIR 训练范式，通过大型语言模型 (LLMs) 高效替代人工标注。具体而言，我们展示了大型标注和语言模型在无标注图像集合上生成 CIR 数据的强大能力。此外，我们提出了一种创新的嵌入式改写架构，能够有效结合图像和文本模态。我们的模型 InstructCIR 在 CIRR 和 FashionIQ 数据集上的零样本合成图像检索任务中超越了现有最优方法。进一步研究表明，通过增加生成数据的数量，我们的零样本模型性能能够显著逼近监督基线水平。

> Composed Image Retrieval (CIR) is the task of retrieving images matching a reference image augmented with a text, where the text describes changes to the reference image in natural language. Traditionally, models designed for CIR have relied on triplet data containing a reference image, reformulation text, and a target image. However, curating such triplet data often necessitates human intervention, leading to prohibitive costs. This challenge has hindered the scalability of CIR model training even with the availability of abundant unlabeled data. With the recent advances in foundational models, we advocate a shift in the CIR training paradigm where human annotations can be efficiently replaced by large language models (LLMs). Specifically, we demonstrate the capability of large captioning and language models in efficiently generating data for CIR only relying on unannotated image collections. Additionally, we introduce an embedding reformulation architecture that effectively combines image and text modalities. Our model, named InstructCIR, outperforms state-of-the-art methods in zero-shot composed image retrieval on CIRR and FashionIQ datasets. Furthermore, we demonstrate that by increasing the amount of generated data, our zero-shot model gets closer to the performance of supervised baselines.

[Arxiv](https://arxiv.org/abs/2504.00812)