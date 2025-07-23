# # 通过MLLM和LLM生成的高质量图像-文本数据集来增强遥感视觉语言模型

发布时间：2025年07月22日

`LLM应用` `数据生成`

> Enhancing Remote Sensing Vision-Language Models Through MLLM and LLM-Based High-Quality Image-Text Dataset Generation

# 摘要

> 视觉语言基础模型（VLFMs）在遥感图像（RS）中的应用因其卓越能力而备受关注，但高质量图像-文本数据的稀缺性是一个主要挑战。我们提出了一种名为MpGI的两阶段方法，通过多视角生成和融合技术，为遥感图像生成高质量描述。首先，我们利用Rule-MLLM接力生成和MLLMs生成方法，从不同角度提取独特细节；然后，通过大型语言模型将这些描述整合为全面的文本。我们还创建了包含21万遥感图像和130万描述的HQRS-IT-210K数据集，并基于此微调了CLIP和CoCa模型，推出了HQRS-CLIP和RS-CoCa。实验表明，HQRS-CLIP在仅4.2%的训练数据下超越了现有最优模型，而RS-CoCa生成的描述可与人工标注媲美。相关资源将在GitHub上开放。

> The application of Vision-language foundation models (VLFMs) to remote sensing (RS) imagery has garnered significant attention due to their superior capability in various downstream tasks. A key challenge lies in the scarcity of high-quality, large-scale, image-text paired training data. Recently, several works introduced extensive image-text datasets for RS and trained their VLFMs. However, due to the rudimentary methods used for generating captions, the quality of datasets is suboptimal, requiring larger volumes of training data, while only yielding modest performance improvements. In this paper, we propose a two-stage method named MpGI(Multi-Perspective Generation and Integration) for generating high-quality text captions for RS images. Firstly, we generate distinct and detailed descriptions from different perspectives using Rule-MLLM(Multimodal Large Language Model) Relay Generation and MLLMs generation methods. Next, we utilize Large Language Models (LLMs) to integrate these diverse descriptions into comprehensive captions, capturing details from multiple perspectives. Finally, we have created the HQRS-IT-210K dataset, including about 210,000 RS images and 1.3 million captions. We fine-tuned two VLFMs using our dataset: CLIP, a discriminative model, and CoCa, an image-to-text generative model. This process resulted in our proposed HQRS-CLIP and RS-CoCa models. Experimental results demonstrate that HQRS-CLIP surpassed the previous SOTA RS CLIP model in various downstream tasks while using only 4.2\% of the training data. RS-CoCa outperforms other advanced approaches across benchmark datasets and can generate captions for RS images that rival or even exceed manual annotations. Dataset, pre-trained models, and codes will be released at https://github.com/YiguoHe/HQRS-210K-and-HQRS-CLIP.

[Arxiv](https://arxiv.org/abs/2507.16716)