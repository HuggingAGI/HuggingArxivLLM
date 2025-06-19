# 视频版SALMONN 2：基于字幕增强的视听大语言模型

发布时间：2025年06月18日

`LLM应用` `视频处理` `人工智能`

> video-SALMONN 2: Captioning-Enhanced Audio-Visual Large Language Models

# 摘要

> 视频蕴含丰富的信息，生成自然语言下的详细准确描述是视频理解的核心。本文介绍 video-SALMONN 2——一款结合低秩适配（LoRA）的高级视听大语言模型，专为通过有向偏好优化（DPO）提升视频描述质量而设计。我们提出了新的评估指标，用于衡量视频描述的完整性和准确性，并通过 DPO 进行优化。为提升训练效果，我们创新性地提出多轮 DPO（MrDPO）方法：定期更新 DPO 参考模型，每轮训练（1,000 步）后合并并重新初始化 LoRA 模块以模拟参数更新，同时结合真实字幕指导以稳定训练。实验结果显示，MrDPO 将 video-SALMONN 2 的描述错误率降低了 28%。最终，仅拥有 70 亿参数的 video-SALMONN 2 在视频描述任务中超越 GPT-4o 和 Gemini-1.5-Pro 等领先模型，同时在视频问答基准测试中，与同规模模型的最先进水平相比，保持了极具竞争力的表现。代码可在 \href{https://github.com/bytedance/video-SALMONN-2}{https://github.com/bytedance/video-SALMONN-2} 获取。

> Videos contain a wealth of information, and generating detailed and accurate descriptions in natural language is a key aspect of video understanding. In this paper, we present video-SALMONN 2, an advanced audio-visual large language model (LLM) with low-rank adaptation (LoRA) designed for enhanced video (with paired audio) captioning through directed preference optimisation (DPO). We propose new metrics to evaluate the completeness and accuracy of video descriptions, which are optimised using DPO. To further improve training, we propose a novel multi-round DPO (MrDPO) approach, which involves periodically updating the DPO reference model, merging and re-initialising the LoRA module as a proxy for parameter updates after each training round (1,000 steps), and incorporating guidance from ground-truth video captions to stabilise the process. Experimental results show that MrDPO significantly enhances video-SALMONN 2's captioning accuracy, reducing the captioning error rates by 28\%. The final video-SALMONN 2 model, with just 7 billion parameters, surpasses leading models such as GPT-4o and Gemini-1.5-Pro in video captioning tasks, while maintaining highly competitive performance to the state-of-the-art on widely used video question-answering benchmarks among models of similar size. Codes are available at \href{https://github.com/bytedance/video-SALMONN-2}{https://github.com/bytedance/video-SALMONN-2}.

[Arxiv](https://arxiv.org/abs/2506.15220)