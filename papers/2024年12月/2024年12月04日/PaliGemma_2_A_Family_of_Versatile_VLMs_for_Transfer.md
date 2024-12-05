# PaliGemma 2：一系列用于迁移的多功能 VLM

发布时间：2024年12月04日

`LLM应用` `视觉语言模型` `知识转移`

> PaliGemma 2: A Family of Versatile VLMs for Transfer

# 摘要

> 摘要：PaliGemma 2 是对 PaliGemma 开放视觉语言模型（VLM）基于 Gemma 2 系列语言模型的升级。我们把 PaliGemma 所用的 SigLIP-So400m 视觉编码器与整个 Gemma 2 模型系列（从 2B 到 27B 模型）相融合。我们分多个阶段以三种分辨率（224px、448px 和 896px）训练这些模型，让它们通过微调拥有广泛的知识转移能力。由此产生的涵盖不同模型大小和分辨率的基础模型系列，使我们能够探究影响转移性能的因素（如学习率），并分析任务类型、模型大小和分辨率之间的相互关系。我们还进一步增加了转移任务的数量和范围，超出了 PaliGemma 的范畴，包含不同的与 OCR 相关的任务，比如表格结构识别、分子结构识别、乐谱识别，还有长细粒度字幕和放射学报告生成，PaliGemma 2 在这些任务上都取得了顶尖的成果。

> 
Abstract:PaliGemma 2 is an upgrade of the PaliGemma open Vision-Language Model (VLM) based on the Gemma 2 family of language models. We combine the SigLIP-So400m vision encoder that was also used by PaliGemma with the whole range of Gemma 2 models, from the 2B one all the way up to the 27B model. We train these models at three resolutions (224px, 448px, and 896px) in multiple stages to equip them with broad knowledge for transfer via fine-tuning. The resulting family of base models covering different model sizes and resolutions allows us to investigate factors impacting transfer performance (such as learning rate) and to analyze the interplay between the type of task, model size, and resolution. We further increase the number and breadth of transfer tasks beyond the scope of PaliGemma including different OCR-related tasks such as table structure recognition, molecular structure recognition, music score recognition, as well as long fine-grained captioning and radiography report generation, on which PaliGemma 2 obtains state-of-the-art results.
    

[Arxiv](https://arxiv.org/pdf/2412.03555)