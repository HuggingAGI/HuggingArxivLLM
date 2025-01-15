# Omni-RGPT：利用标记实现图像与视频区域级理解的统一

发布时间：2025年01月14日

`LLM应用` `计算机视觉`

> Omni-RGPT: Unifying Image and Video Region-level Understanding via Token Marks

# 摘要

> 我们推出了 Omni-RGPT，一个多模态大型语言模型，旨在提升图像和视频的区域级理解能力。为了实现跨时空维度的一致区域表示，我们引入了 Token Mark，这是一组在视觉特征空间中突出目标区域的标记。这些标记通过区域提示（如框或掩码）直接嵌入空间区域，并同时融入文本提示以指定目标，从而在视觉和文本标记之间建立直接联系。为了进一步支持无需轨迹的稳健视频理解，我们引入了一个辅助任务，通过利用标记的一致性来指导 Token Mark，确保视频中的区域解释稳定。此外，我们还推出了一个大规模的区域级视频指令数据集（RegVID-300k）。Omni-RGPT 在图像和视频的常识推理基准测试中取得了领先成绩，并在字幕生成和指代表达理解任务中表现卓越。

> We present Omni-RGPT, a multimodal large language model designed to facilitate region-level comprehension for both images and videos. To achieve consistent region representation across spatio-temporal dimensions, we introduce Token Mark, a set of tokens highlighting the target regions within the visual feature space. These tokens are directly embedded into spatial regions using region prompts (e.g., boxes or masks) and simultaneously incorporated into the text prompt to specify the target, establishing a direct connection between visual and text tokens. To further support robust video understanding without requiring tracklets, we introduce an auxiliary task that guides Token Mark by leveraging the consistency of the tokens, enabling stable region interpretation across the video. Additionally, we introduce a large-scale region-level video instruction dataset (RegVID-300k). Omni-RGPT achieves state-of-the-art results on image and video-based commonsense reasoning benchmarks while showing strong performance in captioning and referring expression comprehension tasks.

[Arxiv](https://arxiv.org/abs/2501.08326)