# FakeSV-VLM：借助渐进式混合专家适配器驾驭VLM实现虚假短视频新闻检测

发布时间：2025年08月27日

`LLM应用` `媒体与娱乐`

> FakeSV-VLM: Taming VLM for Detecting Fake Short-Video News via Progressive Mixture-Of-Experts Adapter

# 摘要

> 本文提出了FakeSV-VLM——一个基于视觉语言模型（VLM）的短视频平台假新闻检测新框架。尽管假新闻视频对公共信息安全构成严重威胁，人们已投入大量精力应对这一问题，但现有方法的检测精度仍有不足，根源在于缺乏验证新闻真实性的知识支撑。然而，大型视觉语言模型（VLMs）已从海量多模态数据中习得丰富的现实世界知识。受此启发，我们将先进的VLMs适配到短视频假新闻检测任务中。通过深入分析新闻样本，我们发现短视频可分为四种典型场景：视频与文本均真实（真实样本）、均虚假，或二者中任一项虚假（虚假样本）。基于这一发现，我们设计了四个专门应对各场景的“专家”，并通过混合专家（Mixture of Experts）机制将其集成到VLM中。具体而言，我们开发了渐进式MoE适配器（PMOE）模块：检测专家先进行初步分析，归因专家再展开全面诊断，最终形成可靠决策。此外，我们还注意到假新闻视频常存在模态间的不一致性，为此进一步设计了对齐驱动事件检查（ADEC）模块，通过捕捉不同模态间的矛盾来识别假新闻。在FakeSV和FakeTT两个基准数据集上的大量实验证实了该模型的优越性——它以3.32%和5.02%的性能提升显著超越现有最先进模型，为该领域树立了新标杆。

> We present FakeSV-VLM in this paper, a new VLM-based framework for detecting fake news on short video platforms. Despite significant efforts to combat this issue due to the severe threat that fake news videos pose to public information security, existing methods still fall short in detection accuracy, often due to lack of knowledge to verify the news is real or not. However, large Vision Language Models (VLMs) have absorbed extensive real-world knowledge from massive multimodal datasets. Motivated by this, we adapt advanced VLMs for fake news detection in short videos. Upon close examination of news samples, we observe that short video samples can be categorized into four distinct scenarios: both video and text are real (for real samples), or both are fake, or either the video or text is fake (for fake samples). Inspired by this insight, we design four experts tailored to handle each scenario and integrate them into VLM via Mixture of Experts. Specifically, we develop the Progressive MoE Adapter (PMOE) module where detection experts first provide an initial analysis, followed by attribution experts for a comprehensive diagnosis, leading to a robust decision. Additionally, we also note the fake news videos often show inconsistency between two modalities. Consequently, we further design the Alignment-driven Event Checking (ADEC) module, which perceives the fake news by capturing the inconsistency between different modalities. Extensive experiments on two benchmark datasets, FakeSV and FakeTT, verify the superiority of our model. It significantly outperforms current state-of-the-art models by +3.32% and +5.02%, establishing a new benchmark in the field.

[Arxiv](https://arxiv.org/abs/2508.19639)