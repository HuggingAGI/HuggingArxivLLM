# MLLM-SUL：多模态大语言模型在交通场景中的语义理解与定位

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了如何利用多模态大型语言模型（MLLMs）来解决自动驾驶任务中的联合语义场景理解和风险定位问题。论文提出了一个名为MLLM-SUL的框架，该框架结合了视觉编码器和微调的LLaMA模型来生成场景描述和定位风险对象。这些工作都是将大型语言模型应用于具体的实际问题（自动驾驶），因此属于LLM应用的范畴。` `自动驾驶` `语义理解`

> MLLM-SUL: Multimodal Large Language Model for Semantic Scene Understanding and Localization in Traffic Scenarios

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在自动驾驶任务中表现出色。本文利用MLLMs解决联合语义场景理解和风险定位任务，仅依赖前视图像。我们提出的MLLM-SUL框架首先设计了一个双分支视觉编码器，从不同分辨率中提取特征，丰富的视觉信息有助于语言模型准确描述不同大小的风险对象。接着，微调LLaMA模型以生成场景描述，包括驾驶场景类型、风险对象动作以及自车的驾驶意图和建议。最后，训练了一个包含回归标记的transformer网络来定位风险对象。在DRAMA-ROLISP和扩展的DRAMA-SRIS数据集上的实验表明，我们的方法高效且优于许多基于图像和视频的先进方法。具体而言，我们的方法在场景理解任务中取得了80.1%的BLEU-1分数和298.5%的CIDEr分数，在定位任务中达到了59.6%的准确率。代码和数据集可在https://github.com/fjq-tongji/MLLM-SUL获取。

> Multimodal large language models (MLLMs) have shown satisfactory effects in many autonomous driving tasks. In this paper, MLLMs are utilized to solve joint semantic scene understanding and risk localization tasks, while only relying on front-view images. In the proposed MLLM-SUL framework, a dual-branch visual encoder is first designed to extract features from two resolutions, and rich visual information is conducive to the language model describing risk objects of different sizes accurately. Then for the language generation, LLaMA model is fine-tuned to predict scene descriptions, containing the type of driving scenario, actions of risk objects, and driving intentions and suggestions of ego-vehicle. Ultimately, a transformer-based network incorporating a regression token is trained to locate the risk objects. Extensive experiments on the existing DRAMA-ROLISP dataset and the extended DRAMA-SRIS dataset demonstrate that our method is efficient, surpassing many state-of-the-art image-based and video-based methods. Specifically, our method achieves 80.1% BLEU-1 score and 298.5% CIDEr score in the scene understanding task, and 59.6% accuracy in the localization task. Codes and datasets are available at https://github.com/fjq-tongji/MLLM-SUL.

[Arxiv](https://arxiv.org/abs/2412.19406)