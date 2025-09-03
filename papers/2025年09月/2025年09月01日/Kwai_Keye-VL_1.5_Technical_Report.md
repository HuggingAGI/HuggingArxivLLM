# <翻译失败>

发布时间：2025年09月01日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> Kwai Keye-VL 1.5 Technical Report

# 摘要

> <翻译失败>

> In recent years, the development of Large Language Models (LLMs) has significantly advanced, extending their capabilities to multimodal tasks through Multimodal Large Language Models (MLLMs). However, video understanding remains a challenging area due to the dynamic and information-dense nature of videos. Existing models struggle with the trade-off between spatial resolution and temporal coverage when processing video content. We present Keye-VL-1.5, which addresses fundamental challenges in video comprehension through three key innovations. First, we introduce a novel Slow-Fast video encoding strategy that dynamically allocates computational resources based on inter-frame similarity, processing key frames with significant visual changes at higher resolution (Slow pathway) while handling relatively static frames with increased temporal coverage at lower resolution (Fast pathway). Second, we implement a progressive four-stage pre-training methodology that systematically extends the model's context length from 8K to 128K tokens, enabling processing of longer videos and more complex visual content. Third, we develop a comprehensive post-training pipeline focusing on reasoning enhancement and human preference alignment, incorporating a 5-step chain-of-thought data construction process, iterative GSPO-based reinforcement learning with progressive prompt hinting for difficult cases, and alignment training. Through extensive evaluation on public benchmarks and rigorous internal human assessment, Keye-VL-1.5 demonstrates significant improvements over existing models, particularly excelling in video understanding tasks while maintaining competitive performance on general multimodal benchmarks.

[Arxiv](https://arxiv.org/abs/2509.01563)