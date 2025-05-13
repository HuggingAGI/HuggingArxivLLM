# 视觉指令微调结合兴趣区域链方法

发布时间：2025年05月11日

`LLM应用` `多模态` `计算机视觉`

> Visual Instruction Tuning with Chain of Region-of-Interest

# 摘要

> 高分辨率图像对提升多模态大语言模型的识别与理解能力至关重要。然而，直接提升图像分辨率会大幅增加计算需求。本研究提出了一种名为兴趣区域链（CoRoI）的视觉指令微调方法，旨在缓解高分辨率图像对模型的计算压力。灵感源于人类视觉系统的选择性特点，我们发现高分辨率图像中并非所有区域同等重要。CoRoI专注于识别并优先处理最具信息量的区域，从而提升多模态视觉理解和识别能力，同时避免处理冗长的高分辨率图像令牌。通过在11个基准测试上的广泛实验，我们验证了CoRoI在不同规模（从7B到34B参数）下的有效性。我们的模型在多样化的多模态基准测试和任务中表现优异。值得注意的是，我们的方法在几乎所有基准测试中均超越了LLaVA-NeXT，而经过微调的34B模型在六个基准测试上超过了如Gemini Pro 1.0等专有方法，并在MMB、SEED-I和MME上优于GPT-4V。

> High-resolution (HR) images are pivotal for enhancing the recognition and understanding capabilities of multimodal large language models (MLLMs). However, directly increasing image resolution can significantly escalate computational demands. In this study, we propose a method called Chain of Region-of-Interest (CoRoI) for Visual Instruction Tuning, aimed at alleviating the computational burden associated with high-resolution images for MLLMs. Drawing inspiration from the selective nature of the human visual system, we recognize that not all regions within high-resolution images carry equal importance. CoRoI seeks to identify and prioritize the most informative regions, thereby enhancing multimodal visual comprehension and recognition while circumventing the need for processing lengthy HR image tokens. Through extensive experiments on 11 benchmarks, we validate the efficacy of CoRoI across varying sizes, ranging from 7B to 34B in parameters. Our models consistently demonstrate superior performance across diverse multimodal benchmarks and tasks. Notably, our method outperforms LLaVA-NeXT on almost all benchmarks and our finetuned 34B model surpasses proprietary methods like Gemini Pro 1.0 on six benchmarks, as well as outperforming GPT-4V on MMB, SEED-I, and MME.

[Arxiv](https://arxiv.org/abs/2505.06840)