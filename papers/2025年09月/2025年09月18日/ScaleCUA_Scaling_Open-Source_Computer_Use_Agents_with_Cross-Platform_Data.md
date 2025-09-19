# ScaleCUA：基于跨平台数据扩展开源计算机使用智能体

发布时间：2025年09月18日

`Agent` `基础理论`

> ScaleCUA: Scaling Open-Source Computer Use Agents with Cross-Platform Data

# 摘要

> 视觉语言模型（VLMs）赋能的计算机使用智能体（CUAs）已能自主操作图形用户界面（GUIs），潜力巨大，但大规模开源计算机使用数据与基础模型的匮乏限制了其发展。本研究提出ScaleCUA，为开源CUAs的规模化发展迈出关键一步。该项目构建了涵盖6个操作系统、3个任务领域的大规模数据集，其闭环构建流程融合了自动化智能体与人类专家的协作。基于这些规模化数据训练后，ScaleCUA实现了跨平台无缝运行。具体而言，它在基线模型上实现显著提升（WebArena-Lite-v2提升+26.6，ScreenSpot-Pro提升+10.7），并刷新多项最先进结果（MMBench-GUI L1-Hard达94.4%，OSWorld-G达60.6%，WebArena-Lite-v2达47.4%）。这些成果凸显了数据驱动规模化对通用计算机使用智能体的重要作用。我们将开源数据、模型及代码以推动后续研究：https://github.com/OpenGVLab/ScaleCUA。

> Vision-Language Models (VLMs) have enabled computer use agents (CUAs) that operate GUIs autonomously, showing great potential, yet progress is limited by the lack of large-scale, open-source computer use data and foundation models. In this work, we introduce ScaleCUA, a step toward scaling open-source CUAs. It offers a large-scale dataset spanning 6 operating systems and 3 task domains, built via a closed-loop pipeline uniting automated agents with human experts. Trained on this scaled-up data, ScaleCUA can operate seamlessly across platforms. Specifically, it delivers strong gains over baselines (+26.6 on WebArena-Lite-v2, +10.7 on ScreenSpot-Pro) and sets new state-of-the-art results (94.4% on MMBench-GUI L1-Hard, 60.6% on OSWorld-G, 47.4% on WebArena-Lite-v2). These findings underscore the power of data-driven scaling for general-purpose computer use agents. We will release data, models, and code to advance future research: https://github.com/OpenGVLab/ScaleCUA.

[Arxiv](https://arxiv.org/abs/2509.15221)