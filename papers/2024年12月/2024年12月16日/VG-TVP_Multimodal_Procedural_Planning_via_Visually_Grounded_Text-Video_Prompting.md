# VG-TVP：借助基于视觉的文本-视频提示来实现多模态程序规划

发布时间：2024年12月16日

`LLM应用` `程序规划` `多模态`

> VG-TVP: Multimodal Procedural Planning via Visually Grounded Text-Video Prompting

# 摘要

> 大型语言模型（LLM）为基础的代理在程序任务中展现出良好前景，然而通过文本和视频增强的多模态指令辅助用户的潜力尚未充分挖掘。为弥补这一不足，我们提出了视觉基础的文本 - 视频提示（VG-TVP）方法，这是一种创新的由 LLM 赋能的多模态程序规划（MPP）框架。给定特定的高级目标，它能生成具有连贯性的文本和视频程序规划。主要挑战在于程序规划中实现文本和视觉的信息量、时间连贯性以及准确性。VG-TVP 借助 LLM 的零样本推理能力、视频字幕模型的视频转文本生成能力以及扩散模型的文本转视频生成能力。VG-TVP 通过提出新颖的字幕融合（FoC）方法，并运用文本到视频桥（T2V-B）和视频到文本桥（V2T-B），改善了模态间的交互。这使得 LLM 能够引导生成基于视觉的文本规划和基于文本的视频规划。鉴于适用于 MPP 的数据集稀缺，我们精心整理了一个名为日常生活任务程序规划（Daily-PP）的新数据集。我们开展了全面的实验和基准测试，以评估人类偏好（有关文本和视觉的信息量、时间连贯性以及规划准确性）。我们的 VG-TVP 方法在 Daily-PP 数据集上优于单模态基线。

> Large Language Model (LLM)-based agents have shown promise in procedural tasks, but the potential of multimodal instructions augmented by texts and videos to assist users remains under-explored. To address this gap, we propose the Visually Grounded Text-Video Prompting (VG-TVP) method which is a novel LLM-empowered Multimodal Procedural Planning (MPP) framework. It generates cohesive text and video procedural plans given a specified high-level objective. The main challenges are achieving textual and visual informativeness, temporal coherence, and accuracy in procedural plans. VG-TVP leverages the zero-shot reasoning capability of LLMs, the video-to-text generation ability of the video captioning models, and the text-to-video generation ability of diffusion models. VG-TVP improves the interaction between modalities by proposing a novel Fusion of Captioning (FoC) method and using Text-to-Video Bridge (T2V-B) and Video-to-Text Bridge (V2T-B). They allow LLMs to guide the generation of visually-grounded text plans and textual-grounded video plans. To address the scarcity of datasets suitable for MPP, we have curated a new dataset called Daily-Life Task Procedural Plans (Daily-PP). We conduct comprehensive experiments and benchmarks to evaluate human preferences (regarding textual and visual informativeness, temporal coherence, and plan accuracy). Our VG-TVP method outperforms unimodal baselines on the Daily-PP dataset.

[Arxiv](https://arxiv.org/abs/2412.11621)