# Q-智能体：借助强大的多模态大型语言模型，实现质量驱动的思考链图像修复智能体。

发布时间：2025年04月08日

`Agent` `图像处理` `计算机视觉`

> Q-Agent: Quality-Driven Chain-of-Thought Image Restoration Agent through Robust Multimodal Large Language Model

# 摘要

> 图像修复在现实场景中常面临噪声、模糊、压缩伪影和低分辨率等多种复杂且未知的降质问题。为特定降质训练特定模型可能导致泛化能力差。All-in-One模型虽能同时处理多种降质，但可能在某些类型上表现欠佳，且难以应对未见过的降质。现有IR代理依赖多模态大型语言模型（MLLM），采用耗时的回滚选择策略，却忽视了图像质量。因此，它们可能错误识别降质，并在进行不必要的修复任务时产生高昂的时间和计算成本，且修复顺序冗余。针对这些问题，我们提出了一种基于链式思维（CoT）修复的质量驱动代理（Q-Agent）。具体来说，Q-Agent由鲁棒的降质感知和质量驱动的贪心修复两部分组成。前者通过微调MLLM并使用CoT将多降质感知分解为单降质感知任务，从而增强MLLM的感知能力。后者则利用客观图像质量评估（IQA）指标来确定最优修复顺序并执行相应算法。实验结果生动展现，Q-Agent在图像修复性能上显著优于现有的All-in-One模型。


> Image restoration (IR) often faces various complex and unknown degradations in real-world scenarios, such as noise, blurring, compression artifacts, and low resolution, etc. Training specific models for specific degradation may lead to poor generalization. To handle multiple degradations simultaneously, All-in-One models might sacrifice performance on certain types of degradation and still struggle with unseen degradations during training. Existing IR agents rely on multimodal large language models (MLLM) and a time-consuming rolling-back selection strategy neglecting image quality. As a result, they may misinterpret degradations and have high time and computational costs to conduct unnecessary IR tasks with redundant order. To address these, we propose a Quality-Driven agent (Q-Agent) via Chain-of-Thought (CoT) restoration. Specifically, our Q-Agent consists of robust degradation perception and quality-driven greedy restoration. The former module first fine-tunes MLLM, and uses CoT to decompose multi-degradation perception into single-degradation perception tasks to enhance the perception of MLLMs. The latter employs objective image quality assessment (IQA) metrics to determine the optimal restoration sequence and execute the corresponding restoration algorithms. Experimental results demonstrate that our Q-Agent achieves superior IR performance compared to existing All-in-One models.

[Arxiv](https://arxiv.org/abs/2504.07148)