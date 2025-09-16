# EmoBench-Reddit：评估多模态大型语言模型情绪智能的分层基准

发布时间：2025年09月14日

`LLM应用` `媒体与娱乐`

> EmoBench-Reddit: A Hierarchical Benchmark for Evaluating the Emotional Intelligence of Multimodal Large Language Models

# 摘要

> 随着多模态大型语言模型（MLLMs）的飞速发展，其在各类视觉-语言任务中已展现出非凡实力。但目前的评估基准多聚焦于客观的视觉问答或图像描述，难以充分衡量模型对复杂主观人类情感的理解能力。为此，我们提出了EmoBench-Reddit——一个全新的分层多模态情感理解基准，旨在填补这一空白。该数据集精选自社交媒体平台Reddit的350个样本，每个样本均包含图像、用户配文及由用户标签确认的情感类别（悲伤、幽默、讽刺、快乐）。我们构建了一套从基础感知到高级认知层层递进的分层任务框架，每个数据点均设有六道选择题和一道难度递增的开放式问题。其中，感知任务用于评估模型对基本视觉元素（如颜色、物体）的识别能力，认知任务则要求模型进行场景推理、意图理解，并结合文本语境实现深度共情。我们结合AI辅助（Claude 4）与人工验证，确保了标注质量的可靠性。

> With the rapid advancement of Multimodal Large Language Models (MLLMs), they have demonstrated exceptional capabilities across a variety of vision-language tasks. However, current evaluation benchmarks predominantly focus on objective visual question answering or captioning, inadequately assessing the models' ability to understand complex and subjective human emotions. To bridge this gap, we introduce EmoBench-Reddit, a novel, hierarchical benchmark for multimodal emotion understanding. The dataset comprises 350 meticulously curated samples from the social media platform Reddit, each containing an image, associated user-provided text, and an emotion category (sad, humor, sarcasm, happy) confirmed by user flairs. We designed a hierarchical task framework that progresses from basic perception to advanced cognition, with each data point featuring six multiple-choice questions and one open-ended question of increasing difficulty. Perception tasks evaluate the model's ability to identify basic visual elements (e.g., colors, objects), while cognition tasks require scene reasoning, intent understanding, and deep empathy integrating textual context. We ensured annotation quality through a combination of AI assistance (Claude 4) and manual verification.

[Arxiv](https://arxiv.org/abs/2509.11101)