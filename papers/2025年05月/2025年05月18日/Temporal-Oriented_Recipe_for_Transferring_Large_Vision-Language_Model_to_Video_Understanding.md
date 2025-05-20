# # 基于时间导向的大型视觉语言模型迁移至视频理解方案

发布时间：2025年05月18日

`LLM应用

理由：这篇论文主要探讨了大型视觉语言模型（LVLMs）在视频理解任务中的应用，特别是优化模型的时序理解能力。它属于将模型应用到具体任务中的范畴，因此归类为LLM应用。` `视频处理` `计算机视觉`

> Temporal-Oriented Recipe for Transferring Large Vision-Language Model to Video Understanding

# 摘要

> 近年来，大型视觉语言模型（LVLMs）取得了显著进展。然而，现有的模型在处理视频理解任务时，主要依赖其隐式的时序理解能力，尚未解析出关键的时序理解组件，这可能限制了其在视频理解方面的潜力。本研究通过全面的实证分析，揭示了影响LVLMs时序理解能力的关键因素。研究发现，视觉编码器与语言模型之间的中间接口是影响时序理解的核心。基于此，我们提出了一种以时序为导向的优化方案，包括专门的训练策略和增强的接口设计。最终，通过该方案开发的模型在标准视频理解任务中显著超越了现有模型。

> Recent years have witnessed outstanding advances of large vision-language models (LVLMs). In order to tackle video understanding, most of them depend upon their implicit temporal understanding capacity. As such, they have not deciphered important components that contribute to temporal understanding ability, which might limit the potential of these LVLMs for video understanding. In this work, we conduct a thorough empirical study to demystify crucial components that influence the temporal understanding of LVLMs. Our empirical study reveals that significant impacts are centered around the intermediate interface between the visual encoder and the large language model. Building on these insights, we propose a temporal-oriented recipe that encompasses temporal-oriented training schemes and an upscaled interface. Our final model developed using our recipe significantly enhances previous LVLMs on standard video understanding tasks.

[Arxiv](https://arxiv.org/abs/2505.12605)