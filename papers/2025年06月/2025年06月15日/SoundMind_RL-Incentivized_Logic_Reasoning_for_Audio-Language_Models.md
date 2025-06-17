# SoundMind：强化学习激励的音频语言模型逻辑推理研究

发布时间：2025年06月15日

`LLM应用` `音频技术` `人工智能`

> SoundMind: RL-Incentivized Logic Reasoning for Audio-Language Models

# 摘要

> 尽管大型语言模型在推理领域展现出了强大的能力，但其在音频模态中的应用，尤其是大型音频语言模型（ALMs）领域，仍处于发展初期。针对这一研究空白，我们提出了一套系统性解决方案。首先，我们构建了音频逻辑推理（ALR）数据集，其中包含6,446个专门设计用于复杂推理任务的文本-音频标注样本。基于这一数据资源，我们开发了SoundMind——一种专为提升ALMs深度跨模态推理能力设计的规则强化学习（RL）算法。通过在ALR数据集上应用SoundMind算法对Qwen2.5-Omni-7B模型进行训练，我们在音频逻辑推理任务中取得了当前最佳性能。这项研究展示了高质量推理数据集与专用强化学习技术相结合的巨大潜力，为语言模型的听觉智能发展开辟了新的道路。我们的代码和数据集已开源，详情请访问https://github.com/xid32/SoundMind。

> While large language models have shown reasoning capabilities, their application to the audio modality, particularly in large audio-language models (ALMs), remains significantly underdeveloped. Addressing this gap requires a systematic approach, involving a capable base model, high-quality reasoning-oriented audio data, and effective training algorithms. In this study, we present a comprehensive solution: we introduce the Audio Logical Reasoning (ALR) dataset, consisting of 6,446 text-audio annotated samples specifically designed for complex reasoning tasks. Building on this resource, we propose SoundMind, a rule-based reinforcement learning (RL) algorithm tailored to endow ALMs with deep bimodal reasoning abilities. By training Qwen2.5-Omni-7B on the ALR dataset using SoundMind, our approach achieves state-of-the-art performance in audio logical reasoning. This work highlights the impact of combining high-quality, reasoning-focused datasets with specialized RL techniques, advancing the frontier of auditory intelligence in language models. Our code and the proposed dataset are available at https://github.com/xid32/SoundMind.

[Arxiv](https://arxiv.org/abs/2506.12935)