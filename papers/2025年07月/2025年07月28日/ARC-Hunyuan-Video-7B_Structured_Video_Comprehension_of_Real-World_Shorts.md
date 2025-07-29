# ARC-Hunyuan-Video-7B：结构化视频理解模型探索真实世界短视频的奥秘

发布时间：2025年07月28日

`LLM应用` `社交媒体` `视频处理`

> ARC-Hunyuan-Video-7B: Structured Video Comprehension of Real-World Shorts

# 摘要

> 真实世界用户生成的短视频，特别是那些在微信频道和TikTok等平台上发布的短视频，在移动互联网中占据主导地位。然而，当前大型多模态模型缺乏有效的基于时间结构化、详细且深入的视频理解能力，而这正是有效视频搜索、推荐以及新兴视频应用的基础。理解真实世界的短视频实际上颇具挑战，因为它们具有复杂的视觉元素、视觉和音频中的高信息密度，以及快速节奏，专注于情感表达和观点传递。这需要先进的推理能力来有效整合视觉、音频和文本等多模态信息。在本研究中，我们引入了ARC-Hunyuan-Video，这是一种多模态模型，能够从原始视频输入中端到端处理视觉、音频和文本信号，以实现结构化理解。该模型具备多粒度时间戳视频描述、视频摘要、开放式视频问答、时间视频定位和视频推理的能力。通过来自自动标注管道的高质量数据，我们的70亿参数紧凑型模型通过全面的训练方案进行训练：预训练、指令微调、冷启动、强化学习（RL）后训练，以及最终的指令微调。在我们引入的ShortVid-Bench基准上的定量评估和定性比较表明，该模型在真实世界视频理解方面表现出色，支持零样本或基于少量样本的微调，适用于多种下游应用。我们的模型在实际生产中的部署带来了用户参与度和满意度的显著提升，这一成功得益于其卓越的效率，压力测试显示在H20 GPU上对一分钟视频进行推理仅需10秒。

> Real-world user-generated short videos, especially those distributed on platforms such as WeChat Channel and TikTok, dominate the mobile internet. However, current large multimodal models lack essential temporally-structured, detailed, and in-depth video comprehension capabilities, which are the cornerstone of effective video search and recommendation, as well as emerging video applications. Understanding real-world shorts is actually challenging due to their complex visual elements, high information density in both visuals and audio, and fast pacing that focuses on emotional expression and viewpoint delivery. This requires advanced reasoning to effectively integrate multimodal information, including visual, audio, and text. In this work, we introduce ARC-Hunyuan-Video, a multimodal model that processes visual, audio, and textual signals from raw video inputs end-to-end for structured comprehension. The model is capable of multi-granularity timestamped video captioning and summarization, open-ended video question answering, temporal video grounding, and video reasoning. Leveraging high-quality data from an automated annotation pipeline, our compact 7B-parameter model is trained through a comprehensive regimen: pre-training, instruction fine-tuning, cold start, reinforcement learning (RL) post-training, and final instruction fine-tuning. Quantitative evaluations on our introduced benchmark ShortVid-Bench and qualitative comparisons demonstrate its strong performance in real-world video comprehension, and it supports zero-shot or fine-tuning with a few samples for diverse downstream applications. The real-world production deployment of our model has yielded tangible and measurable improvements in user engagement and satisfaction, a success supported by its remarkable efficiency, with stress tests indicating an inference time of just 10 seconds for a one-minute video on H20 GPU.

[Arxiv](https://arxiv.org/abs/2507.20939)