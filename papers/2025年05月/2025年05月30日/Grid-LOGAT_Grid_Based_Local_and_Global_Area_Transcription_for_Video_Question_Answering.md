# Grid-LOGAT：基于网格的局部与全局区域转录，专为视频问答设计

发布时间：2025年05月30日

`LLM应用` `问答系统`

> Grid-LOGAT: Grid Based Local and Global Area Transcription for Video Question Answering

# 摘要

> 本文提出了一种基于网格的局部和全局区域转录系统（Grid-LoGAT），专为视频问答（VideoQA）设计。该系统分为两个阶段：首先，利用视觉语言模型（VLM）从视频帧中提取文本转录；其次，通过大型语言模型（LLM）处理问题，生成答案。这种设计通过在边缘设备部署VLM、在云端部署LLM，有效保障了图像隐私。为提升转录质量，我们引入了基于网格的视觉提示方法，该方法从每个网格单元提取复杂局部细节，并与全局信息融合。实验结果表明，Grid-LoGAT在使用开源VLM（LLaVA-1.6-7B）和LLM（Llama-3.1-8B）时，在NExT-QA和STAR-QA数据集上分别以65.9%和50.11%的准确率，超越了具有相似基线模型的最先进方法。此外，我们在基于NExT-QA创建的定位问题上，Grid-LoGAT比非网格版本高出24个百分点。

> In this paper, we propose a Grid-based Local and Global Area Transcription (Grid-LoGAT) system for Video Question Answering (VideoQA). The system operates in two phases. First, extracting text transcripts from video frames using a Vision-Language Model (VLM). Next, processing questions using these transcripts to generate answers through a Large Language Model (LLM). This design ensures image privacy by deploying the VLM on edge devices and the LLM in the cloud. To improve transcript quality, we propose grid-based visual prompting, which extracts intricate local details from each grid cell and integrates them with global information. Evaluation results show that Grid-LoGAT, using the open-source VLM (LLaVA-1.6-7B) and LLM (Llama-3.1-8B), outperforms state-of-the-art methods with similar baseline models on NExT-QA and STAR-QA datasets with an accuracy of 65.9% and 50.11% respectively. Additionally, our method surpasses the non-grid version by 24 points on localization-based questions we created using NExT-QA.

[Arxiv](https://arxiv.org/abs/2505.24371)