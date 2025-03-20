# Solla：迈向感知声学上下文的语音导向大型语言模型

发布时间：2025年03月19日

`LLM应用

摘要中提到的Solla框架扩展了大型语言模型处理多模态输入的能力，特别是语音和音频，属于应用层面的创新。因此，这篇论文被归类为LLM应用。` `语音处理` `音频分析`

> Solla: Towards a Speech-Oriented LLM That Hears Acoustic Context

# 摘要

> 大型语言模型 (LLMs) 不仅在文本处理方面表现出色，还能应对语音和音频等多模态输入。然而，现有模型多依赖文本指令分析输入，忽视了语音指令与音频混合输入的场景。为此，我们推出 Solla，一个能够同时解析语音问题并捕捉声学环境的创新框架。Solla 配备音频标签模块，精准识别和表征音频事件，并借助 ASR 辅助预测方法，提升对口语内容的理解。为了全面评估 Solla 与其他公开模型的性能，我们打造了 SA-Eval 基准数据集，涵盖音频事件分类、音频描述和音频问答三大任务。SA-Eval 包含多样化语音指令，融合多种说话风格，设有简单和困难两级难度，真实还原实际声学环境。实验结果表明，Solla 在简单与困难测试集上均与基线模型持平或更优，充分证明了其在语音与音频协同理解方面的卓越能力。

> Large Language Models (LLMs) have recently shown remarkable ability to process not only text but also multimodal inputs such as speech and audio. However, most existing models primarily focus on analyzing input signals using text instructions, overlooking scenarios in which speech instructions and audio are mixed and serve as inputs to the model. To address these challenges, we introduce Solla, a novel framework designed to understand speech-based questions and hear the acoustic context concurrently. Solla incorporates an audio tagging module to effectively identify and represent audio events, as well as an ASR-assisted prediction method to improve comprehension of spoken content. To rigorously evaluate Solla and other publicly available models, we propose a new benchmark dataset called SA-Eval, which includes three tasks: audio event classification, audio captioning, and audio question answering. SA-Eval has diverse speech instruction with various speaking styles, encompassing two difficulty levels, easy and hard, to capture the range of real-world acoustic conditions. Experimental results show that Solla performs on par with or outperforms baseline models on both the easy and hard test sets, underscoring its effectiveness in jointly understanding speech and audio.

[Arxiv](https://arxiv.org/abs/2503.15338)