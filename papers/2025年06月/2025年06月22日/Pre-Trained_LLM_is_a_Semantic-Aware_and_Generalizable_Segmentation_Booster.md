# # 预训练的LLM：语义感知型的通用分段提升工具

发布时间：2025年06月22日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLM）应用于医学图像分割任务，属于LLM的具体应用。` `医学影像` `图像分割`

> Pre-Trained LLM is a Semantic-Aware and Generalizable Segmentation Booster

# 摘要

> 随着大型语言模型（LLM）在自然语言处理领域的突破，本文发现一个令人兴奋的现象：冻结的预训练LLM层能够处理视觉标记，用于医学图像分割任务。我们提出了一种简单的混合结构，将预训练且冻结的LLM层集成到CNN编码器-解码器分割框架中（LLM4Seg）。令人惊喜的是，这一设计在超声、皮肤镜、结肠镜和CT扫描等多种医学影像模态下，仅需增加少量可训练参数，就显著提升了分割性能。深入分析表明，将LLM的语义理解能力迁移至分割任务中，能够同时提升全局理解与局部建模能力。这一改进在不同LLM中表现稳健，已在LLaMA和DeepSeek上得到验证。

> With the advancement of Large Language Model (LLM) for natural language processing, this paper presents an intriguing finding: a frozen pre-trained LLM layer can process visual tokens for medical image segmentation tasks. Specifically, we propose a simple hybrid structure that integrates a pre-trained, frozen LLM layer within the CNN encoder-decoder segmentation framework (LLM4Seg). Surprisingly, this design improves segmentation performance with a minimal increase in trainable parameters across various modalities, including ultrasound, dermoscopy, polypscopy, and CT scans. Our in-depth analysis reveals the potential of transferring LLM's semantic awareness to enhance segmentation tasks, offering both improved global understanding and better local modeling capabilities. The improvement proves robust across different LLMs, validated using LLaMA and DeepSeek.

[Arxiv](https://arxiv.org/abs/2506.18034)