# VoCap：基于任意提示的视频目标描述与分割

发布时间：2025年08月29日

`其他` `媒体与娱乐`

> VoCap: Video Object Captioning and Segmentation from Any Prompt

# 摘要

> 从细粒度定位掩码和详细语义属性出发理解视频中的对象，是视频理解的基础任务。本文提出VoCap——一种灵活的视频模型，它能输入视频和多种模态提示（文本、边界框或掩码），并生成时空掩码片段及对应的对象中心描述。因此，该模型可同时处理可提示视频对象分割、指代表达式分割与对象描述生成三项任务。由于该任务的数据获取繁琐且成本高，我们提出为现有大规模分割数据集（SAV）标注伪对象描述：利用视频的真实掩码预处理视频以突出感兴趣对象，再将其输入大型视觉语言模型（VLM）。为实现无偏评估，我们在验证集上收集了人工标注，由此得到的数据集被命名为SAV-Caption。我们在SAV-Caption数据集与其他多种图像、视频数据集的混合数据上，对VoCap模型进行了大规模训练。该模型在指代表达式视频对象分割任务上达到了当前最佳性能，在半监督视频对象分割任务上表现具有竞争力，同时为视频对象描述生成任务确立了基准。我们的数据集将公开于https://github.com/google-deepmind/vocap。

> Understanding objects in videos in terms of fine-grained localization masks and detailed semantic properties is a fundamental task in video understanding. In this paper, we propose VoCap, a flexible video model that consumes a video and a prompt of various modalities (text, box or mask), and produces a spatio-temporal masklet with a corresponding object-centric caption. As such our model addresses simultaneously the tasks of promptable video object segmentation, referring expression segmentation, and object captioning. Since obtaining data for this task is tedious and expensive, we propose to annotate an existing large-scale segmentation dataset (SAV) with pseudo object captions. We do so by preprocessing videos with their ground-truth masks to highlight the object of interest and feed this to a large Vision Language Model (VLM). For an unbiased evaluation, we collect manual annotations on the validation set. We call the resulting dataset SAV-Caption. We train our VoCap model at scale on a SAV-Caption together with a mix of other image and video datasets. Our model yields state-of-the-art results on referring expression video object segmentation, is competitive on semi-supervised video object segmentation, and establishes a benchmark for video object captioning. Our dataset will be made available at https://github.com/google-deepmind/vocap.

[Arxiv](https://arxiv.org/abs/2508.21809)