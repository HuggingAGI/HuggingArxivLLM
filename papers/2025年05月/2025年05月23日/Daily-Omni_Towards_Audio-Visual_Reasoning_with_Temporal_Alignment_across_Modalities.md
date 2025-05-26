# Daily-Omni：迈向跨模态时序对齐的听视觉推理

发布时间：2025年05月23日

`Agent` `多模态` `跨模态`

> Daily-Omni: Towards Audio-Visual Reasoning with Temporal Alignment across Modalities

# 摘要

> 多模态大型语言模型（MLLMs）在视觉和音频任务上展现了令人瞩目的能力，但它们在同步处理跨模态信息方面仍有待探索。本文带来了三大创新：1) Daily-Omni，一个包含684个日常生活场景视频的音频-视觉问答数据集，拥有丰富的音频和视觉信息，涵盖6个主要任务的1197个问答对；2) Daily-Omni QA生成管道，通过自动标注、问答生成和优化，大幅提升了数据集的评估效率和扩展性；3) Daily-Omni-Agent，一个无需训练的代理，结合开源的视觉语言模型（VLM）、音频语言模型（ALM）和自动语音识别（ASR）模型，为基准测试奠定了基础。研究发现，当前MLLMs在音频-视觉整合任务上仍显不足，但通过简单的时序对齐技术结合VLMs和ALMs，性能可显著提升。更多内容请访问\href{https://github.com/Lliar-liar/Daily-Omni}{https://github.com/Lliar-liar/Daily-Omni}。

> Recent Multimodal Large Language Models (MLLMs) achieve promising performance on visual and audio benchmarks independently. However, the ability of these models to process cross-modal information synchronously remains largely unexplored. In this paper, we introduce: 1) Daily-Omni, an Audio-Visual Questioning and Answering benchmark comprising 684 videos of daily life scenarios from diverse sources, rich in both audio and visual information, and featuring 1197 multiple-choice QA pairs across 6 major tasks; 2) Daily-Omni QA Generation Pipeline, which includes automatic annotation, QA generation and QA optimization, significantly improves efficiency for human evaluation and scalability of the benchmark; 3) Daily-Omni-Agent, a training-free agent utilizing open-source Visual Language Model (VLM), Audio Language Model (ALM) and Automatic Speech Recognition (ASR) model to establish a baseline for this benchmark. The results show that current MLLMs still struggle significantly with tasks requiring audio-visual integration, but combining VLMs and ALMs with simple temporal alignment techniques can achieve substantially better performance. Codes and benchmark are available at \href{https://github.com/Lliar-liar/Daily-Omni}{https://github.com/Lliar-liar/Daily-Omni}.

[Arxiv](https://arxiv.org/abs/2505.17862)