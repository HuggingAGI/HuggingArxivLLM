# 从寂静中听声：通过视觉语言模型从无声视频中生成音频描述

发布时间：2025年05月19日

`LLM应用` `计算机视觉` `音频处理`

> Hearing from Silence: Reasoning Audio Descriptions from Silent Videos via Vision-Language Model

# 摘要

> 人类能够直观地从无声视频中推断出声音，但多模态大语言模型是否能够在不依赖目标模态的情况下进行模态错配推理，这一问题仍相对未被探索。现有的文本辅助视频到音频（VT2A）方法在视频音效任务中表现出色，但在推理过程中获取音频描述时却面临困难。我们提出了从无声视频中推理音频描述（SVAD）的任务，以应对这一挑战，并研究视觉语言模型（VLMs）在该任务中的能力。为了进一步提升VLMs在SVAD任务中的推理能力，我们构建了CoT-AudioCaps数据集，并提出了一种基于链式思维的监督微调策略。在SVAD任务和后续的VT2A任务上的实验表明，我们的方法在两个关键方面表现出显著优势：显著提升了VLMs在SVAD任务中的模态错配推理能力，并有效解决了VT2A推理过程中获取音频描述的挑战。

> Humans can intuitively infer sounds from silent videos, but whether multimodal large language models can perform modal-mismatch reasoning without accessing target modalities remains relatively unexplored. Current text-assisted-video-to-audio (VT2A) methods excel in video foley tasks but struggle to acquire audio descriptions during inference. We introduce the task of Reasoning Audio Descriptions from Silent Videos (SVAD) to address this challenge and investigate vision-language models' (VLMs) capabilities on this task. To further enhance the VLMs' reasoning capacity for the SVAD task, we construct a CoT-AudioCaps dataset and propose a Chain-of-Thought-based supervised fine-tuning strategy. Experiments on SVAD and subsequent VT2A tasks demonstrate our method's effectiveness in two key aspects: significantly improving VLMs' modal-mismatch reasoning for SVAD and effectively addressing the challenge of acquiring audio descriptions during VT2A inference.

[Arxiv](https://arxiv.org/abs/2505.13062)