# # MetaCLIP 2：全球规模化的方案

发布时间：2025年07月29日

`LLM应用` `多模态` `计算机视觉`

> MetaCLIP 2: A Worldwide Scaling Recipe

# 摘要

> 对比语言-图像预训练（CLIP）是一种广受欢迎的基座模型，支持从零-shot分类、检索到多模态大型语言模型（MLLMs）的编码器功能。尽管CLIP已经在来自英语世界的数十亿级图像-文本对上取得了成功，但进一步将其训练规模扩展到全球网络数据仍然面临挑战：（1）缺乏能够处理非英语世界数据点的整理方法；（2）现有跨语言CLIP的英语性能不如其仅限于英语的版本，即类似于大型语言模型中常见的“多语言诅咒”。在这里，我们提出了MetaCLIP 2，这是首个从零开始基于全球网络规模图像-文本对训练CLIP的方案。为了验证我们的发现，我们进行了严格的消融实验，仅对解决上述挑战所必需的部分进行了最小的修改，并提出了一种使英语和非英语世界数据相互受益的方案。在零-shot ImageNet分类任务中，MetaCLIP 2的ViT-H/14版本比仅限于英语的版本高出0.8%，比mSigLIP高出0.7%，并且在多语言基准测试（如CVQA的57.4%、Babel-ImageNet的50.2%和XM3600的64.3%的图像到文本检索）中，意外地在没有系统级混杂因素（如翻译或专门的架构更改）的情况下达到了新的最先进水平。

> Contrastive Language-Image Pretraining (CLIP) is a popular foundation model, supporting from zero-shot classification, retrieval to encoders for multimodal large language models (MLLMs). Although CLIP is successfully trained on billion-scale image-text pairs from the English world, scaling CLIP's training further to learning from the worldwide web data is still challenging: (1) no curation method is available to handle data points from non-English world; (2) the English performance from existing multilingual CLIP is worse than its English-only counterpart, i.e., "curse of multilinguality" that is common in LLMs. Here, we present MetaCLIP 2, the first recipe training CLIP from scratch on worldwide web-scale image-text pairs. To generalize our findings, we conduct rigorous ablations with minimal changes that are necessary to address the above challenges and present a recipe enabling mutual benefits from English and non-English world data. In zero-shot ImageNet classification, MetaCLIP 2 ViT-H/14 surpasses its English-only counterpart by 0.8% and mSigLIP by 0.7%, and surprisingly sets new state-of-the-art without system-level confounding factors (e.g., translation, bespoke architecture changes) on multilingual benchmarks, such as CVQA with 57.4%, Babel-ImageNet with 50.2% and XM3600 with 64.3% on image-to-text retrieval.

[Arxiv](https://arxiv.org/abs/2507.22062)