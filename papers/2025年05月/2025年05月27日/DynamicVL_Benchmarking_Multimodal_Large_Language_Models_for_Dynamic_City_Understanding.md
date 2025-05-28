# DynamicVL：多模态大型语言模型在动态城市理解中的基准测试

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了多模态大语言模型在长期地球观测分析中的应用，展示了其在城市动态分析中的潜力，并提出了一个综合性的框架和数据集来提升模型的性能。这属于将大语言模型应用于特定领域的问题，因此归类为LLM应用。` `地球观测` `城市分析`

> DynamicVL: Benchmarking Multimodal Large Language Models for Dynamic City Understanding

# 摘要

> 多模态大语言模型在视觉理解方面展现了卓越的能力，但其在长期地球观测分析中的应用仍显不足，主要局限于单一时态或双时态图像。为填补这一空白，我们推出了DVL-Suite——一个基于遥感图像分析长期城市动态的综合性框架。该框架整合了覆盖美国42个特大城市、横跨2005年至2023年的15,063张高分辨率（1.0米）多时态图像，分为DVL-Bench和DVL-Instruct两大模块。DVL-Bench包含从基础变化检测（像素级别）到定量分析（区域级别），再到全面城市叙述（场景级别）的七大核心城市理解任务，涵盖城市扩张/转变模式、灾害评估及环境挑战等多样化动态。通过对17个当前先进的多模态大语言模型的评估，我们揭示了现有模型在长期时态理解与定量分析方面的诸多局限。为应对这些挑战，我们开发了DVL-Instruct——一个专注于多时态地球观测能力提升的指令微调数据集。基于此数据集，我们成功打造了DVLChat——一个能够实现图像级别问答与像素级别分割的基线模型，通过语言交互助力城市动态的全方位理解。

> Multimodal large language models have demonstrated remarkable capabilities in visual understanding, but their application to long-term Earth observation analysis remains limited, primarily focusing on single-temporal or bi-temporal imagery. To address this gap, we introduce DVL-Suite, a comprehensive framework for analyzing long-term urban dynamics through remote sensing imagery. Our suite comprises 15,063 high-resolution (1.0m) multi-temporal images spanning 42 megacities in the U.S. from 2005 to 2023, organized into two components: DVL-Bench and DVL-Instruct. The DVL-Bench includes seven urban understanding tasks, from fundamental change detection (pixel-level) to quantitative analyses (regional-level) and comprehensive urban narratives (scene-level), capturing diverse urban dynamics including expansion/transformation patterns, disaster assessment, and environmental challenges. We evaluate 17 state-of-the-art multimodal large language models and reveal their limitations in long-term temporal understanding and quantitative analysis. These challenges motivate the creation of DVL-Instruct, a specialized instruction-tuning dataset designed to enhance models' capabilities in multi-temporal Earth observation. Building upon this dataset, we develop DVLChat, a baseline model capable of both image-level question-answering and pixel-level segmentation, facilitating a comprehensive understanding of city dynamics through language interactions.

[Arxiv](https://arxiv.org/abs/2505.21076)