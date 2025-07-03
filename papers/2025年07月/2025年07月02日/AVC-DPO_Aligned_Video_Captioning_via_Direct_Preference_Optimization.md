# AVC-DPO：基于直接偏好优化的对齐视频字幕生成

发布时间：2025年07月02日

`LLM应用` `视频处理` `计算机视觉`

> AVC-DPO: Aligned Video Captioning via Direct Preference Optimization

# 摘要

> 视频多模态大语言模型（video MLLMs）在视频描述任务中虽然取得了显著进展，但如何根据人类偏好调整描述重点仍具挑战。为此，我们提出了基于直接偏好优化的对齐视频描述方法（AVC-DPO），这是一种后训练框架，旨在通过偏好对齐提升视频MLLM的描述能力。我们的方法设计了增强提示，特别针对时间动态和空间信息——人类在观看视频时关注的两个关键因素，从而融入以人为中心的偏好。AVC-DPO利用同一基础模型在不同提示条件下生成的描述响应，进行偏好感知训练和描述对齐。通过这一框架，我们在LOVE@CVPR'25 Workshop Track 1A: Video Detailed Captioning Challenge中取得了卓越表现，根据VDCSCORE评估指标，在视频详细描述（VDC）基准上获得了第一名。

> Although video multimodal large language models (video MLLMs) have achieved substantial progress in video captioning tasks, it remains challenging to adjust the focal emphasis of video captions according to human preferences. To address this limitation, we propose Aligned Video Captioning via Direct Preference Optimization (AVC-DPO), a post-training framework designed to enhance captioning capabilities in video MLLMs through preference alignment. Our approach designs enhanced prompts that specifically target temporal dynamics and spatial information-two key factors that humans care about when watching a video-thereby incorporating human-centric preferences. AVC-DPO leverages the same foundation model's caption generation responses under varied prompt conditions to conduct preference-aware training and caption alignment. Using this framework, we have achieved exceptional performance in the LOVE@CVPR'25 Workshop Track 1A: Video Detailed Captioning Challenge, achieving first place on the Video Detailed Captioning (VDC) benchmark according to the VDCSCORE evaluation metric.

[Arxiv](https://arxiv.org/abs/2507.01492)