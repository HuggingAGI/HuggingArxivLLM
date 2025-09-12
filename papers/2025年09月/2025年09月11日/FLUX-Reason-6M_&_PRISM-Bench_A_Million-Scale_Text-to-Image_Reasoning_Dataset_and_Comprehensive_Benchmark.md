# FLUX-Reason-6M 与 PRISM-Bench：百万级文本到图像推理数据集与综合基准

发布时间：2025年09月11日

`其他` `媒体与娱乐`

> FLUX-Reason-6M & PRISM-Bench: A Million-Scale Text-to-Image Reasoning Dataset and Comprehensive Benchmark

# 摘要

> 开源文本到图像（T2I）模型的发展一直受限于缺乏大规模、聚焦推理的数据集和全面的评估基准，因此与领先的闭源系统相比存在性能差距。为解决这一难题，我们推出了FLUX-Reason-6M数据集和PRISM-Bench（精确稳健图像合成测量基准）。FLUX-Reason-6M是一个海量数据集，包含600万张高质量FLUX生成图像和2000万条双语（中英文）描述，专为训练复杂推理能力设计。图像按六大核心特征分类：想象力、实体、文本渲染、风格、情感和构图，并配有明确的生成思维链（GCoT），详细拆解图像生成步骤。整个数据构建过程耗费15,000个A100 GPU天，为研究社区提供了此前仅大型工业实验室才能获取的资源。PRISM-Bench则提出了包含七个独特赛道的全新评估标准，其中包括使用GCoT的高难度长文本挑战。通过精心设计的提示词，该基准借助先进的视觉语言模型，对提示词与图像的对齐度及图像美学进行细腻且符合人类感知的评估。我们在PRISM-Bench上对19个主流模型的全面评估，不仅发现了关键的性能短板，还明确了亟需改进的方向。我们已公开数据集、基准和评估代码，旨在推动下一波聚焦推理的T2I生成技术发展。项目页面：https://flux-reason-6m.github.io/ 。

> The advancement of open-source text-to-image (T2I) models has been hindered by the absence of large-scale, reasoning-focused datasets and comprehensive evaluation benchmarks, resulting in a performance gap compared to leading closed-source systems. To address this challenge, We introduce FLUX-Reason-6M and PRISM-Bench (Precise and Robust Image Synthesis Measurement Benchmark). FLUX-Reason-6M is a massive dataset consisting of 6 million high-quality FLUX-generated images and 20 million bilingual (English and Chinese) descriptions specifically designed to teach complex reasoning. The image are organized according to six key characteristics: Imagination, Entity, Text rendering, Style, Affection, and Composition, and design explicit Generation Chain-of-Thought (GCoT) to provide detailed breakdowns of image generation steps. The whole data curation takes 15,000 A100 GPU days, providing the community with a resource previously unattainable outside of large industrial labs. PRISM-Bench offers a novel evaluation standard with seven distinct tracks, including a formidable Long Text challenge using GCoT. Through carefully designed prompts, it utilizes advanced vision-language models for nuanced human-aligned assessment of prompt-image alignment and image aesthetics. Our extensive evaluation of 19 leading models on PRISM-Bench reveals critical performance gaps and highlights specific areas requiring improvement. Our dataset, benchmark, and evaluation code are released to catalyze the next wave of reasoning-oriented T2I generation. Project page: https://flux-reason-6m.github.io/ .

[Arxiv](https://arxiv.org/abs/2509.09680)