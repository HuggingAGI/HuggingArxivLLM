# T2Vid：将长文本转化为多图像乃视频-LLM 的催化剂

发布时间：2024年12月02日

`LLM应用` `多模态`

> T2Vid: Translating Long Text into Multi-Image is the Catalyst for Video-LLMs

# 摘要

> 多模态大型语言模型（MLLMs）在图像领域的成功备受研究界关注。基于过往成功经验，研究人员近来尝试将其拓展至视频理解领域。除了从零开始训练，有效途径之一是运用预训练的图像-LLMs，由此产生了两种主流方法，即零样本推理和利用视频数据进一步微调。在本研究中，我们对这些方法的探索收获了一种有效的数据增强手段。我们先是深入探究了零样本推理方式，发现了两个局限，即泛化能力有限和缺乏时间理解能力。接着，我们进一步研究微调方法，发现单纯使用所有视频数据样本时学习效率低，原因在于指令多样性的缺失。针对此问题，我们开发了名为 T2Vid 的方法来合成类视频样本，以丰富训练语料中的指令多样性。整合这些数据形成了一种简便高效的训练方案，仅用 15%的样本量训练就能取得与使用完整视频数据集相当甚至更优的性能。同时，我们发现该方案无需用长视频样本训练就能提升长视频理解的性能。我们期望本研究能引发更多关于运用 MLLMs 进行视频理解和高质量数据策划的思考。代码发布于 https://github.com/xjtupanda/T2Vid 。

> The success of Multimodal Large Language Models (MLLMs) in the image domain has garnered wide attention from the research community. Drawing on previous successful experiences, researchers have recently explored extending the success to the video understanding realms. Apart from training from scratch, an efficient way is to utilize the pre-trained image-LLMs, leading to two mainstream approaches, i.e. zero-shot inference and further fine-tuning with video data. In this work, our study of these approaches harvests an effective data augmentation method. We first make a deeper inspection of the zero-shot inference way and identify two limitations, i.e. limited generalization and lack of temporal understanding capabilities. Thus, we further investigate the fine-tuning approach and find a low learning efficiency when simply using all the video data samples, which can be attributed to a lack of instruction diversity. Aiming at this issue, we develop a method called T2Vid to synthesize video-like samples to enrich the instruction diversity in the training corpus. Integrating these data enables a simple and efficient training scheme, which achieves performance comparable to or even superior to using full video datasets by training with just 15% the sample size. Meanwhile, we find that the proposed scheme can boost the performance of long video understanding without training with long video samples. We hope our study will spark more thinking about using MLLMs for video understanding and curation of high-quality data. The code is released at https://github.com/xjtupanda/T2Vid.

[Arxiv](https://arxiv.org/abs/2411.19951)